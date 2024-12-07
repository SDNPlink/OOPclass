## 04

- Name: Sierra Norstrom
- Class: 2143 OOP

## Definitions

#### Abstract Classes and Interfaces

>
>
>

#### Abstraction

> Allows only certain information to be shown with access modifiers

#### Access Modifiers (Public, Private, Protected)

> Allows what can be accessed outside of a class,  
> public - everything available to everyone  
> private - everything available to current class, or a friend class  
> protected - everything available to current class, its subclasses, or a friend class  
> ```
> class Test
> {
>   private:
>     data;
>   protected:
>     data2;
>   public:
>     data3;
> };

#### Attributes / Properties

> Defines a property of an object/element/file, usually consists of a name and value
> 
> ![attributes](https://github.com/user-attachments/assets/f8159b09-35ac-479d-bf63-23fe0a67e07e)

#### Class Variable

> A Variable defined in a class, and belongs to the class, only one instance that is shared across all instances of the class
> 
>![class variable](https://github.com/user-attachments/assets/58177bb5-4887-465d-ade1-0e9f2e507d53)

#### Classes and Objects

> Basic data types in C++, with classes holding their own data members and functions, while an object is a declared version of a class
> 
>![classesobjects](https://github.com/user-attachments/assets/f6512b88-027c-40be-80c7-adf45990ff62)
>```
>class person
>{
>  data;
>};
>int main()
>{
>  person Dave;
>}

#### Collections and Iterators

>
>
>

#### Composition

> Combining objects/classes to create more complex versions  
> Contrasts with Inheritance, is an "has-a" relationship
> 
>![Composition](https://github.com/user-attachments/assets/ba6bb648-c29e-4eb1-a73f-85165f5148fc)
>```
>class wheel
>{
>  data;
>};
>class car
>{
>  wheel wheels;
>};

#### Constructors and Destructors

> A Constructor initializes an object of a class, it is used to allocate memory for an object
> A Destructor deallocates memory of an object, uses a '~'  
>```
>class Thing
>{
>  public:
>    Thing()
>      { }
>    ~Thing()
>      { }
>};

#### Design Patterns (e.g., Singleton, Factory, Observer)

>
>
>

#### Encapsulation

> Combining similar data and functions into one class, usually limits access to its own objects
> 
>![encapsulation](https://github.com/user-attachments/assets/6eb8212e-0ba5-46a3-9941-df1bbdcc3b44)
>```
>class Square
>{
>  private:
>    int length;
>  public:
>    void setLength(int)
>      {
>        code;
>      }
>};
>int main()
>{
>  Square s1;
>  s1.setLength(2);
>}
> ``` 

#### Exception Handling

> A way to handle runtime errors and prevent program crashing  
> Uses the keywords try, throw, and catch
> 
>![exceptionhandling](https://github.com/user-attachments/assets/8dbf6b06-03b1-4d94-a7d1-78f4d6dbe66b)

#### File I/O in OOP

>
>
>

#### Friends

> Allows a class to give a different class access to its private and protected members 
>```
>class Person
>{
>  private:
>    friend class Other;
>    some data;
>};
>class Other
>{
>  some data; //same as in Person
>};

#### Generics and Templates

>
>
>

#### Inheritance

> How sub/derived/child classes/objects gain extra properties and behaviors from their super/base/parent class/object  
> Contrasts with Composition, is an "is-a" relationship
> 
>![inheritance](https://github.com/user-attachments/assets/3d08870f-d6ce-4597-a2d6-c0933e281b4b)
>```
>class Parent
>{
>  data members;
>};
>class Child : public Parent
>{
>  data members; //same as in Parent
>};
>```

#### Instance Variable

> A Non-Static Variable that is declared in a class outside of a method  
> Does not need to be initialized, and can only be accessed by creating objects
>```
>class Person
>{
>  public:
>    string name; //instance variable
>};
>```

#### Member Variable

> A Variable that is associated with a specific object, and is accessible for all its methods
> Two types: Instance and Class

#### Memory Management (Garbage Collection, Pointers)

>
>
>

#### Method Overloading

> A method with the same name as another method but uses different parameters
>```
>int math(int a)
>{
>  something;
>}
>int math(int a, int b)
>{
>  something
>}
>```

#### Method

> A function defined inside a class that operates on the data members of that class  
> can be a constructor or destructor
>```
>class Rectangle
>{ ...
>  public:
>    void makeRectangle(int w, int l)
>    {
>      return w * l;
>    }
>}
>```

#### Multiple Inheritance

> A sub/derived/child classes/objects that inherits from more than one super/base/parent class/object
> 
>![multiple inheritance](https://github.com/user-attachments/assets/faf2e265-ce78-4893-b214-b910e2ccfdb7)
>```
>class Parent1
>{
>  data members;
>};
>class Parent2
>{
>  data members2;
>};
>class Child : public Parent1, public Parent2
>{
>  data members; //same as in Parent1
>  data members2; //same as in Parent2
>};
>```

#### Multithreading in OOP (time permitting)

>
>
>

#### Object Relationships (Association, Aggregation, Composition)

>
>
>

#### Object-Oriented Design Principles

>
>
>

#### Operator Overloading

> Defines how an operator can be applied to different situations (+, -, =, etc.)  
>ex: (cout << type;) would output 'type' but (int a = 3 << 2) would shift the value of 3 by 2 bits

#### Overloading

> Uses the same name of an already existing thing but with extra parameters to make it different

#### Polymorphism

> To take something that already exists and changing it into a different version of the same thing  
> ex: A person can be a friend, child, and employee all at the same time

#### Public / Private / Protected

> Access Modifiers that limit what in a class can be used outside the class, see Access Modifiers

#### SOLID Principles

>
>
>

#### Static (Methods and Variables)

>
>
>

#### Testing in OOP (Unit Testing, Test-Driven Development)

>
>
>

#### UML Diagrams and Modeling

>
>
>

#### Virtual

> A keyword that enables Runtime Polymorphism, and ensures that the correct function  
> is called for an object, regardless of the reference used for the function call  
> They are always defined in the base class and overridden in a derived class
>```
>class thing
>{
>  virtual void thingy();
>};
>```
