# EXPLANATION OF POLYMORPHISM TO A FIVE YEAR OLD

Let's take for instance we have what we call an ice cream which is always delicious, cold and yummy and we have different 

types of ice cream which are;

* Mochi Ice Cream
![Mochi Ice Cream](https://res.cloudinary.com/layitheinfotechguru/image/upload/v1614689651/mochi_image_pnwsr6.jpg)
* Gelato
![Gelato](https://res.cloudinary.com/layitheinfotechguru/image/upload/v1614689649/gelato_h0svlf.jpg)
* Frozen Yogurt
![Frozen Yogurt](https://res.cloudinary.com/layitheinfotechguru/image/upload/v1614689648/frozen_yogurt_qi7t3a.jpg)
* Sorbet
![Sorbet](https://res.cloudinary.com/layitheinfotechguru/image/upload/v1614689655/Sorbet_qamdif.jpg)
* Sherbet
![Sherbet](https://res.cloudinary.com/layitheinfotechguru/image/upload/v1614689660/sherbet_zxgqu0.jpg)

We have an ice cream truck that comes to your house everyday, when you tell the truck driver you want frozen yogurt the truck

driver knows you want EXACTLY frozen yogurt because frozen yogurt would differ in terms of taste, look, crispiness, smell when

you compare it to other types of ice cream, and that same truck driver when you ask for Gelato he gives you EXACTLY Gelato

and it goes on like that depending on the type of ice cream you want.

But what you should note here is that the word ice cream can be used to point or give you access to a particular type of ice cream or other types of ice cream,

including future types of ice cream we haven't seen yet or that have being created.

# POLYMORPHISM IN TECHNICAL TERM

Polymorphism is the provision of a single interface to entities of different types

or the use of a single symbol to represent multiple different types.

In respect to Inheritance,when you define a supertype for a group of classes, any subclass

of that supertype can be substituted where the supertype is expected. Because you get to refer to a 

subclass object using a reference declared as the supertype.

When we have a particular class it is important to know that the reference type AND the object

type are the same. e.g Dog myDog = new Dog ( ); in this example, both are Dog.

With polymorphism, the reference type can be a superclass of the actual object type.

e.g Animal myDog = new Dog (); i.e Animal is the parent or superclass of Dog.

When you declare a reference variable, any object that passes the IS-A test for the declared type of the reference variable

can be assigned to that reference. 

In other words, anything that extends the declared reference variable type can be assigned to the reference

variable. This allows us to do things like make polymorphic arrays.
