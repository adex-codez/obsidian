Evaluate the significance of encapsulation as a fundamental principle in object-oriented programming, highlighting its role in promoting code modularity and ensuring data security. Explain how encapsulation contributes to code organization by encapsulating related data and behavior within objects. Additionally, discuss how encapsulation prevents unauthorized access to object data, ensuring data integrity and privacy. Support your argument with relevant examples from real-world programming scenarios to illustrate the practical benefits of encapsulation in enhancing code maintenance, reusability, and overall software security.


Encapsulation is one of the core principles in object oriented programming which guide how we write code in a object oriented way the following are the significance of  encapsulation :

1. It helps us to hide data in classes by making fields and methods private thus preventing fields and methods unmodifiable from outside a class thus helping to keep secrets or data.
2. Encapsulation helps us organize code into classes thereby having one place to keep our code for specific use cases.
3. Encapsulation saves us the time we need to create methods and properties anytime we need them but create them once and use them anywhere.

Encapsulation helps us to organize code by creating classes that stores business logic which reduces repetition of code we need for specific business  logic other programming paradigms also have a way to store business logic in specific places like modules but object oriented programming uses classes and objects.

Once you encapsulate data in classes the data cannot be tampered with which also helps us to make sure our data remains the same through out our application which ensures data integrity since our code is encapsulated there cannot be unauthorized access to data in objects.

Code

Teacher
package encapsulation;

  

public class Teacher {

String FirstName;

String LastName;

int Salary;

String SubjectTaught;

Teacher(String firstName, String lastName, int salary, String subjectTaught){

FirstName = firstName;

LastName = lastName;

Salary = salary;

SubjectTaught = subjectTaught;

}

public void introduction()

{

System.out.println("My name is " + FirstName + " " + LastName + " and i am a teacher");

}

public void teach() {

System.out.println("I teach " + SubjectTaught);

}

}

This class holds everything that relates to a teacher including the data members and behaviours.


Student

package encapsulation;

  

public class Student {

String FirstName;

String LastName;

int SchoolFeesAmount;

Student(String firstName, String lastName, int schoolFeesAmount)

{

FirstName = firstName;

LastName = lastName;

SchoolFeesAmount = schoolFeesAmount;

}

public void introduction()

{

System.out.println("My name is " + FirstName + " " + LastName + " and i am a student");

}

public void paySchoolFees()

{

System.out.println("This is the amount i pay for school fees " + SchoolFeesAmount);

}

}

This class holds everything that relates to a student including the data members and behaviours.

Main Class

package encapsulation;

  

public class main {

  

public static void main(String[] args) {

// TODO Auto-generated method stub

Student studentObj = new Student("Adegbite", "Adeife", 50000);

Teacher teacherObj = new Teacher("Adegbite", "Adeadura", 700000, "Physics");

studentObj.introduction();

teacherObj.introduction();

}

  

}