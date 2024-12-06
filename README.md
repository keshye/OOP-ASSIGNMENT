"# OOP-ASSIGNMENT" 
................QUESTION 1


class Superhero:
    def __init__(self, name, superpower, city):
        self.name = name
        self.superpower = superpower
        self.city = city


def save_the_day(self):
        return f"{self.name} is saving the day with their power of {self.superpower} in {self.city}!"


def introduce(self):
        return f"Hi, I'm {self.name}, the superhero of {self.city}!"


class Sidekick(Superhero):
    def __init__(self, name, superpower, city, main_hero):
        super().__init__(name, superpower, city)
        self.main_hero = main_hero


 def assist(self):
        return f"{self.name} is assisting {self.main_hero.name}!"


# Example usage

hero = Superhero("Captain Valor", "Super Strength", "Metropolis")
sidekick = Sidekick("Kid Courage", "Invisibility", "Metropolis", hero)


print(hero.introduce())
print(hero.save_the_day())
print(sidekick.introduce())
print(sidekick.assist())
................................QUESTION 2

class Vehicle:
    def move(self):
        raise NotImplementedError("Subclasses must implement this method")


class Car(Vehicle):
    def move(self):
        return "Driving 🚗"


class Plane(Vehicle):
    def move(self):
        return "Flying ✈️"


class Bicycle(Vehicle):
    def move(self):
        return "Pedaling 🚲"


# Example usage
vehicles = [Car(), Plane(), Bicycle()]


for vehicle in vehicles:
    print(vehicle.move())
#   o o p - a s s i g n m e n t 
 
 
