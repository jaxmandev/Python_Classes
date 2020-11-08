# OOP - Object Oriented Programming

## There are four pillars
```
1. Inheritance (most used) - Eliminates redundant code. We can use all functions and variable from parent class

2. Encapsulation - Reduce complexity and increase reusability. Also used to reduce access, making private methods/ variables etc.

3. Abstraction - Reduce complexity and isolate impact of changes.

4. Polymorphism (Many Forms) - Refactor code or case statements. It allows us to change behaviour or attributes / variables
```
## What are classes?:

- Class is the main factor that is used to implement any of these pillars
```
Class —> a template i.e. dog
Method —> a defined capability of a class i.e. bark()
Attribute —> a bit of data in a class i.e. length
Object or instance —> a particular instance of a class i.e. missy
```
### Creating a class
```
class Class_name:
    variable = "Something"

    def function(self):
        return "Something"
```
## Dog Class Example
```
#### Classes, objects and instanciation
#### How to create class
#### Syntax: class name_of_class starting with Capital letter
#### good naming convention is required
#### classes are a way to bring data and functionality together
```
```
class Dog:

    animal_kind = "Canine is running"   # defining class variable

    def bark(self):  # self refers to fido. in this case
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

```

## Other notes

```
# fname and lname are the Person class variables such as Person(fname, lname)
class Person:
  def __init__(self, fname, lname): 
  
    self.firstname = fname
    self.lastname = lname

# always use prefix self. when defining methods 
# because when it is then called self. liaise with the Class 
  def printname(self):
    print(self.firstname, self.lastname)

# use the Person class to create an object, and then execute the printname method:

x = Person("John", "Doe")
x.printname()
```
