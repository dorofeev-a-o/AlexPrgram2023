class Student():
    def __init__(self, name, age, Class, fav_subj):
        self.name = name
        self.age = age
        self.Class = Class
        self.fav_subj = fav_subj
        self.Sex = "М"

    def Say_hallo(self):
        print(f"{self.fav_subj} мой любимый предмет")
