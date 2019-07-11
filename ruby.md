# Ruby Assessments

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What is a method in Ruby? How is it different or similar to functions in JavaScript?
my answer:
A method in ruby is every single thing, this is because every command in ruby is considered a method vs. JS where methods are mainly only found inside the body.

Googled:
A method in ruby is a set of expressions thst returns a value. 

#### 2. What does it mean that a class inherits from another class? Try to explain Ruby inheritance. 


[Your Answer]
A class inheriting from another class in ruby means that classes can access and use the superclass method.

[Googled Answer]
Inheritance in ruby provides the concept of reusability. If a programmer wants to create a new class and there is a class that already includes some of the code that programmer wants then they can derive a new a class from the exisitng class. This increases the ruse of the fields and methods of the exisitng class without creating extra code. 

#### 3. What is rspec and what is the general process for writing tests in RSpec?

//Your Answer

Its similar to yarn test for JS react in the sense that it can allow you to test your code as you're creating it in order to prevent malfunctions and bugs harder to find once you have huge lines of code.

//Googled Answer
RSPEC ios a testing tool for ruby, create for behavior-driven development. It is the most frequently used testing library for ruby in production applications.


#### 4. Name three possible non-inheritance relationships between ruby objects? 

//Your Answer
- belongs to 
- has a
- has many

//Googled Answer
- belongs to
- has many of each
- has many through

#### 5. What do we call the #{} convention used below? What is it accomplishing?

```ruby
x = 1022
puts "I am printing a random number #{x}"
```

it's the operator used for interpolation inside double-quoted strings. It allows for you to put ruby code within a string so:
"three plus three is #{3+3}""
would output:
"three plus three is 6"

#### 6. How do you feel about testing right now? What potential pros/cons/barriers/advantages do you see to implementing BDD in your own code?

//Your Answer
It's tedious but extremely benificial to pushing your projects forward.


//Googled Answer
Rspec is good for testing models, controllers, and views as well as unit testing.
RSpec includes traditional Unit Testing, which means testing a class or part of the application in isolation from the rest of the application.
RSpec used for Acceptance Testing known as TDD (Test Driven Development) or BDD (Behaviour Driven Development) Specification.  These are support business-case driven Integration Tests.
#### 7. What is an instance variable in Ruby? How is it different from a normal, local variable?

//Your Answer
instance variables have a scope throughout an instance of a class.
//Googled Answer

An instance variable has a name beginning with @ , and its scope is confined to whatever object self refers to. 
Two different objects, even if they belong to the same class, are allowed to have different values for their instance variables.
Local variables can only be accessed in a specific, local environment. A local variable that is defined inside one method, for example, cannot be accessed by another method.
In order to get around this limitation, we can use instance variables inside our Ruby classes.
An instance variable is a variable that is accessible in any instance method in a particular instance of a class.

#### 8. Ruby has a great community and tons of free resources to help you learn. Here is the long list of great resources: https://www.ruby-lang.org/en/documentation/. Below are a few popular ones:
- Interactive Ruby tutorial (http://tryruby.org/levels/1/challenges/0)
- Why's (poigniant) Guide to Ruby: comics, anecdotes, and microscopic canaries (http://poignant.guide/book/chapter-1.html)
- Ruby in 20 min (https://www.ruby-lang.org/en/documentation/quickstart/)


Choose one of these resources and go through the material (not for hours, only looking for around 10min of your time) then come back here and list a few new things you learned about Ruby.
