There are seven deadly sins in programming that would grind your code quality if you don't heed their lessons and they are as follows: 

## Not following coding standards

Coding standards like how to structure your file, whitespaces that make our code look more consistent and therefore easily readable. If we don't follow coding standard it is like changing font
all the time, we can read it sure but there are subtle differences that could slow us down

## Coding principles

coding principles are like a general guide into becoming a better programmer. They are the raw philosophies of coding.
The following are one of the most important of all the available principles:

1. Single Responsibility(S)
	It teaches us to aim to break our code modular with one responsibility each.

2. Open and Close(O)
	it suggests that we design our modules to be able to add new functionalities without having to make change  to them, instead we should extend the module to add to it. Once a module is in use it is locked, and this reduces the chance of any new additions causing breaking changes.

3. Liskov Substitution(L)
	It tells us to only extend modules when we are absolutely  sure that it is still the same type at heart

4. Interface Segregation(I)
	It says our modules do not need to know about any functionality that they don't use. 
	
5. Dependency Inversion(D)
	It says that instead of talking to other parts of your code directly, we should always communicate abstractly via our interfaces. It breaks down any direct relationships between our code, and isolates our modules completely from one another meaning we can swap out parts when we need to. They should only be concerned about taking certain inputs and returning a valid output. 
When we apply all this together it ends up decoupling our code giving us modules that are independent of each other making our code more maintainable, scalable, reusable and testable.


## Programming design patterns

Patterns give us real solutions to our code problems but they aren't fixed implementations,  so they are still kind of open to interpretation.
-  Creational patterns: This are design patterns that help us in creating object instances.
- Structural Patterns: This are design patterns that is concerned with organizing and manipulating our objects.
- Behavioral patterns: This are design patterns that is concerned with how our code functions and how it handles communication with other parts of the code.

## Naming

- Avoid encodings such has type information which make it harder to read our code in a natural way 
- Expand abbreviations or acronyms to avoid any misunderstandings
- Use clear distinctions that represents the nuances of the code we are working with.
- No "magic" values by removing magic values with named constants that clarify their significance.
- Be descriptive with your names but this should not be so verbose that it becomes an information overload.

## Testing 

## Time

A common rule of thumb is to triple or even double your initial time estimate for a task.

## Speed 

Try not to rush things can feel great when we are blazing through a project. If it is going to be a long term project take your time and think things through from day one. We would never get our decision right the first time, but we can at least give ourselves a better foundation to work from 