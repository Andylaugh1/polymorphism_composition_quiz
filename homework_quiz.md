Polymorphism
What does the word 'polymorphism' mean?
- Polymorphism is from Greek words "Poly" and "Morphism" which mean "many" and "forms" respectively.
Therefore it means to be able to take on multiple forms in different situations.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
- Polymorphism means that an object can pass more than one "is-a" test
- An example of polymorphism would be an object acting as two different types of object in two different settings.
 - for example a printer object can be a printer, and at the same be simply a 'device' in an array of devices
 - Methods can also be polymorphic and two versions of the same methods can be used on the same class

What can we use to implement polymorphism in Java?
- We can use classes, interfaces and arrays.

How many 'forms' can an object take when using polymorphism?
- It can take many forms. There is not a specific limit.

Give an example of when you could use polymorphism.
- In the printer example above
- Another example would be if you had numerous food subclasses which all called a '.eat method'. You could put new sub-class objects inside one Array or ArrayList using the parent class, and loops through those objects to call the .eat method which applies in the sub-classes




Composition
What do we mean by 'composition' in reference to object-oriented programming?
- Composition references an object, or class, which is composed, or partially composed, of other objects, which themselves have behaviours the initial class requires.
- It refers to the idea that when an object uses another object/class as part of it's properties, it can also achieve the functionalities of those property objects

When would you use composition? Provide a simple example in Java.
- In composition the object/property relationship should be a "has-a" relationship
- You may use composition when creating a car object - as the car object may be composed (made up of) of properties which themselves are objects. Eg an engine object, tyre objects,
- A better example might be blood and bloodcells - when the blood goes the bloodcells die.


What is/are the advantage(s) of using composition?
- The advantage of using composition is that often is can add simplicity to a project and reduce the need for lots of inheritance, which can be confusing and require a lot of refactoring later on.
- Rather than having a class which has all the functionality, an object can be composed of objects which have the desired functionality in them (eg to start the car object, rather than have a start method in the car class, you would actually put the start method in the car's property object - the engine)

What happens to the behaviours when the object composed of them is destroyed?
- They are lost too
