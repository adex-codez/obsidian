Principles of Object Oriented programming, including polymorphism, method overriding, dynamic binding and inheritance can be effectively connected to enhance code organization and runtime flexibility by the following:

Polymorphism helps to enhance code organization because different subclasses have a similar method which has a similar method signature but have different implementations since this method belongs to a class and they encapsulate certain business logic that are local to those classes. It also enhances runtime flexibility because this method have different implementations depending on the instance of the class being created.

Method Overriding helps to enhance code organization because once you create a subclass from a superclass and there are certain methods which belong to the superclass and you override them and give the subclass a different implementation you have created a new business logic inside the subclass with a method which has the same method signature. It enhances runtime flexibility because a method behaves differently depending on  the object of the class you created.

Inheritance helps to enhance code organization because you create a subclass which has the same functionality as the superclass but you also give the subclass its own functionality you have organized functionality inside different classes and you have extended the functionality of certain classes.

Main class

package inheritanceExp;

  

public class Main {

  

public static void main(String[] args) {

// TODO Auto-generated method stub

Person person = new Person();

Student student = new Student();

person.getInfo();

person.introduction();

student.getInfo();

student.introduction();

}

  

}

Person Class

package inheritanceExp;

  

import java.util.Scanner;

  

public class Person {

String firstName;

String lastName;

int age;

int dateOfBirth;

void getInfo()

{

Scanner input = new Scanner(System.in);

System.out.println("Enter first name");

firstName = input.nextLine();

System.out.println("Enter last name");

lastName = input.nextLine();

System.out.println("Enter age");

age = input.nextInt();

System.out.println("Enter date of birth");

dateOfBirth = input.nextInt();

}

void introduction()

{

System.out.println("My name is " + firstName + " " + lastName + " I am a person");

}

void eat()

{

System.out.println("I can eat");

}

void walk()

{

System.out.println("I can walk");

}

}

Student Class
package inheritanceExp;

  

public class Student extends Person{

@Override

void introduction()

{

System.out.println("My name is " + firstName + " " + lastName + " I am a student");

}

void study()

{

System.out.println("I can study");

}

void paySchoolFees()

{

System.out.println("I pay school fees");

}

}


A real life scenario where inheritance can find application is Let's say we want to create a class that serves has a base class which has its own data and functionality but we also want to create a subclass which has the same functionality has the base class and we also want to extend the base class by adding  new functionality to the subclass.

Inheritance has significance in the context of modern software development practice by providing the following:

Less boilerplate
Inheritance reduces boilerplate because if you want to create a new class but you already have a class created that has some of the functionality you need instead of recreating the functionality from scratch you could allow the new class to extend the already available class.

Extension
Inheritance helps in extension by allowing us to create a new class and also inherit some functionalities from another class and also extend the functionality by either creating new functionalities or overriding the already given functionalities.