# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the **_word_** 'polymorphism' mean?

Polymorphism is when something can have multiple or many forms. Polymorphism - "poly" meaning "many" and "morph" meaning change.

2. What does it mean when we apply polymorphism to OO design?

In OO design polymorphism allows us to treat different objects as if they are the same type.

3. What can we use to implement polymorphism in Java?

In Java we can use both inheritance and interfaces to implement polymorphism.

4. How many 'forms' can an object take when using polymorphism?

An object can take on multiple forms when using polymorphism.

5. Give an example of when you could use polymorphism.

An example could be when modelling a program for a fairground with various attractions such as a 'Rollercoaster', 'Dodgems' and "Water flume'.

We could use polymorphism to treat all the attractions as if they are the same object.

Using a method to calculate the price of the ride which can be called on any of the objects. The correct price will be calculated based on the specific ride's implementation of the method.

# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

Composition is when we see an object as being a part of another object. An object being made up of or composed of other objects.

7. When would you use composition? Provide a simple example in Java.

In Java a 'House' class can be composed of multiple components such as a 'Roof' object, a 'Windows' object and a 'Chimney' object. Each of these can be created seperately then combined together to form a complete 'House' object.

8. Give a difference between composition and aggregation?

Aggregation is similar to composition except that the objects can exist independently from the object which contains them.

We see composition as having a "part_of" relationship with ojects where as in aggregation the relationship is "has_a".

9. What is/are the advantage(s) of using composition/aggregation?

The advantages would be being able to reuse our code in multiple places. Reusing methods by combining them together.

Flexibility and modularity. The code can be broken down into smaller pieces being easier to undertand and maintain whilst being flexible in the sense that we can change or alter our objects without affecting the overall structure of the program.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

All the objects our object is composed of are also destroyed.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

When an object is destroyed the composed object can continue to exist independently.
