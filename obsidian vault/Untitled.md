Documentation
This project is to emulate a school management system that has the ability to create students, enroll them and create course to enroll them with, it also comes with a grade management system

Student Class
The student class is what is in charge of all the functionality that concerns the students which includes grade of student and enrollment of students.
The following are the methods and variables available in the student class

private String studentFullName
This is the variable which holds student full name as you can see the variable is private so as to prevent it from being modified by other classes, objects and method. The studentFullName since it is private we created getters and setters so that we can retrieve and modify them from another class, object and methods and they are getStudentFullName and setStudentFullName respectively

private String id
This is the variable which holds student id which is a number as you can see the variable is private so as to prevent it from being modified by other classes, objects and method. 
The id since it is private we created getters and setters so that we can retrieve and modify them from another class, object and methods and they are getId and setId respectively.

private Course[] enrolledCourses.
This private variable is an array that holds the courses that were enrolled by the students. This private field only has a getter because we already have method for adding courses to the enrolled course.

public void enrollStudent.
this method returns nothing but it adds courses to the courses that the student wants to enroll in.

public void assignGrade
This method assigns grade to each course  for the student.

Course Class
This is the class that holds the functionality pertaining to courses.
The following are the methods and variables in the course class.
Course
This is the constructor of the course class that is used to initialize the information about the course.
private int courseCode.
This private variable holds the unique identifier of a course. It has only a getter the getCourseCode it only has the getter because we only want to retrieve the courseCode and not modify it.

private String courseName.
This private variable holds the name of the course. It has only a getter the getCourseName it only has the getter because we only want to retrieve the courseName and not modify it.

private int maximumCapacity.
This private variable holds the maximum amount of student in number that can enroll for the course. It has only a getter the getMaximumCapacity it only has the getter because we only want to retrieve the maximumCapacity and not modify it.

private int totalNumberOfEnrolledStudents.
This private variable holds the total number of students that have enrolled in a course. It has only a getter the getTotalNumberOfEnrolledStudents it only has the getter because we only want to retrieve the getTotalNumberOfEnrolledStudents and not modify it.

CourseManagement Class.
This class holds the functionality of managing courses in the school and it also brings the student and the course class together.

The following are the variables and methods that belong to this class:

private static Course[] availableCourses
This private and static variable holds the array of courses offer able in the institution. it has a getter which could be used outside of the class to retrieve it.

static void addCourse
This method collects all the information of the course that were defined in the course class and creates a new course object with the parameter of the method as the parameter of the constructor of the course class and adds the course to the list of available courses.

static void enrollStudent.
This method takes a student object and a course object has parameter then uses the enrollStudent method in the student object to add the course object has the enrolled courses of the student objects.

How to interact with the program
When you run the program the program asks for the action you want to perform which could be either add a course, enroll student, adding a grade to a course for a student and to calculate the overall score of all the course each student enrolled for. Before you enroll a student you have to create the course the student can enroll for but there is a bug because I have to check against the available course a student can offer but once you perform one operation the program terminates but I tried to use a do while loop and ask the user if the user would like perform another task but I am still having the same exception in my code