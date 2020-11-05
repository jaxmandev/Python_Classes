OOP - Object Oriented Programming

There are four pillars

Inheritance (most used)
Encapsulation
Abstraction
Polymorphism - refers to a programming languages ability to process objects differently depending on their data type or class. More specifically, it is the ability to redefine methods for derived classes.
What are classes?:

Class is the main factor that is used to implement any of these pillars
Creating a class

class Class_name:
    variable = "Something"

    def function(self):
        return "Something"
Dog Class Example

# Classes, objects and instantciation

# How to create class
# Syntax: class name_of_class starting with Capital letter
# good naming convention is required

# classes are a way to bring data and functionality together
class Dog:

    animal_kind = "Canine is running"   # defining class variable

    def bark(self):  # self refers to current class
        return "woof"

# in order to execute a class we have to create an object of this class
fido = Dog()  # Creating an object of our Dog class

print(fido)
print(fido.animal_kind) # Fido is a canine
print(fido.bark()) # Fido barks woof

print("Below are lassie's results objects ")
lassie = Dog() # Creating an object of our Dog class
print((lassie.bark()))
print(lassie.animal_kind)

fido.animal_kind = "Big Dog"
# Changing the animal_kind for fido
# will not have any impact on the main Dog() class, so will not impact lassie
print("fido changed to Big Dog -----> " + fido.animal_kind)
print("lassie is unaffected -----> " + lassie.animal_kind)
Task - Cat Class

# Create a Cat class

# one function that returns "MEOWWWW"

# Create 2 class level variable
# Create 3 objects
# Display all information with each object
# Change the class variable values in each object and display
# Pseudo code each block of code

class Cat:

    animal_kind = "feline"

    tendency = "cuddly"

    def meow(Self):
        return "MEOWWWW"

# Creating 3 objects i.e. cats
ginger = Cat()
max = Cat()
frankie = Cat()

# Changing the variables for each object and then displaying the changes
# for every cat with the MEOWWWW remaining the same
ginger.animal_kind = "BIG feline"
ginger.tendency = "a little wuss"

print(f"ginger is a -----> " + ginger.animal_kind)
print(f"ginger has a tendency to be ------> " + ginger.tendency)
print("meow??   "+ ginger.meow())


max.animal_kind = "small feline"
max.tendency = "scratch scratch"

print(f"max is a -----> " + max.animal_kind)
print(f"max has a tendency to ------> " + max.tendency)
print("meow???   "+ max.meow())

frankie.animal_kind = "wild feline"
frankie.tendency = "a bit wild"

print(f"frankie is a -----> " + frankie.animal_kind)
print(f"frankie has a tendency to be ------> " + frankie.tendency)
print("meowww????    "+ frankie.meow())
