# Python Classes

Python is an Object Oriented Programming (OOP) language. Its code is mostly implemented through classes and thus through objects. Python programming helps you to reuse code, making it easy to maintain and scale. 
  
Use this guide to know how to create a Python class.
  
## What is a Class? 
  
A class is a template for objects. Objects are an encapsulation of variables and functions into an entity, which is an instance of a class. i.e., A class contains a related code block such as functions and variables stored within that object. Unlike a function, a class can contain properties (or variables) and/or methods (or functions). The functionalities are defined by setting attributes. A single class may have multiple objects. The process of creating an object is called instantiation.
  
#### Example
  
Consider a class `Person_Information` which stores a person's information. In that case, a single person's details are an instance of the class. `Person_Information` class contains personal details such as `first_name`, `last_name`, `age` as variables and can also have functions such as `print_data ()`.
  
## Class Definition
  
A class is created using the keyword `class`.
  
### Syntax
  
``` python
class ClassName:

''' This is a docstring which briefly describes the class.'''

# variables
    
# functions
    
# more code
```

##### Note:
  
-   Capitalize the first letter of the class.
   - **Example**: `ClassName` 
-  You can create a class without any statements. However, such a class is of less use.
-  A class may contain a list of statements such as functions and methods.
-  It's recommended to include a docstring, which has a brief description of the class. 

### Sample
  
``` python
class PersonInformation
  
# List of statements
```

A class creates a new local `namespace` where all its attributes are defined. 
  
## Defining class attributes

In a class, class attributes are variables or properties. Class attributes are defined at the class level and are shared by all instances of the class. They are defined outside class methods but within the class.

### Sample 

``` python

class PersonInformation:

  first_name = "Alex"
  last_name = "Sa"
  age = 10
```

There can also be special attributes that begin with double underscores `__`.

#### Example

 - ` __doc__` gives docstring of the class.
 - `__init__()` is a special function that automatically executes when a class object initiates.

## Creating an Object

Once a class is defined, an object is created with the same name, which can  instantiate new objects and access attributes. Object creation is similar to a function call.

### Syntax

``` python
objectName = ClassName ()
```

This creates a new object instance, `ClassName`, which can be used to access the attributes. 

### Sample - [Try this](https://replit.com/@AlekhyaSasi/CreateClass#main.py)

``` python
person_information_object = PersonInformation ()
print (PersonInforamtion.first_name)
```

### output 

``` curl
Alex
```

## Defining class methods

Methods are functions you can define to access and modify the attributes.

### `__init__()` function

All classes have a built-in function called `__int__()` which automatically executes when a class is initiated. You can use this function to assign values to class attributes objects in runtime. This type of function is known as constructors in OOP. 

### Syntax

``` python

class ClassName:

''' This is a docstring which briefly describes the class.'''

# variables
    
def function_name (self, argument 1 ---- arguement n):

  # more code

``` 

##### Note:

- The `self` parameter is the first parameter of any function. You can name it anything but recommended to name as `self`.
- It's a reference to the current instance of the class and is used to access class variables.


### Sample

``` python

class PersonInformation:
  ''' This is a class with personal information such as first name, last name, and age.'''
  
  # Define an init method with variables to obtain value at runtime.
  def __init__(self, first_name, last_name, age):
    self.first_name = first_name
    self.last_name = last_name
    self.age = age
 
  # Define a method to display the values.
  def print_data(self):
    print("Person information:")
    print(f'Name: {self.first_name} {self.last_name}')
    print(f'Age: {self.age}')
    
 # Intializing an object.
person_information = PersonInformation("Alex", "Sa", 10)
 
person_information.print_data()

``` 

### Output

``` curl

Person information:
Name: Alex Sa
Age: 10

```









  
  
  
  
 
  
  
