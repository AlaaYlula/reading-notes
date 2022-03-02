# Inheritance and Interfaces
  
### Inheritance
>Different objects may has some common features additional to the features that make them different.  
>>So the OOP allaw the classes to Inherit the commonly used state and behavior from other classes.  
>>The syntax for creating a subclass: the name of class(we called it subclass) then **extends** then the name of the class inherit from(we >>called it superClass).  
  
> Method Overriding in Java Inheritance
>>if the same method is present in both the superclass and subclass, the method in the subclass overrides the method in the superclas.  
>>This concept is known as method overriding in Java.
>>we can use the **super** keyword with the method of the parent class from the same method of the child class, so the method in the parent class will execute.  
>>If a class includes **protected** fields and methods, then these fields and methods are accessible from the subclass of the class.
<!-- https://www.programiz.com/java-programming/inheritance#:~:text=Example%201%3A%20Java%20Inheritance&text=Rohu%22%3B%20labrador.-,eat()%3B,the%20object%20of%20the%20Dog%20. -->

> Java Abstract Class and Abstract Methods  
>> Cannot create objects of abstract classes.  
>> A method that doesn't have its body is known as an **abstract method**. We use the same abstract keyword to create abstract methods.  
>>If a class contains an abstract method, then the class should be declared abstract. Otherwise, it will generate an error.  
  
  
### Interface  
>Interface Body can contain only constants, method signatures, default methods, static methods, and nested types.
>>public *interface* NameInterface *extends* ParentInterface(if there any) { the methods with empty bodies and The compiler will now require that methods all be implemented}.
>Implementing an Interface  
>>In the class decleration we used the **implements** keyword then the name of the interface. 
>Using an Interface as a Type  
>>Any object you assign to it must be an instance of a class that implements the interface.  
>If you make change in interface, then all classes that implement the old interface will break because they no longer implement the old interface. If you want to add additional methods to an interface, You could create a new interface that extends the old interface. **OR** you can define the new methods as *default* methods.  

