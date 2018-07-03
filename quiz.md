# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the word 'polymorphism' mean?
    ___The ability of an object to take on many forms. For example when an object can be used in a parent class and a child class.___

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
    ___An object can be defined in a parent class and then referenced and used in a child class.___

3. What can we use to implement polymorphism in Java?
    ___Interfaces or parent/child classes.___

4. How many 'forms' can an object take when using polymorphism?


5. Give an example of when you could use polymorphism.
    ___An animal superclass has the methods eat and sleep, which all child classes of animals can use. Child classes contain more specific methods such as swim, climb, and hunt.___



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
    ___When classes contain instances implemented from other classes rather than a parent class___

7. When would you use composition? Provide a simple example in Java.
    ___A website is made up of available programs to download. Some are free, some cost money. The classes of programs that cost money implement a IPay interface that contains methods to take a payment___

8. What is/are the advantage(s) of using composition?
    ___A child class may not need everything from a parent class, so using an interface would make more sense. Composition doesn't require major restructuring when making changes.___

9. What happens to the behaviours when the object composed of them is destroyed?
    ___The behaviours will remain___
