# Object-Oriented Programming (OOPs)
## Introduction -
Object-Oriented Programming (**OOPs**) is a **programming paradigm** that relies on the concept of `classes and objects`. Everything in **OOPs** is associated with `classes and objects`, along with its attributes and methods. For example: in real life, a car is an `object`. The car has attributes, such as weight and color, and methods, such as drive and brake. `Class` is used to structure a software program into **simple** and **reusable** pieces of code blueprints, which are used to create individual instances of `objects`. There are many _**OOPs**_ languages including _Ruby, JavaScript, C++, Java_, and _Python_, etc.

## OOPs Concepts -
There are basically **six** concepts of OOPs, are given below:
- Class
- Object
- Polymorphism
- Inheritance
- Encapsulation
- Abstraction

>If the `Inheritance` concept is allowed by any programming language along with the above other five concepts then that programming language is known as **Object-Oriented Programming** language. But if all the concepts are allowed except Inheritance then that programming language is known as **Object-Based Programming** language.

![GeeksforGeeks Image](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20190717114649/Object-Oriented-Programming-Concepts.jpg)

## Class and Object -
An object-oriented programming language involves `classes and objects`. A `class` is the **blueprint** from which individual `objects` are created and defines the variables and the methods common to all objects of a certain kind. We can understand better with the help example code in _Ruby_ given below:
```ruby
# Ruby program to illustrate the class and object

# defining class Car 
class Car
    # defining method 
    def brands
        puts "BMW"
        puts "Audi"
    end
end
# creating object 
obj=Car.new
# calling method using object 
obj.brands

```
```
Output:

BMW
Audi
```
## Polymorphism -
**Polymorphism** is one of the fundamental features of object-oriented programming. **Polymorphism** is made up of two words **Poly** which means *Many* and **Morph** which means *Forms*. So we can obtain different results using the same function by passing different input objects.
There are two types of **Polymorphism**-
- **Static Polymorphism**
  - linking of a function with an `object` during *compile-time*.
  - also known as **Static Binding**.
  - _Method Overloading_ and _Operator Overloading_ are the examples of **Static Polymorphism**.
- **Dynamic Polymorphism**
  - linking of a function with an `object` during _run-time_.
  - also known as **Run-time Polymorphism**.
  - Method Overriding and Duck Typing are examples of **Dynamic Polymorphism**.
  

> In the Ruby programming language, Polymorphisms can be performed in two ways:
> - By the use of **Inheritance** (_Method Overriding_)
> - By the use of **Duck Typing**
```ruby
# Ruby program of polymorphism using Duck typing 

# Creating three different classes 
class Hotel 
    def enters 
	    puts "A customer enters"
    end
    def type(customer) 
    	customer.type 
    end
    def room(customer) 
    	customer.room 
    end
end

# Creating class with two methods 
class Single 
    def type 
	    puts "Room is on the fourth floor."
    end
    def room 
    	puts "Per night stay is 5 thousand"
    end
end
class Couple 
    # Same methods as in class single 
    def type 
    	puts "Room is on the second floor"
    end
    def room 
	    puts "Per night stay is 8 thousand"
    end
end

# Creating Object 
# Performing polymorphism 
hotel= Hotel.new
puts "This visitor is Single."
customer = Single.new
hotel.type(customer) 
hotel.room(customer) 

puts "The visitors are a couple."
customer = Couple.new
hotel.type(customer) 
hotel.room(customer) 
```
```
Output:

This visitor is Single.
Room is on the fourth floor.
Per night stay is 5 thousand
The visitors are a couple.
Room is on the second floor
Per night stay is 8 thousand
```
## Inheritance -
In an object-oriented programming language, `Inheritance` is one of the most important features. It allows us to inherit the characteristics of one class into another class. It provides the concept of *Reusability*. It is a **mechanism** where you can derive a `class` from another `class` for a hierarchy of classes that share a set of attributes and methods.
There are basically the following types of `Inheritance` given below:
- Single Inheritance
- Multiple Inheritance
- Multi-level Inheritance
- Hierarchical Inheritance
- Hybrid Inheritance

![Inhertitance](https://intellipaat.com/wp-content/uploads/2015/09/inheritance-types.png)

>_Ruby_ supports only single class inheritance, it does not support multiple class inheritance but it supports **mixins**. The **mixins** are designed to implement multiple inheritances in _Ruby_, but it only inherits the interface part.

In _Ruby_, a subclass is derived from the superclass with the help of the `<` operator.
```
sub_class > super_class
```
```ruby
# Ruby program to demonstrate the Inheritance 

# Super class or parent class 
class SuperClass 
	# constructor of super class 
	def initialize 	
		puts "This is Superclass"
	end
	# method of the super class 
	def super_method 
		puts "Method of superclass"
	end
end

# subclass or derived class 
class SubClass < SuperClass 
	# constructor of deriver class 
	def initialize 
	    puts "This is Subclass"
	end
end

# creating object of superclass 
SuperClass.new
# creating object of subclass 
sub_obj = SubClass.new
# calling the method of super class using sub class object 
sub_obj.super_method 
```
```
Output:

This is Superclass
This is Subclass
Method of superclass
```


## Encapsulation -
`Encapsulation` is defined as the wrapping up of data under a single unit. It is the mechanism that binds together **data** and **methods**. It describes the idea of bundling **data** and **methods** that work within one unit.
```ruby
# Ruby program to illustrate encapsulation 
class Demoencapsulation 
    def initialize(id, name, addr) 		
        # Instance Variables	 
        @cust_id = id 
        @cust_name = name 
        @cust_addr = addr 
    end
    # displaying result 
    def display_details() 
        puts "Customer id: #@cust_id"
        puts "Customer name: #@cust_name"
        puts "Customer address: #@cust_addr"
    end
end

# Create Objects 
cust1 = Demoencapsulation .new("1", "Shivam", 
			"Deoria, Uttar Pradesh, India") 

cust2 = Demoencapsulation .new("2", "Rohit",
            "Rohtak, Haryana, India") 
	
# Call Methods 
cust1.display_details() 
cust2.display_details() 

```
```
Output:

Customer id: 1
Customer name: Shivam
Customer address: Deoria, Uttar Pradesh, India
Customer id: 2
Customer name: Rohit
Customer address: Rohtak, Haryana, India
```
## Abstraction -
The idea of representing **significant details** and hiding details of functionality is called data `Abstraction`. It is a concept of hiding the complexities of a system from the users of that system.

```ruby
# Ruby program to demonstrate Data Abstraction 

class AbstractClass
	# defining publicMethod 
	public 
	def publicMethod 
		puts "In Public!"
		# calling privateMethod inside publicMethod 
		privateMethod 
	end
	# defining privateMethod 
	private 
	def privateMethod 
		puts "In Private!"
	end
end

# creating an object of class Geeks 
obj = AbstractClass.new

# calling the public method of class Geeks 
obj.publicMethod 
```
```
Output:

In Public!
In Private!
```
# References
Referencs | Links
------------ | -------------
Reference 1 | https://www.tutorialspoint.com/ruby/index.htm
Reference 2 | https://medium.com/launch-school/the-basics-of-oop-ruby-26eaa97d2e98
Reference 4 | https://www.rubyguides.com/ruby-tutorial/
Reference 5 | https://www.javatpoint.com/ruby-tutorial
Reference 6 | https://www.codecademy.com/learn/learn-ruby
Reference 7 | https://www.ruby-lang.org/en/documentation/quickstart/
