# Aim: To study and implement Constructors and Destructors

# Apparatus: 
VS Code

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

Default constructor:

1.Start

2.Define a class Student with:

Data members:

rollno (integer)

name (character array of size 50)

fee (double/float)

A default constructor that:

Prompts the user to enter the roll number and stores it in rollno.

Prompts the user to enter the name and stores it in name.

Prompts the user to enter the fee and stores it in fee.

A display() function that prints rollno, name, and fee.

3.In the main() function:

Step 1: Create an object s of class Student.

On creation, the constructor will automatically be called, and it will take input values from the user.

Step 2: Call the function s.display() to show the student’s roll number, name, and fee.

4.Stop

Parameterized Constructor:

1.Start

2.Define a class construct with:

Private data members:

a (integer)

b (integer)

A parameterized constructor that accepts two integer arguments m and n and initializes:

a = m

b = n

A display() function that prints the values of a and b.

3.In the main() function:

Step 1: Create an object c of class construct with parameters (23, 45).

This automatically calls the parameterized constructor, which assigns:

a = 23

b = 45

Step 2: Call the function c.display() to print the values of a and b.

4.Stop

Copy Constructor:

1.Start

2.Define a class Student with:

Private data members:

name (string)

age (integer)

Public members:

Parameterized constructor to initialize name and age.

Copy constructor that copies data from another Student object.

display() function to print name and age.

3.In the main() function:

Step 1: Create an object s1 of class Student using the parameterized constructor, and pass "Suyashi" as name and 19 as age.

Step 2: Create another object s2 by copying s1 (this automatically calls the copy constructor).

Step 3: Print "Original object:" and call s1.display() to show s1’s details.

Step 4: Print "Copied object:" and call s2.display() to show s2’s details (which should be the same as s1).

4.End

Destructor:

1.Start

2.Initialize a global variable count = 0 to keep track of objects.

3.Define a class destruct with:

Constructor (destruct()):

Increment count by 1.

Print "No. of objects created: " followed by count.

Destructor (~destruct()):

Decrement count by 1.

Print "No. of objects destroyed: " followed by count.

4.In the main() function:

Step 1: Create three objects: aa, bb, and cc.

For each object, the constructor is called → increments count and prints creation message.

Step 2: Create a block { ... }.

Inside this block, create object dd.

Constructor runs → increments count and prints message.

When the block ends, object dd goes out of scope → destructor is called → decrements count and prints destruction message.

Step 3: At the end of main(), objects aa, bb, and cc go out of scope one by one → their destructors run, decrementing count each time and printing destruction messages.

5.Stop

# Conclusion:

Hence we have learned to implement Constructors and Destructors in c plus plus







