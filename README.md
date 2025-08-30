# Aim: To study and implement Constructors and Destructors

# Apparatus: VS Code

# Theory: 

# CONSTUCTOR:

•	The name of the constructor is same as its class name. 

•	Constructors are mostly declared in the public section of the class though it can be declared in the private section of the class. 

•	Constructors do not return values; hence they do not have a return type. 

•	 A constructor gets called automatically when we create the object of the class. 

•	Constructors are used when variables need to be initiated before object is called.

•	Constructors can be overloaded. 

•	Constructor cannot be declared virtual.

•	The prototype of Constructors is as follows:
	<class-name> (list-of-parameters);
 
•	Constructors can be defined inside or outside the class declaration:-

•	The syntax for defining the constructor within the class:
	<class-name> (list-of-parameters) { // constructor definition }
 
•	The syntax for defining the constructor outside the class:
<class-name>: :<class-name> (list-of-parameters){ // constructor definition}

# TYPES OF CONSTRUCTORS:

⮚	Default Constructor🡪Default constructor is the constructor which doesn’t take any argument. It has no parameters. It is also called a zero-argument constructor.

⮚	Parametrized Constructor 🡪To create a parameterized constructor, simply add parameters to it the way you would to any other function. When you define the constructor’s body, use the parameters to initialize the object.

⮚	Copy Constructor 🡪A copy constructor is a member function that initializes an object using another object of the same class. In simple terms, a constructor which creates an object by initializing it with an object of the same class, which has been created previously is known as a copy constructor.

# DESTRUCTOR:

•	A destructor is also a special member function like a constructor. Destructor destroys the class objects created by the constructor. 

•	Destructor has the same name as their class name preceded by a tilde (~) symbol.

•	It is not possible to define more than one destructor. 

•	The destructor is only one way to destroy the object created by the constructor. Hence destructor can-not be overloaded.

•	Destructor neither requires any argument nor returns any value.

•	It is automatically called when an object goes out of scope. 

•	Destructor release memory space occupied by the objects created by the constructor.

•	In destructor, objects are destroyed in the reverse of an object creation.

#  Algorithms:







