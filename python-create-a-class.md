Python is an Object oriented programming language. It's code is mostly implemented through classes and thus through objects. Python programming helps you to reuse code, making it easy to maintain and scale. 
  
Use this guide to know how to create a Python class.
  
## What is a Class? 
  
A class is a template to objects. Objects are an encapsulation of variables and functions into an entity, which is an instance of a class. i.e A class contains related block
of code such as functions and variables stored within that object. Unlike a function, a class can contain properties (or variables) and/or methods (or functions). The functionalities are defined by setting attributes. A single class may have multiple objects. The process of creating an object is called instantiation.
  
#### Example
  
Consider a class `Personal_Information` which stores a person's information. In that case, a single person such as `Alekhya` is an instance of the class. `Personal_Information` class contains details about the person such as `first name`, `last name`, `age`, and so on as variables and can alos have functions such as .
  
## Class Definition
  
They are created using the keyword `class`.
  
### Syntax
  
``` python
class ClassName:

''' This is a docstring which briefly describes the class.'''

# methods
    
# functions
    
# more code
```

#### Note:
  
- First letter of a class should be capitalized.
   - **Example**: `Class_Name` or `ClassName` 
-  A class can be created withou any arguments. However, such class is of less use.
-  A class may contain list of statements such as functions and methods.
-  It's recommended to include a docstring, which has a brief description of the class. 

### Sample
  
``` python
class Personal_Inforamtion
  
# List of statements
```

A class creates a new local `namespace` where all its attributes are defined. 
  
## Defining class attributes

In a class, class attributes are varibles or properties. Class attributes are defined at class level and are shared by all instances of the class. They are defined outside class methods but within the class.

### Sample 

``` python

class Personal_Information:

  first_name = "Alekhya"
  
  last_name = "Sai"
  
  age = 20
```


There can also be special attributes that begin with double underscores `__`.

#### Example

__doc__ gives docstring of the class.

## Creating an Object

Once a class is defined, an object is created with the same name which can be used to instantiate new objects and access attributes. Object creation is simialr to a function call.

### Syntax

``` curl
objectName = ClassName ()
```

This creates a new object instance `ClassName` which can be used to access the attributes. 

### Sample 

``` python
personal_information_object = Personal_Inforamtion ()
print (Personal_Inforamtion.first_name)
```
### Output

``` curl
Alekhya
```

## Defining class methods


  
  
  
  
 
  
  
