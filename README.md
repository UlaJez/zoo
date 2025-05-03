# Zoo managment

# Mano sukurta programa yra skirta virtualaus zoologijos sodo valdymui, naudojant objektinio programavimo principus.

# Kaip naudotis programa
1. Paleisti programą.

2. Susikurti norimus gyvūnus, zoologijos sodo prižiūrėtojus, priskirti prižiūrėtojams gyvunus ir t.t.

3. Išsaugoti duomenis.

4. Išeiti.

Zoologijos sodo duomenys bus issaugoti faile "zoo_data.txt", o vėliau iš šio failo bus skaitomi duomenys ir bus galima tęsti zoologijos sodo papildymą.

# Reikalavimai:
+ Polymorphism
+ Abstraction
+ Inheritance
+ Encapsulation

# Polimorfizmas
Polimorfizmas reiškia, kad skirtingos klasės gali naudoti tą patį metodą, bet kiekviena jį įgyvendina savo būdu.

Mano kode polimorfizmą galime pastebėti šiose vietose:
```python
class Lion(Animal):
    def make_sound(self):
        return "ROAR!"

class Penguin(Animal):
    def make_sound(self):
        return "Honk honk!"

class Monkey(Animal):
    def make_sound(self):
        return "Ooh ooh ah ah!"
```
Kreipiantis į metodą make_sound, gražinami skirtingi gyvunų garsai.

