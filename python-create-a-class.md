# Python Classes

Python is an [Object Oriented Programming](https://en.wikipedia.org/wiki/Object-oriented_programming) (OOP) language. A class is a user-defined blueprint from which objects are created. Classes are best used to represent logical collection of attributes and methods.

In this article, learn to create a Python class and how to use it using a sample code.
  
## What is a Class? 
  
A class is a logical template to represent objects. Unlike a function, a class can contain properties (or fields) and/or methods (or functions). Objects are instances of such classes representing one or more entities. The functionalities are defined by setting the class attributes. The process of creating an object is called instantiation. A single class may have multiple objects.
  
#### Example
  
Consider a class `PersonInformation` which store people information. `PersonInformation` class contains personal details such as `first_name`, `last_name`, `age` as fields and can also have functions such as `print_data ()`. A single person's details are an instance of the class. 
  
## Class Definition
  
A class is created using the keyword `class`.
  
### Syntax
  
``` python
class ClassName:

''' This is a docstring which briefly describes the class.'''

# fields
    
# functions
    
# more code
```

##### Note:
  
-   Class names are written in [camel case](https://en.wikipedia.org/wiki/Camel_case).
   - **Example**: `ClassName` 
-  A class may contain a list of statements such as functions and methods.
-  You can also create a class without any statements. However, such a class is of less use.
-  It's recommended to include a docstring in the beginning, which briefly describes the functionality of the class. 

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

Once a class is defined, an object is created with the same name, which can instantiate new objects and access attributes. Object creation is similar to a function call.

### Syntax

``` python
objectName = ClassName ()
```

This creates a new object instance, `ClassName`, which can be used to access the attributes. 

### Sample 

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


### Sample - [Try this](https://replit.com/@AlekhyaSasi/CreateClass#main.py)

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

## Conclusion

In this article, You can learn about baisc concepts of classes in python. You can also view code samples on how to implement the constructors and methods in a class. Stay tuned for more informative articles.









  
  
  
  
 
  
  
