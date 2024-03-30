**Static variables or Methods

Static variables belong to the class itself - (David J.  Eck, 2022).
An instance of a class is not needed to make use of static variables or methods.

**Use Cases**
Useful when you don't want to create a instance of a class to make use of such methods.

**Non-Static variables or Methods

Non-static variables belong to the object of a class or a instance of the class - (David J.  Eck, 2022).
An instance of a class is  needed to make use of non-static variables or methods.

**Use Cases**
Useful when you want every object to hold a copy of the variable or the method like a person has their own name which is unique to them so does object have variables unique to them.



package StaticVariablesandmethods;

  

public class main {

  

	public static void main(String[] args) {
	
	// TODO Auto-generated method stub
	
	Person person = new Person();
	
	person.firstName = "John";
	
	person.lastName = "Cena";
	
	
	System.out.println("My name is " + person.firstName + " " + person.lastName + " and " + Person.walk());
	}

  

}

package StaticVariablesandmethods;

  

public class Person {

	String firstName;
	
	String lastName;
	
	public static String walk()
	
	{
	
	return "I can walk";
	
	}

}

In the code above I created a class called person which had two non-static variables which were firstName and lastName and a static method named walk the variables firstName and lastName were created has non-static because every object which is a person must have a first name and last name unique to them so they were created has non-static because they belong only to the instance of the class while the method walk was static because walking necessary does not only belong to the object but for the class itself because everybody can walk and is not unique to only to one person.


Non-Static variables or methods

Advantages
1. it is very useful when you want to let objects have their own copy of the variable or method.

Limitations
1. It uses much memory because memory is allocated to them every time  they want to be used.
2. an object of a class has to be created before they could be accessed it could be good for some use cases but overcomplicated  for simple use.

Static variables or methods

Advantages.
1. They can be accessed without creating the instance of a class.
2. It does not use much memory because memory is only allocated once which is when they are created.

Limitations.
1. 