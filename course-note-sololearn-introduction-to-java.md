<img src="https://raw.githubusercontent.com/dark-teal-coder/dark-teal-coder/main/images/coder-no-background-000-128-128.png"
    alt="coder-black-background-000-128-128.png" width="100" height="100" align="right" style="margin:0px 5%; padding: 5px;">
<p>
    GitHub: <a href="https://github.com/dark-teal-coder">@dark-teal-coder</a>
    <br />
    First Published Date: 2023-07-19
    <br />
    Last Modified Date: 2024-03-12
</p>

&nbsp;

---

&nbsp;

# Introduction to Java

This simple, beginner-friendly Java course requires no previous coding knowledge. All you need is a mobile phone or desktop computer and 5 minutes a day! You’ll learn all about the key concepts of Java and will be writing clear, working code right from your first lesson.

&nbsp;

---

&nbsp;

## Table of Contents

- [Module 01: Basic Concepts](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#module-01-basic-concepts)
- [Module 02: Control Flow](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#module-02-control-flow)
- [Module 03: Arrays](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#module-03-arrays)
- [Module 04: Methods](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#module-04-methods)

&nbsp;

---

&nbsp;

## Module 01: Basic Concepts

### Lesson 01.01: Getting Started with Java

#### Welcome to Java!

Java is one of the most popular programming languages.

Java's slogan is "Write once, run anywhere". Java programs can run on different platforms, including mobile, desktop, and other portable systems. You can use Java to build apps, games, banking applications, web apps, and much more!

#### Coding

Humans use computer programs to communicate with machines. Without computer programs, we wouldn't have smartphones, websites, or even exploration in outer space.

<p align="center">
    <img src="./images/java-introduction-01-01-p02-a.png" alt="./images/java-introduction-01-01-p02-a.png" width="50%" height="50%">
</p>

Learning some coding can help you innovate and create different solutions to problems, giving you a competitive edge in this technology-driven world. 

#### Quiz 01.01.01

**Question**

What's a programming language?

**Answer**

A language used by humans to communicate with machines

#### Output

Most computer programs are designed to produce outputs. Here are some examples:

- "You've got a new message" notifications
- "Game Over" displayed on the screen when playing video games
- Your account balance when checking your online banking app.

The simplest output consists of displaying a message on the screen.

#### Quiz 01.01.02

**Question**

Notifications and text displayed on a screen are examples of outputs from computer programs

**Answer**

True

#### Output

Coders use outputs all the time to check that the computer is following the given instructions and fix problems with code.

The following line of code displays Java's slogan on the screen as an output:

```java
System.out.println("Write once, run anywhere!");
```

#### Quiz 01.01.03

**Question**

Drag and drop to write a line of code that outputs "New message".

**Answer**

"New message"

#### The Code Playground

Ready to write, run and test real code?

Open the Code Playground below. Then hit "run" to see the output on the screen.

```java
public class Program {
	public static void main(String[] args) {
		System.out.println("Welcome to the Code Playground");
	}
}
```

You'll see other lines of code when you open the Code Playground. They are needed for the code to run without errors. You will learn everything about these lines in the upcoming lessons.

#### Quiz 01.01.04

**Question**

Drag and drop to complete a line of code that outputs "Game Over".

**Answer**

`println`

#### Quiz 01.01.05

**Question**

The `println` instruction needs to be followed by parentheses. Drag and drop to create a line of code that runs without errors.

**Answer**

`(` and `)`

#### Quiz 01.01.06

**Question**

Drag and drop to create a line of code that runs without errors.

**Answer**

`out` and `println`

#### Lesson Takeaways

Awesome! You completed your first lesson 🚀. Remember the following important points:

- You can write code that generates outputs with the `System.out.println()` statement
- The `println` instruction needs to be followed by parentheses

What's next?

In the next lesson, you will create code with multiple lines and different types of data.

&nbsp;

### Lesson 01.02: Multiple Statements

#### More Complex Programs

Real computer programs can include thousands of lines of code.

In this lesson, you’ll start building more complex programs.

#### Statement

A line of code is called a statement. A statement performs a specific task.

The output command is an example of a statement.

```java
System.out.println("Write once, run anywhere!");
```

> :warning: Each statement needs to end with a semicolon `;`.

#### Quiz 01.02.01

**Question**

Each statement needs to end with a

**Answer**

Semicolon `;`

#### Multiple Statements

You can add as many statements (or lines of code) as you need.

The following piece of code consists of 2 statements. It outputs two messages in different lines.

```java
public class Program {
	public static void main(String[] args) {
		System.out.println("Name:");
		System.out.println("Surname:");
	}
}
```

> :warning: Remember your code will result in an error if you forget the semicolons `;` at the end of the statements.

#### Quiz 01.02.02

**Question**

Drag and drop to complete code that runs without errors

**Answer**

`(`, `;` and `)`

#### Quiz 01.02.03

**Question**

When you give the computer many statements, the instructions will be executed line by line, from top to bottom.

Drag and drop to reorder the statements and output the following lines in the correct order:

*Head east*
*Turn left*
*Cross the road*

**Answer**

`System.out.println("Head east");`, `System.out.println("Turn left");` and `System.out.println("Cross the road");` 

#### Text vs Numbers

Computers treat text and numbers differently. When printing text outputs, you need to enclose the text in double quotes. You don't need quotes when outputting numbers.

```java
public class Program {
	public static void main(String[] args) {
		System.out.println("Points:");
		System.out.println(500);
	}
}
```

> :warning: Your code will result in an error if you forget the quotes around the text.

#### Quiz 01.02.04

**Question**

Drag and drop to write code that runs without errors

**Answer**

`"` and `(`

#### Quiz 01.02.05

**Question**

Drag and drop to write code that runs without errors

**Answer**

`println`, `;` and `out`

#### Quiz 01.02.06

**Question**

Java is a case-sensitive language. This means that you need to pay attention to the correct input of uppercase and lowercase letters.

Drag and drop to write code that runs without errors:

**Answer**

`System`

#### Quiz 01.02.07

**Question**

Java is a

**Answer**

case-sensitive language

#### Lesson Takeaways

Great work 🎯! You completed the lesson. You learned that:

- You can add multiple statements to your programs
- Text needs to be enclosed in quotes
- Java is a case-sensitive language.

In the next lesson, you’ll learn about the structure of programs in Java.

#### Practice makes perfect!

Put your knowledge into practice and write real code to solve the exercise below.

##### My First Code Coach!

###### Your First Java Program

Let's code for real!

The given program should output the text: "My first Java Code Coach!".

But something is wrong.

**Task**

Complete the code to generate the required output.

###### Answer

```java
public class Program {
	public static void main(String[] args) {
		System.out.println("My first Java Code Coach!");
	}
}
```

&nbsp;

### Lesson 01.03: Program Structure

#### Java Program

In this lesson we will break down the structure of Java programs and understand how they work.

The whole code to create a valid Java program that outputs a simple text is the following:

```java
class Demo {
	public static void main(String[] args) {
		System.out.println("Hi there");
	}
}
```

> :warning: We are already familiar with the println method and the statement used to create output, so let's learn what the other parts of the code are.

#### Java Program

The first line of the code defines a class called Demo.

```java
class Demo {
```

In Java, every line of code that can actually run needs to be inside a class. You can call the class anything you want.

> :warning: We will learn more about classes in more advanced modules. For now, just remember, that any Java program needs to be inside a class.

#### Java Program

The class opens and closes using curly brackets, like this:

```java
class Demo {

}
```

Any code that we want to include in the class needs to go inside the brackets.

> :warning: The opening bracket can also be written below the class name, but it's generally common to write it on the same line to save space.

#### Quiz 01.03.01

**Question**

Fill in the blanks to create an empty class called Bot.

**Answer**

`class` and `Bot`

#### Java Program

Our program includes one more thing that we need to cover:

```java
class Demo {
	public static void main(String[] args) {
		System.out.println("Hi there");
	}
}
```

As you can see, the Demo class includes the following line:

```java
public static void main(String[] args) {
```

In Java, each application has an entry point, or a starting point, which is a method called main.

> :warning: We will cover public, static and void keywords definition in later lessons, when learning about methods. For now, remember that the main method needs to be declared identically to the code above.

#### Quiz 01.03.02

**Question**

The starting point of every Java program is:

**Answer**

the main method

#### Java Program

Notice that the main method, similar to the class, opens and closes with curly brackets.

```java
public static void main(String[] args) {
	System.out.println("Hi there");
}
```

The main method contains the code that executes when we run our program. In this case, the `println` method will be executed, when we run our program.

#### Quiz 01.03.03

**Question**

Fill in the blanks to create a valid main method that outputs a text.

**Answer**

`main`

#### Java Program

The main method can contain multiple statements, for example:

```java
class Demo {
	public static void main(String[] args) {
		System.out.println("Welcome");
		System.out.println("This is a demo"); 
		System.out.println("Bye");
	}
} 
```

> :warning: This is now a fully functioning Java program.

#### Quiz 01.03.04

**Question**

Fill in the blanks to create a valid Java program.

**Answer**

`class`, `main` and `out`

#### Lesson Takeaways

Great job 🎯! You now know how to create a valid Java program structure!

Remember the following important points:

- You need to start your program by creating a class.
- The class needs to include a main method, which is the starting point of the program.
- The main method includes the statements that need to be executed when the program runs.
- The class, as well as the main method opens and closes using opening and closing curly brackets.

##### Coding is fun!

###### Your First Code Coach 

Let's code for real!

The given program outputs “Coding is boring”. But that's not true, is it? Let’s change the message.

**Task**

Modify the code to output "Coding is fun" to the screen.

> :warning: After fixing the code, tap the RUN button to see the result.

###### Answer

```java
class Demo {
	public static void main(String[] args) {
		System.out.println("Coding is fun");
	}
}
```

&nbsp;

### Lesson 01.04: Variables

#### Variables

Every program works with values.

A variable lets you store a value by assigning it to a name. The name can be used to refer to the value later in the program.

> :warning: For example, in game development, you would use a variable to store how many points the player has scored.

#### Variables

Every variable has a type, which defines the type of the value it holds. A variable can hold a text value, a number, a decimal, etc.

We are already familiar with text values - they are created using quotes:

```java
"this is some text"
```

Text in quotes is called a String.

#### Quiz 01.04.01

**Question**

Which of the following is a String?

**Answer**

`welcome`

#### Variables

Let's create a variable of type String:

```java
String name;
```

This creates a variable called name of type String.

Now, our variable name can hold String values.

> :warning: In programming terms, the process of creating a variable is called declaration.

#### Quiz 01.04.02

**Question**

Drag & drop to declare a String variable called "message".

**Answer**

`String` and `message`

#### Variables

After declaring our variable, we can assign it a value using the assignment = operator:

```java
String name;
name = "James";
```

Now, name holds the value "James".

> :warning: Note, that the type String should start with a capital letter S. A lowercase version will cause an error.

#### Quiz 01.04.03

**Question**

Fill in the blanks to declare a variable called 'city' and assign the value "New York" to it.

**Answer**

`city`, `=` and `;`

#### Variables

We can use our variable in our program.

For example, let's output its value using `println()`:

```java
class Demo {
	public static void main(String[] args) {
		String name;
		name = "James";
		System.out.println(name); 
	}
}
```

#### Quiz 01.04.04

**Question**

Rearrange the code to create a program that declares a variable called "country", assign the value "UK" to it and output it to the screen.

**Answer**

`String country;`, `country = "UK";` and `System.out.println(country);`

#### Variables

We can combine the declaration and assignment into one statement, like this:

```java
class Demo {
	public static void main(String[] args) {
		String name = "James";
		System.out.println(name);
	}
}
```

This is handy when we already know the value for our variable and makes the code shorter and more readable.

#### Quiz 01.04.05

**Question**

Drag & drop to declare the variable and assign it to the given value.

**Answer**

`String` and `=`

#### Variables

A variable can change its value during the program multiple times.

For example, the player of a game can change his name:

```java
class Demo {
	public static void main(String[] args) {
		String name = "James";
		name = "David";

		System.out.println(name);
	}
}
```

#### Quiz 01.04.06

**Question**

What is the output of this code?

```java
String x = "hey";
x = "hoy";
System.out.println(x);
```

**Answer**

`hoy`

#### Lesson Takeaways 

Awesome! Here are some key takeaways:

- A variable has a name and a type of the value it holds.
- To declare a variable use the type followed by the name of the variable.
- You can assign a value to the declared variable using the = operator.
- A variable can change its value during the program, by being assigned to a new value.

We will learn about more variable types in the next lesson!

##### Storing Characters

###### Storing Characters

The given program declares a variable that holds all the letters of the English alphabet.

**Task**

Complete the program to output the value of the variable.

###### Answer 

```java
public class Program {
	public static void main(String[] args) {
		String alphabet = "abcdefghijklmnopqrstuvwxyz";
		System.out.println(alphabet);
	}
}
```

#### Quiz 01.04.07

**Question**

Drag & drop to create a valid Java program that declares a variable, assigns it to a value and outputs it.

**Answer**

`class`, `main`, `String`, `println` and `color`

&nbsp;

### Lesson 01.05: Variable Types

#### Types

There are other types that you can use for variables.

The int type is used to store whole numbers (or integers, as we call them in programming).

```java
class Demo {
	public static void main(String[] args) {
		int age = 42; 
		System.out.println(age);
	}
}
```

> :warning: Now, the `age` variable of type `int` holds the value `42`.

#### Quiz 01.05.01

**Question**

Fill in the blanks to declare a variable that holds the value 14.

**Answer**

`int` and `=`

#### Decimals

To work with decimal numbers, use the type double:

```java
class Demo {
	public static void main(String[] args) {
		double weight = 12.5; 
		System.out.println(weight);
	}
}
```

#### Quiz 01.05.02

**Question**

Drag and drop from the options below to have a valid Java program.

**Answer**

`String`, `int` and `double`

#### Decimals

Java has another type for decimals called float.

When using the float type, you need to use an f postfix after the value:

```java
class Demo {
	public static void main(String[] args) {
		float height = 1.94f; 
		System.out.println(height);
	}
}
```

This tells Java to use the value as a float, instead of double.

> :warning: Wondering what's the difference between float and double? Tap Continue to learn more!

#### Quiz 01.05.03

**Question**

Fill in the missing symbol to correctly declare a float.

**Answer**

`f`

#### float vs dobule

By default, decimal values are of type double.

float is using less storage in the memory, but is not as precise as the double type.

This means that the calculations that use floats are faster than the ones that use double, however, the result is less accurate in terms of the decimal digits.

> :warning: As a general rule: use float instead of double when memory usage is critical. If you need more precise computations, for example, when dealing with currency, use double.

#### Characters

The char type is used to hold a single character.

It is created similar to Strings, however it uses single quotes for the value:

```java
class Demo {
	public static void main(String[] args) {
		char letter = 'B'; 
		System.out.println(letter);
	}
}
```

#### Quiz 01.05.04

**Question**

A char value must be enclosed in:

**Answer**

single quotes 

#### Boolean

Another important type is boolean.

It can hold only the values true or false.

This is handy when we work with states or conditions, for example:

```java
class Demo {
	public static void main(String[] args) {
		boolean isOpen = false; 
		System.out.println(isOpen);
	}
}
```

For example, the boolean above can show whether a shop is open or closed.

#### Quiz 01.05.05

**Question**

Select the two values that a boolean can hold.

Select all correct answers.

**Answer**

- [x] `true`
- [x] `false`

#### Lesson Takeaways  

Great job! Here are some key takeaways:

- int holds integers (whole numbers).
- double holds decimal numbers.
- float is similar to double, but has less precision and requires less memory.
- You need to use an f postfix after the value to make it a float (for example: 3.14f)
- char holds a single character.
- boolean can have one of the following values: true or false.

We will learn how to make calculations in the next lesson.

##### Displaying Account Balance

###### Displaying Account Balance

The given program declares a label and a balance variable, and assigns it to their values.

Then, it outputs the label and the balance values.

However, the code is missing the required types of the variables

**Task**

Add the required types to make the program work as expected.

###### Answer 

```java
public class Program {
	public static void main(String[] args) {
		String label = "Balance";
		double balance = 599.84;

		System.out.println(label);
		System.out.println(balance);
	}
}
```

#### Quiz 01.05.06

**Question**

Drag & drop to fill in the correct data types for the given variables.

**Answer**

`int`, `boolean`, `double` and `String`

&nbsp; 

### Lesson 01.06: Doing Math

#### Doing Math

You can use common math operators to perform calculations.

For example:

```java
class Demo {
	public static void main(String[] args) {
		int x = 6;
		int y = 3;

		System.out.println(x+y);
	}
}
```

This will output the sum of the two variables.

#### Doing Math

The result can be assigned to another variable, like this:

```java
class Demo {
	public static void main(String[] args) {
		double price1 = 24.99;
		double price2 = 19.45;
		double sum = price1 + price2;

		System.out.println(sum);
	}
}
```

#### Quiz 01.06.01

**Question**

What is the output of this code?

```java
int a = 3;
int b = 2;
int z = a+b;
System.out.println(z+a);
```

**Answer**

`8`

#### Doing Math

Similarly, you can use - for subtraction:

```java
class Demo {
	public static void main(String[] args) {
		int salary = 90000;
		int tax = 15000;
		int result = salary - tax;  

		System.out.println(result);
	}
}
```

#### Multiplication

The `*` operator multiplies two values.

Let's use it to find how much is 20% of the given value:

```java
class Demo {
	public static void main(String[] args) {
		int price = 1200;

		System.out.println(price*0.2);
	}
}
```

> :warning: 0.2 represents 20%

#### Quiz 01.06.02

**Question**

Fill in the blanks to calculate and output the height of a 9-story building. Each floor has a height of 3 meters.

**Answer**

`*`, `out` and `total`

#### Division

The `/` operator divides one value by another.

The following program calculates how many products with the given price you can buy with the given amount:

```java
class Demo {
	public static void main(String[] args) {
		int amount = 9000;
		int price = 49;
		int result = amount/price;

		System.out.print(result);
	}
}
```

> :warning: In the example above, the result of the division equation will be a whole number, as int is used as the data type. 

#### Quiz 01.06.03

**Question**

What is the result of the following code?

```java
int x = 15; int y = 4;
int result = x / y;
System.out.println(result);
```

**Answer**

`3`

#### Division

You can use double to get the result of the division with a decimal point.

```java
class Demo {
	public static void main(String[] args) {
		double amount = 9000;
		double price = 49;
		double result = amount/price;

		System.out.print(result);
	}
}
```

#### Quiz 01.06.04

**Question**

The result of dividing two doubles is:

**Answer**

a double

#### Modulo

The modulo `%` (or remainder) math operation returns the remainder of a division. 

For example, let's use it to find how many of the given items will be left over if we place them in boxes of 5:

```java
class Demo {
	public static void main(String[] args) {
		int items = 23;
		int res = items % 5; 

		System.out.print(res);
	}
}
```

#### Quiz 01.06.05

**Question**

What value is stored in the result variable?

```java
int x = 8;
int y = 3;
int result = x % y;
```

**Answer**

`2`

#### Strings

Java allows to add together strings, using the + operator. The result is the combination of the strings.

For example, let's combine the first and last names to result in the full name of a user:

```java
class Demo {
	public static void main(String[] args) {
		String firstname = "James";
		String lastname = "Smith";
		String fullname = firstname+lastname;

		System.out.print(fullname);
	}
}
```

Note, that the result will combine the given strings without any separator. We can add a space " " between them:

```java
class Demo {
	public static void main(String[] args) {
		String firstname = "James";
		String lastname = "Smith";
		String fullname = firstname+" "+lastname; 

		System.out.print(fullname);
	}
}
```

> :warning: The process of adding strings together is called concatenation. You can also concatenate strings with other types, such as integers and doubles.

#### Quiz 01.06.06

**Question**

Which of the following statements concatenates the Strings a and b?

**Answer**

`a + b;`

#### Lesson Takeaways

Math is fun! Here are some key takeaways:

You can use basic math operators to perform calculations with values and variables.

- `+` is addition
- `-` is subtraction
- `/` is division
- `%` finds the remainder of a division.

You can add Strings using the + operator, in a process called concatenation.

##### Chess Tournament Scores

###### Chess Tournament Scores

You are making a program for a chess tournament, that needs to calculate the points earned by a player. A win is worth 1 point, while a tie is worth 0.5 points. The given program declares two variables: wins and ties with the corresponding values.

**Task**

Create a program to calculate and output the points earned by the player.

> :warning: Multiply the `ties` value by 0.5, to get the points earned for ties.

###### Answer

```java
public class Program {
	public static void main(String[] args) {
		int wins = 54;
		int ties = 31;

		System.out.println(wins + ties*0.5); 
	}
}
```

#### Quiz 01.06.07

**Question**

You are packing eggs in baskets, each holding 8 eggs. All packed baskets need to be full.

Fill in the blanks to create a program that calculates how many of the given eggs will be leftover.

**Answer**

`eggs`, `%` and `result`

### Lesson 01.07: Java Comments

#### Comments

One more thing to learn before wrapping up the first module!

Comments are annotations in the code that explain what the code is doing. Code is for computers, while comments are for humans who read and work with the code.

#### Comments

A single-line comment starts with two forward slashes and continues until it reaches the end of the line.

For example:

```java
class Demo {
	public static void main(String[] args) {
		// storing the age of the user
		int age = 23; // this is just a demo value

		System.out.print(age);
	}
}
```

> :warning: Adding comments as you write code is a good practice, because they provide clarification and understanding when you need to refer back to it, as well as for others who might need to read it.

#### Quiz 01.07.01

**Question**

Fill in the required symbols to make a comment.

**Answer**

`//`

#### Comments

You can also comment out lines of code, in case they are work-in-progress or you don't want to delete it yet:

```java
class Demo {
	public static void main(String[] args) {
		int age = 23;
		// int height = 122;
		System.out.println(age);
		// System.out.println(height);
	}
}
```

> :warning: The commented lines of code will get ignored when you run the program.

#### Quiz 01.07.02

**Question**

What is the output of this code?

```java
int x = 8;
// x = 2;
x = 3;
System.out.println(x+1);
```

**Answer**

`4`

#### Multi-Line Comments

If you need to comment out multiple lines, or write a multi-line comment, you can use the `/* */` symbols, like this:

```java
class Demo {
	public static void main(String[] args) {
		/* This is just a
		demo program
		that outputs a number */
		int age = 23;

		System.out.println(age);
	}
}
```

Anything between the `/*` and `*/` symbols becomes a comment.

> :warning: You can also use multi-line comments to comment out multiple lines of code.

#### Quiz 01.07.03

**Question**

Make this text a multi-line comment.

**Answer**

`/*` and `*/`

#### Lesson Takeaways

Now you know how to add comments to your code! Here are some key takeaways:

Comments are explanatory statements that explain what the code is doing.

They can contain notes, todos as well as code that is work-in-progress.

- `//` starts a single line comment.
- `/* */` is used for multi-line comments.

##### Contact Management System

###### Contact Management System

You are given a code for a contact management system. It should declare name and age variables, then output "name is age years old", where name and age are the corresponding values of the variables. However, the program includes some wrong comments.

**Task**

Fix the code to make the program run correctly.

###### Answer

```java
public class Program {
	public static void main(String[] args) {
		// declare variables
		String name = "Howard";
		// declare the age
		int age = 42;
		// output values
		System.out.println(name+" is "+age+" years old.");
	}
}
```

### Quiz 01: Module 1 Quiz

**Question M01.01**

Fill in the blanks to create a valid program that declares two variables and outputs their sum.

```java
_____ rogram {
	public static void _____ (tring[] args) {
        int a = 8;
		int b = 4;
		ystem._____.println(a _____ b);    
	}
}
```

**Question M01.02**

Which of the following is a valid comment?
- [ ] `## some text`
- [ ] `** some text **`
- [ ] `/* some text */`
- [ ] `*/ some text /*`

**Question M01.03**

Fill in the blanks to output "Hello, " followed by the value stored in the name variable.

```java
String name = "James";
String msg = "_____"+_____;
System.out.println(_____);
```

**Question M01.04**

What is the output of this code?

```java
int x = 5;
int y = 3;
int z = x%y;
System.out.println(x-z);
```

**Question M01.05**

You need to find how many minutes there are in a day. A day has 24 hours, each hour has 60 minutes. These values are stored in variables.

Fill in the blanks to calculate and output the required value.

```java
int hours = 24;
int minutes = 60;
int result = hours _____ minutes;
System.out.println(_____);
```

[Check Module 01 Quiz Answers](./module-quiz-solutions/module-01-quiz-solutions.md)

&nbsp;

---

&nbsp;

## Module 02: Control Flow

### Lesson 02.01: Taking User Input

#### Input

Some programs need user input. For example, a game may ask the user for a nickname and show it in the game, or a converter can ask for a value that you want to convert.

> :warning: There are a number of ways to take input in Java. Tap Continue to learn how.

#### Input

To take input from the user, we first must import the corresponding class.

That is done using the following line:

```java
import java.util.Scanner;
```

This line should be written at the very top of your code, before the class declaration.

> :warning: This imports the `Scanner` class, which we will use for taking input.

#### Input

After importing the Scanner class, we need to create a Scanner object:

```java
Scanner sc = new Scanner(System.in);
```

Confused about the new terminology? Classes, objects, import... Don't worry, you will learn about these in more advanced lessons. For now, just remember the syntax for creating the Scanner object.

#### Quiz 02.01.01

**Question**

Fill in the blanks to create a valid Scanner object.

**Answer**

`Scanner`, `new` and `System`

#### Input

Now we are ready to take input from the user and assign it to a variable.

For example, to take a String input, we need to use the following:

```java
import java.util.Scanner;

class Demo {
	public static void main(String[ ] args) {
		Scanner sc = new Scanner(System.in);
		String name = sc.nextLine(); 
		System.out.println("Name: "+name);        
	}
}
```

> :warning: Run the code to see how it works.

#### Quiz 02.01.02

**Question**

Fill in the blanks to create a valid program that takes a String input.

**Answer**

`import`, `Scanner`, `String` and `nextLine`

#### Input

Similarly, we can take an integer as input using `nextInt()`:

```java
import java.util.Scanner;

class Demo {
	public static void main(String[ ] args) {
		Scanner sc = new Scanner(System.in);
		int age = sc.nextInt();
		System.out.println("Age: "+age);        
	}
}
```

This will accept an integer input from the user and assign it to the age variable.

> :warning: There are similar methods available to take other types as input: `nextDouble()`, `nextFloat()`, `nextBoolean()`.

#### Quiz 02.01.03

**Question**

Rearrange to create a valid program that takes an integer input and outputs its double.

**Answer**

`Scanner sc = new Scanner(System.in);`, `int x = sc.nextInt();` and `System.out.println(x*2);`

#### Multiple Inputs

You can use the same Scanner to take multiple inputs.

For example, let's take the name and age as input and output them.

```java
import java.util.Scanner;

public class Program {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		String name = sc.nextLine();
		int age = sc.nextInt();
		System.out.println(name+": "+age);
	}
}
```

> :warning: Note, that when you run it in our Playground, you need to provide all the inputs in the popup, separated by new lines.

#### Lesson Takeaways 

That's how you take input from the user in Java!

Here are the steps:

1. import the java.util.Scanner class.

2. create a `Scanner` object:

```java
Scanner sc = new Scanner(System.in);
```

3. Use the corresponding method of the Scanner to take input, for example:

```java
import java.util.Scanner;

class Demo {
	public static void main(String[ ] args) {
		Scanner sc = new Scanner(System.in);
		int num = sc.nextInt();
		System.out.println(num);        
	}
}
```

##### Tip Calculator 

###### Tip Calculator 

You always tip 15% of the bill amount. To make the calculation easier, you decide to write a program that will do that for you.

**Task** 

Take the bill amount as input and output the corresponding tip amount, which should be 15% of the amount.

To calculate 15% of a number, multiply it by 15, then divide by 100.

> :warning: The input amount can be a decimal, so take a double from the input.

###### Answer

```java
import  java.util.Scanner;

public class Program {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double amount = sc.nextDouble(); 
		System.out.println(amount * 0.15); 
	}
}
```

#### Quiz 02.01.04

**Question**

Fill in the blanks to create a valid program that takes a String and an integer as input, then outputs a welcome message.

**Answer**

`import`, `main`, `new`, `sc`, `.` and `out`

### Lesson 02.02: Conditionals

#### Decision Making

Conditional statements are used to perform different actions based on different conditions. 

For example, a billing program can apply a discount to the total only if the amount is greater than a threshold. 

Let's learn how to create such programs.

#### Decision Making

The `if` statement is one of the most frequently used conditional statements.

If the `if` statement's condition is true, the block of code inside the `if` statement is executed. 

Syntax:

```java
if (condition) {
	// some code 
}
```

#### if Statement

Any of the following comparison operators may be used to form the condition:

- `<` less than
- `>` greater than
- `!=` not equal to
- `==` equal to
- `<=` less than or equal to
- `>=` greater than or equal to

For example:

```java
class Demo {
	public static void main(String[ ] args) {
		int age = 24;
		if(age >= 18) {
			System.out.println("Welcome");
		}
	}
}
```

> :warning: This code will output the message only if the age value is greater or equal to 18.

#### Quiz 02.02.01

**Question**

Drag & drop to output "Open" if the time value is less than 20.

```java
_____ ( _____ < 20) {
	System.out._____("Open");
}
```

**Answer**

`if`, `time` and `println`

#### if Statement

Remember that you need to use two equal signs (`==`) to test for equality, since a single equal sign is the assignment operator.

For example:

```java
class Demo {
	public static void main(String[ ] args) {
		int number = 8;
		if(number == 8) {
			System.out.println("Bingo");
		}
	}
}
```

#### Quiz 02.02.02

**Question**

Which of the following operators is used to test for equality?

- [] `=`
- [] `!`
- [] `==`
- [] `--`

**Answer**

`==`

#### else Statement

An if statement can be followed by an optional else statement, which executes when the condition evaluates to false.

For example:

```java
class Demo {
	public static void main(String[ ] args) {
		int age = 30;

		if (age < 16) {
			System.out.println("Too Young");
		}
		else { 
			System.out.println("Welcome!");
		}
	}
}
```

> :warning: As age equals 30, the condition in the if statement evaluates to false and the else statement is executed.

#### Quiz 02.02.03

**Question**

Fill in the blanks to output the greater of the two variables.

```java
int x = 10;  
int y = 5;
_____ (x > y) {
	System.out.println(_____);
}
_____ {
	System.out.println(y);
}
```

**Answer**

`if`, `x` and `else`

#### Nested if Statements

You can use one if-else statement inside another if-or-else statement.

For example:

```java
class Demo {
	public static void main(String[ ] args) {
		int age = 25;
		if(age > 0) {
			if(age > 16) {
				System.out.println("Welcome!");
			}
			else {
				System.out.println("Too Young");
			}
		}
		else {
			System.out.println("Error");
		}
	}
}
```

> :warning: You can nest as many if-else statements as you want, however the code will become harder to read and understand.

#### Quiz 02.02.04

**Question**

What is the value of x after this code is run?

```java
int x = 3;
if(x > 2) {
	if(x >= 5) {
		x = 4;
	}
	else {
		x = 6;
	}
}
else {
	x = 8;
}
```

**Answer**

`6`

#### else if Statements

Instead of using nested if-else statements, you can use the else if statement to check multiple conditions.

For example:

```java
class Demo {
	public static void main(String[ ] args) {
		int age = 25;

		if(age <= 0) {
			System.out.println("Error");
		}
		else if (age <= 16) {
			System.out.println("Too Young");
		}
		else if(age < 100) {
			System.out.println("Welcome!");
		}
		else {
			System.out.println("Really?");
		}
	}
}
```

> :warning: You can include as many else-if statements as you need.

#### Quiz 02.02.05

**Question**

Fill in the blanks to output the letter from the English alphabet that corresponds to the number.

```java
int num = 2;
_____ (num == 1) {
	System.out.println("A");
} 
_____ if (_____ == 2) {
	System.out.println("B");
}
else {
	System.out.println("something else");
}
```

**Answer**

`if`, `else` and `num`

#### Lesson Takeaways

Now you know how to make decisions in your code! Here are some key takeaways:

You can check for a condition using the if statement.

In case the condition is false, the code in an else statement can be executed.

Here is a generic structure of if-else statements:

```java
if(condition) {
	// some code
}
else if (condition) {
	// some other code
}
else {
	// some other code
}
```

We will learn about another decision making statement in the next lesson.

##### Boiling Water

###### Boiling Water

You are making a program for a water sensor that should check if the water is boiling.

Take the integer temperature in Celsius as input and output "Boiling" if the temperature is above or equal to 100. Output "Not boiling" if it's not.

Sample Input
105

Sample Output
Boiling

> :warning: Make sure to output the text exactly as defined in the text.

###### Answer

```java
import java.util.Scanner;

public class Program {
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		int celsius = input.nextInt(); 
		if (celsius >= 100){
			System.out.println("Boiling"); 
		}
		else {
			System.out.println("Not boiling"); 
		}
	}
}
```

#### Quiz 02.02.06

**Question**

Fill in the blanks to create a program that checks the `temp` value and outputs "Alert", in case it's over 38. Also, output "Error" in case the value is lower than 34.

**Answer**

```java
double temp = 36.6;
_____ (temp > 38) _____
	System.out.println("Alert");
}  
_____ (temp < 34) {
	System.out.println("Error");
}
_____ {
	System.out.println("OK").
}
```

### Lesson 02.03: The switch Statement

#### Conditionals

Consider a program that takes a day number as input and outputs the corresponding weekday:

```java
class Demo {
	public static void main(String[ ] args) {
		int day = 2;
		if(day == 1) {
			System.out.println("Monday");
		}
		else if(day == 2) {
			System.out.println("Tuesday");
		}
		else if(day == 3) {
			System.out.println("Wednesday");
		}
	}
}
```

For a shorter code in our demo, we have checked only for the first 3 values.

You can continue the code and check for all 7-day numbers.

#### switch

Instead of many if else statements, which become hard to read, we can use a switch statement.

A switch statement tests a variable for equality against a list of values.

Here is the previous example using a switch statement:

```java
class Demo {
	public static void main(String[ ] args) {
		int day = 2;

		switch(day) {
			case 1:
				System.out.println("Monday");
				break;
			case 2:
				System.out.println("Tuesday");
				break;
			case 3:
				System.out.println("Wednesday");
				break;
		}
	}
}
```

#### switch

Let's look at the code again:

```java
class Demo {
	public static void main(String[ ] args) {
		int day = 2;

		switch(day) {
			case 1:
				System.out.println("Monday");
				break;
			case 2:
				System.out.println("Tuesday");
				break;
			case 3:
				System.out.println("Wednesday");
				break;
		}
	}
}
```

When the variable being switched on is equal to a case, the statements following that case will execute until a break statement is reached.

> :warning: You can have any number of case statements within a switch. Each case is followed by the comparison value and a colon.

#### Quiz 02.03.01

**Question**

Fill in the missing characters to create a valid switch statement.

```java
int num = 2;
switch(num) {
case 1_____
	System.out.println("One");
	break;
 _____ 2:
	System.out.println("Two");
	break;
case 3:
	System.out.println("Three");
	break_____
}
```

**Answer**

`:`, `case` and `;`

#### switch

It is important to have a break statement for each case.

If no break appears, the program will continue to execute the next case in the switch, even if the value does not match the variable that is switched on.

Run this example to see what happens when there is no break in the case:

```java
class Demo {
	public static void main(String[ ] args) {
		int day = 2;

		switch(day) {
			case 1:
				System.out.println("Monday");
			case 2:
				System.out.println("Tuesday");
			case 3:
				System.out.println("Wednesday");
		}
	}
}
```

#### Quiz 02.03.02

**Question**

What is the value of x after this code?

```java
int x = 2;
switch(x) {
	case 1: x = 2;
	case 2: x = 3;
	case 3: x = 4;
}
```

**Answer**

`4`

#### The default Case

A switch statement can have an optional default case.

The default case can be used for performing a task when none of the cases is matched.

For example:

```java
class Demo {
	public static void main(String[ ] args) {
		int day = 5;

		switch(day) {
			case 1:
				System.out.println("Monday");
			case 2:
				System.out.println("Tuesday");
			case 3:
				System.out.println("Wednesday");
			default: 
				System.out.println("Another day");
		}
	}
}
```

> :warning: No break is needed in the default case, as it is always the last statement in the switch.

#### Quiz 02.03.03

**Question**

What is the output of the following code?

```java
int a = 11; int b = 12; int c = 40;
switch (a) {
	case 40:
		System.out.println(b);
		break;
	default:
		System.out.println(c);
}
```

**Answer**

`40`

#### Lesson Takeaways

The switch statement is a handy way to check for multiple values and run code.

- Remember, that each case is followed by a value and a colon.
- Each case needs a break statement, or the code of the other cases will continue to get executed.
- The default case can be used to run code if none of the cases match.

In the next lesson, we will learn how to check for multiple conditions.

##### Boxes

###### Boxes

You are making a robot that should categorize items by their color. Each color corresponds to a box with a specific number.

For simplicity, our program will handle 3 colors:
red goes to box #1
green goes to box #2
black goes to box #3

Your program needs to take a color as input and output the corresponding box number.

Sample Input
green

Sample Output
2

> :warning: Remember, you can use the switch statement to check for different conditions.

###### Answer

```java
import java.util.Scanner;

public class Program {
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in); 
		String color = input.nextLine(); 

		switch (color){
			case "red":
				System.out.println(1); 
				break; 
			case "green": 
				System.out.println(2); 
				break; 
			case "black": 
				System.out.println(3); 
				break;
		}
	}
}
```

#### Quiz 02.03.04

**Question**

You are making a menu for a vending machine. The choice is stored in a variable called item.

Fill in the blanks to output the selected beverage.

```java
switch(item) {
case 1_____
	System.out.println("Coffee");
	_____;
_____ 2:
	System.out.println("Tea");
	break;
default_____
	System.out.println("Try again");
}
```

**Answer**

`:`, `break`, `case` and `:`

### Lesson 02.04: Multiple Conditions

#### Multiple Conditions

In some cases we need to combine multiple conditions, for example, let's say we want to check if the age value is greater than 18 and less than 50.

This can be done using the && operator.

```java
class Demo {
	public static void main(String[ ] args) {
		int age = 42;
		if (age > 18 && age < 50) {
		    System.out.println("Welcome!");
		}
	}
}
```

> :warning: The `&&` operator is also referred to as the logical AND operator.

#### Quiz 02.04.01

**Question**

Fill in the blank to test both conditions in the following if statement.

```java
int age = 23;
int money = 4000;
if (age > 21 _____ money > 500) {
	System.out.println("Welcome");
}
```

**Answer**

`&&`

#### The OR Operator

The OR operator (||) checks if any one of the conditions is true.

For example:

```java
class Demo {
	public static void main(String[ ] args) {
		int age = 25;
		int height = 100;

		if (age > 18 || height > 150) {
			System.out.println("Welcome!");
		}
	}
}
```

> :warning: The code above will print Welcome! if age is greater than 18 or if height is greater than 150.

#### Quiz 02.04.02

**Question**

What is the output of the following code?

```java
int a = 11; int b = 12;
int c = 40;
if (a > 100 || b > 3) {
	System.out.println(a); 
}
else {
	System.out.println(c);
}
```

**Answer**

`11`

#### NOT

The NOT (`!`) logical operator is used to reverse the condition.

If a condition is true, the NOT logical operator will make it false, and vice versa.

Example:

```java
class Demo {
	public static void main(String[ ] args) {
		int age = 25;
		if(!(age > 18)) {
			System.out.println("Too Young");
		}
		else {
			System.out.println("Welcome");
		}
	}
}
```

> :warning: `!(age > 18)` reads as "if age is NOT greater than 18".

#### Quiz 02.04.03

**Question**

If x = 3, what is the result of the following:

```java
!(x < 3)
```

**Answer**

`true`

#### Multiple Conditions

You can chain multiple conditions using parentheses and the logical operators.

For example:

```java
class Demo {
	public static void main(String[ ] args) {
		String country = "US";
		int age = 42;
		
		if((country == "US" || country == "GB") && (age > 0 && age < 100)) {
		    System.out.println("Allowed");
		}
	}
}
```

#### Quiz 02.04.03

**Question**

Fill in the blanks to output OK if the temp variables value is between 36 and 38. Output Alert if its not.

```java
if(temp>=36 _____ temp <=38) {
	System.out.println("_____");
}
_____ {
System.out.println("_____");
}
```

**Answer**

`&&`, `OK`, `else` and `Alert`

#### Lesson Takeaways  

Logical operators allow to combine multiple conditions.

- [ ] The AND operator && combines two conditions and checks if both of them are true.
- [ ] The OR operator || check if any of the conditions if true.
- [ ] The NOT operator ! reverses the condition.

Next lesson will be fun! We will cover loops, which allow to repeat a block of code multiple times. 

##### Age Group

###### Age Group

Given the age of a person as an input, output their age group.

Here are the age groups you need to handle:

Child: 0 to 11
Teen: 12 to 17
Adult: 18 to 64

Sample Input
42

Sample Output
Adult

> :warning: Remember, you can use the AND operator to combine conditions, like x>0 && x<20.

###### Solution

```java
import  java.util.Scanner;

public class Program {
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		int age = input.nextInt();
		
		if (age >= 0 && age < 12){
			System.out.println("Child"); 
		}
		else if (age >= 12 && age < 17){
			System.out.println("Teen");
		}
		else if (age >= 18 && age < 65){
			System.out.println("Adult"); 
		}
	}
}
```

#### Quiz 02.04.04

**Question**

What is the result of this condition, when hour = 9, day = 23?

```java
(hour > 12 && day <= 15) || (hour < 8)﻿
```

**Answer**

`false`

### Lesson 02.05: While Loops

#### Loops

Loops allow you to repeat a block of code multiple times.

> :warning: For example, a banking app can loop over all bank transactions and check for some conditions.

#### while Loops

A while loop statement repeatedly executes a target statement as long as a given condition is true.

Example:

```java
class Demo {
	public static void main(String[ ] args) {
		int x = 3;
		
		while(x > 0) {
			System.out.println(x);
			x = x-1;
		}
	}
}
```

The while loops check for the condition x > 0. If it evaluates to true, it executes the statements within its body. Then it checks for the statement again and repeats.

> :warning: The code above will output the numbers 3 to 1, and then stop, as the condition will become false, after x reaches 0.

#### Quiz 02.05.01

**Question**

Fill in the required symbols to create a valid while loop.

```java
while _____x > 0) _____
	System.out.println(x);
	x = x-2;
_____
```

**Answer**

`(`, `{` and `}`

#### while Loops

Let's look at the code again:

```java
class Demo {
	public static void main(String[ ] args) {
		int x = 3;
		
		while(x > 0) {
			System.out.println(x);
			x = x-1;
		}
	}
}
```

The line x = x-1; is important, as without it the condition would never become false and the loop would run forever. 

Each time the loop runs, 1 is subtracted from x.

#### Quiz 02.05.02

**Question**

Rearrange the code to output the numbers 1 to 5 using a while loop.

**Answer**

`int num = 1;`, `while (num <= 5) {`, `System.out.println(num);`, `num = num + 1;` and `}` 

#### while Loops

As it is common to decrease or increase a variable by 1 during loops, Java provides increment and decrement operators.

These are a shorter way to increase or decrease the value of a variable by one.

For example, the statement x=x-1; can be simplified to x--;

```java
class Demo {
	public static void main(String[ ] args) {
		int x = 3;
		
		while(x > 0) {
			System.out.println(x);
			x--;
		}
	}
}
```

#### Quiz 02.05.03

**Question**

What is the output of this code?

```java
int x = 8;
x--;
x--;
System.out.println(x);
```

**Answer**

`6`

#### while Loops

Similarly, the increment operator ++ is used to increase the value of a variable by one.

Here is a loop that outputs the numbers 1 to 10:

```java
class Demo {
	public static void main(String[ ] args) {
		int x = 1;

		while(x <= 10) {
			System.out.println(x);
			x++;
		}
	}
}
```

#### Quiz 02.05.04

**Question**

x++ is equivalent to:

**Answer**

`x = x + 1;`

#### while Loops

Some loops require to increase or decrease the value of a variable by a different number.

For example, lets output only the even numbers from 0 to 10.

```java
class Demo {
	public static void main(String[ ] args) {
		int x = 0;
		
		while(x <= 10) {
			System.out.println(x);
			x=x+2;
		}
	}
}
```

Surprise! There is also a shorter way for x = x+2; It can be written as x+=2;

> :warning: Similarly, there are shorthand operators for other mathematical operations, such as -= for subtraction, *= for multiplication, etc.

#### Quiz 02.05.05

**Question**

What is the value of x after this code?

```java
int x = 2;
x += 1;
x *= 2;
x -= 2;
```

**Answer**

`4`

#### while Loops

You can perform calculations and other operations in loops.

For example, let's calculate the sum of the numbers from 1 to 100 and output it:

```java
class Demo {
	public static void main(String[ ] args) {
		int sum = 0;
		int num = 0;
		
		while(num <= 100) {
			sum += num;
			num++;
		}
		System.out.println(sum);
	}
}
```

We add the value of num to sum each time the loop runs, and then increase the num value by 1.

At the end of the loop, sum holds the result of our calculation.

> :warning: Notice that the last print statement is out of the while scope.

#### Quiz 02.05.06

**Question**

How many times will the following loop work?

```java
int x = 0;
int y = 5;
while (x < y) {
	System.out.println("Hello");
	x++; 
}
```

**Answer**

`5`

#### do-while Loops

Another variation of the while loop is do-while.

For example:

```java
class Demo {
	public static void main(String[ ] args) {
		int x = 1;
		do {
			System.out.println(x);
			x++;
		} while(x < 5);
	}
}
```

Notice that the condition appears at the end of the loop, so the statements in the loop execute once before it is tested.

Even with a false condition, the code will run once.

Also, note the semicolon after the while condition.

> :warning: The difference between while and do-while is that do-while is guaranteed to run at least once, even with a false condition. Try changing the condition in the code above and see the result.

#### Quiz 02.05.07

**Question**

What is the output of this code?

```java
int x = 3;
do {
	x *= x; 
} while(x<5);
System.out.println(x);
```

**Answer**

`9`

#### Lesson Takeaways

Here is a summary about the while loop:

- The code in the while loop runs as long as the condition is true.
- The ++ and -- operators are used to increase and decrease the value of a variable by one.
- Java provides shorthand operators to perform mathematical operations on a variable, for example x = x * 9; can be written as x * = 9.
- The do-while loop is similar to a while loop, but it is guaranteed to run at least once.

We will learn about another loop type in the next lesson!

##### Sum

###### Sum

Your math teacher asked you to calculate the sum of the numbers 1 to N, where N is a given number.

Task: Take an integer N from input and output the sum of the numbers 1 to N, inclusive.

Sample Input:
10

Sample Output:
55

> :warning: The sum of the numbers 1 to 10 is 55.

###### Solution

```java
import  java.util.Scanner;

public class Program {
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in); 
		int n = input.nextInt(); 
		int sum = 0;
		int i = 1;  
		while (i <= n){
			sum += i;
			i++;
		}
		System.out.println(sum);
	}	
}
```

#### Quiz 02.05.08

**Question**

Fill in the blanks to create a countdown that outputs the numbers 10 to 0.

```java
int x = 10;
_____ (x >= 0) {
	System._____.println(x);
	_____--;
}
```

**Answer**

`while`, `out` and `x`

### Lesson 02.06: For Loops

#### for Loops

Another kind of loop is the for loop.

It looks like this:

```java
class Demo {
	public static void main(String[ ] args) {
		for(int x=1; x<5; x++) {
			System.out.println(x);
		}
	}
}
```

This will output the numbers 1 through 4.

#### for Loop

The for loop has 3 components:

```java
class Demo {
	public static void main(String[ ] args) {
		for(int x=1; x<5; x++) {
			System.out.println(x);
		}
	}
}
```

The first part runs once when we enter the loop and initializes the variable.

The second part is the condition of the loop.

The third part runs every time the loop runs.

> :warning: Notice the semicolons (;) after the parts of the loop.

#### Quiz 02.06.01

**Question**

Fill in the missing symbols to create a valid for loop.

```java
for(int x=10 _____ x>0 _____ x--) 
	System.out.println(x);
}
```

**Answer**

`;`, `;` and `{`

#### for Loops

You can have any type of condition and any type of increment statements in the for loop.

The example below prints only the even values between 0 and 10:

```java
class Demo {
	public static void main(String[ ] args) {
		for(int x=0; x<=10; x+=2) {
			System.out.println(x);
		}
	}
}
```

> :warning: The for loop is best when we know the number of times we need to run the loop.

#### Quiz 02.06.02

**Question**

How many numbers will the following loop output?

```java
for (int i = 2; i < 10; i = i*i) {
	System.out.println(i);
}
```

**Answer**

2

#### Loop Control

Remember the break statement from the switch?

It can also be used to terminate loops.

Example:

```java
class Demo {
	public static void main(String[ ] args) {
		int x = 1;
		
		while(x < 10) {
			System.out.println(x);
			if(x == 4) {
				break;
		    	}
		    	x++;
		}
	}
}
```

> :warning: This will end the loop when x reaches the value 4.

#### break

It also works in the for loop:

```java
class Demo {
	public static void main(String[ ] args) {
		for(int x=1; x<10; x++) {
			System.out.println(x);
			if(x == 4) {
				break;
			}
		}
	}
}
```

Here is one example use case of break:

For example, you are making a calculator and need to take numbers from the user to add together and stop when the user enters "stop".

In this case, the break statement can be used to end the loop when the user input equals "stop".

#### Quiz 02.06.03

**Question**

Fill in the blanks to stop the loop when the num variable reaches the value 55.

```java
for(int num=0; num<1000; num++) { 
	_____ (num == 55) {
		_____;
	}
}
```

**Answer**

`if` and `break`

#### continue

Another control statement is continue.

It makes the loop skip the current iteration and go to the next one.

Example:

```java
class Demo {
	public static void main(String[ ] args) {
		for(int x=10; x<=40; x+=10) {
			if(x == 30) {
				continue;
			}
			System.out.println(x);
		}
	}
}
```

The above code skips the value of 30, as directed by the `continue` statement.

> :warning: An example use case of continue: <br/> An airline ticketing system needs to calculate the total cost for all tickets purchased. Tickets for children under the age of 3 are free. We can use a while loop to iterate through the list of passengers and calculate the total cost of their tickets. Here, the continue statement can be used to skip the children.

#### Quiz 02.06.04

**Question**

Fill in the blanks to output the numbers 10 to 20, skipping the number 13.

```java
for(int x=10; x<=20; x++) _____
	if(x _____ 13) {	
		_____;  
	}
	System.out.println(_____);
}
```

**Answer**

`{`, `==`, `continue` and `x`

#### Lesson Takeaways

Great progress! Here is a summary:

- The for loop has the following syntax:
```java
for(init; condition; increment) {
	// code
}
```
- The break statement can be used to stop a loop.
- The continue statement can be used to skip the current iteration of the loop and jump to the next one.

##### Factorial

###### Factorial

The factorial of a number N is equal to 1 * 2 * 3 * ... * N. For example, the factorial of 5 is 1* 2 * 3 * 4 * 5  = 120.

Create a program that takes a number from input and outputs the factorial of that number.

> :warning: Use a for loop to make the calculation, and start the loop from the number 1.

###### Solution

```java
import java.util.Scanner;

class Demo{
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in); 
		int n = input.nextInt(); 
		long factorial = 1; 
		for (int i=1; i<=n; i++){
			factorial *= i;
		}
		System.out.println(factorial); 
	}
}
```

#### Quiz 02.06.05

**Question**

Fill in the blanks to calculate and output the sum of the numbers 1 to 1000 using a for loop.

```java
int sum = 0;
_____ (int x=1; x<=1000; _____) {
	sum+=_____;
}
_____.out.println(_____);
```

**Answer**

`for`, `x++`, `x`, `System` and `sum`

### Quiz 02: Module 2 Quiz

**Question M02.01**

Fill in the blanks to output Passed if the grade value is greater than 70, and Failed, if it's not.

```java
_____ (grade>70) {
	System.out.println("_____");
}
_____ {
	System.out.println("_____");
}
```

**Question M01.02**

Drag & drop to create a program that takes a number as input, and checks if it's in the range of 1 to 5. 

In case it is, output Correct.

```java
Scanner sc = new _____(System.in);
int num = _____.nextInt();
_____ (num>=1 _____ num<=5) {
	System.out.println("Correct");
}
```

- [ ] `++`
- [ ] `for`
- [ ] `&&`
- [ ] `||`
- [ ] `if`
- [ ] `sc`
- [ ] `and`

**Question M01.03**

Fill in the blanks to create a loop that outputs all the numbers from 1 to 100, except the number 42.

```java
_____ (int x=1; x<=100 _____ x++) {
	_____ (x==42) {
		continue;
	}
	System.out.println(_____);
}
```

**Question M01.04**

How many numbers will the following while loop output?

```java
int x = 8;
while(x>0) {
	System.out.println(x);
	x-=3;
}
```

**Question M01.05**

Fill in the blanks to create a valid switch statement that outputs the first 3 letters by their position in the alphabet.

```java
switch(position) {
	case 1_____
		System.out.println("A");
		break;
	_____ 2:
		System.out.println("B");
		break_____
	case _____: 
		System.out.println("C");
		_____;
}
```

[Check Module 02 Quiz Answers](./module-quiz-solutions/module-02-quiz-solutions.md)

&nbsp;

---

&nbsp;

## Module 03: Arrays

### Lesson 03.01: Arrays

#### Arrays

Imagine a program that needs to store the ages of 10 users.

With variables, you would need to create 10 separate variables for each of the users. That would be really not effective and repetitive.

Arrays can help in these situations!

An array stores multiple values in a single variable.

#### Arrays

An array needs to be declared, just like a variable, with the type of the items it will hold.

To declare an array, you need to define the type of the elements with square brackets.

```java
int[ ] ages;
```

> :warning: The name of the array is ages. The type of elements it will hold is int.

#### Quiz 03.01.01

**Question**

Fill in the blanks to declare an array called `names` of type `String`.

```java
_____ _____ _____;
```

**Answer**

`String`, `[]` and `names`

#### Arrays

Now, to create the array, we need to specify the number of items it will hold using the new keyword:

```java
int[ ] ages;
ages = new int[5];
```

The code above creates an array of 5 integers.

We can combine the above code into one line:

```java
int[] ages = new int[5];
```

#### Quiz 03.01.02

**Question**

Fill in the blanks to create an array of Strings that will hold 8 items.

```java
String _____ names = _____ String[_____];
```

**Answer**

`[]`, `new` and `8`

```java
String [] names = new String[8];
```

#### Arrays

The items in an array are accessed using their position, also called their index.

Here is an example, setting the item with the index 2 to the value 25:

```java
ages[2] = 25;
```

The index is specified in square brackets, next to the array name.

#### Arrays

The item with index 2 is actually the 3rd item of the array.

That's because array indexes start from 0, meaning that the first element's index is 0 rather than one. So, the maximum index of the array int[5] is 4.

Let's set the first items value:

```java
ages[0] = 18;
```

#### Quiz 03.01.03

**Question**

What is the index of the 2nd element of an array? 

- [ ] `2`
- [ ] `3`
- [ ] `1`

**Answer**

`1`

#### Arrays

Similar to setting values, we can also access values of the array, using square brackets and the index of the item we want to access:

```java
public class Demo {
	public static void main(String[] args) {
		int[] ages = new int[5];
		ages[0] = 18;
		ages[2] = 25;
		System.out.println(ages[2]);
	}
}
```

This will output the value of the 3rd item.

#### Quiz 03.01.04

**Question**

Fill in the blanks to declare an array of 5 Strings, set the first item to the value "James". Then output the first item of the array.

```java
_____ names = _____ String[5];
names _____ = "James";
System.out.println(_____[0]);
```

**Answer**

`String[]`, `new`, `[0]` and `names`

```java
String[] names = new String[5];
names[0] = "James";
System.out.println(names[0]);
```

#### Arrays

If you already know what values to store in the array, instead of assigning them one by one, you can use the following syntax:

```java
public class Demo {
	public static void main(String[] args) {
		String[ ] names = { "A", "B", "C", "D"};
		System.out.println(names[2]);
	}
}
```

Place the values in a comma-separated list, enclosed in curly braces.

The code above automatically creates an array containing 4 items, and stores the provided values.

> :warning: Sometimes you might see the square brackets placed after the array name, which also works, but the preferred way is to place the brackets after the array's data type.

#### Quiz 03.01.05

**Question**

What is the output of this code?

```java
int tmp[ ] = {5, 8, 9, 3};
System.out.println(tmp[2]);
```

**Answer**

`9`

#### Lesson Takeaways

Awesome! Here are some key points about arrays:

Arrays allow you to store multiple values in a variable.

When creating an array, we need to provide the type of the items and the size of the array, like this:

```java
int[] nums = new int[4];
```

Array items are accessed using their indexes, placed in square brackets. The first item has the index 0.

You can also create an array with values using the following syntax:

```java
int[] nums = {4, 6, 2, 1};
```

In the next lesson we will learn how to loop over the values of an array and make calculations.

##### Vending Machine

###### Vending Machine

You are making a program for a vending machine that provides drinks.

The menu of the drinks is stored in an array called menu:

```java
String[] menu = {"Tea", "Espresso", "Americano", "Water", "Hot Chocolate"}; 
```

Take the choice of the customer as an integer from input and output the corresponding menu item.

Also, check for errors: in case the input is out of the range of the array, output "Invalid".

> :warning: The choice defines the index of the array.

###### Solution 

```java
import  java.util.Scanner;

public class Program {
	public static void main(String[] args) {
		String[] menu = {"Tea", "Espresso", "Americano", "Water", "Hot Chocolate"};
		Scanner input = new Scanner(System.in);
		int choice = input.nextInt(); 
		if (choice < 0 || choice >= 5) {
			System.out.println("Invalid"); 
		}
		else {
			System.out.println(menu[choice]);
		} 
	}
}
```

#### Quiz 03.01.06

**Question**

Fill in the blanks to create an array, multiply the 2nd and the 4th items and output the result.

```java
int[] x = {4, 3, 6, 8_____;
int res = x[_____] _____ x[3];
System.out.println(_____);
```

**Answer**

`}`, `1`, `*` and `res`

```java
int[] x = {4, 3, 6, 8};
int res = x[1] * x[3];
System.out.println(res);
```

### Lesson 03.02: Looping Over Arrays

#### Arrays

Let's learn how to output the items of an array using a loop.

To use a loop, we first need to find out how many items the array stores. 

For that, the array has a length property, which is accessed like this:

```java
public class Demo {
	public static void main(String[] args) {
		int[] ages = {18, 33, 24, 64, 45};
		System.out.println(ages.length);
	}
}
```

This will output the number of items stored in the array.

#### Quiz 03.02.01

**Question**

What is the output of this code?

```java
int[] x = {3, 2, 1};
System.out.println(x.length);
```

**Answer**

`3`

#### Arrays and Loops

Now, when we know the number of items, we can use a for loop and output all the items of the array:

```java
public class Demo {
	public static void main(String[] args) {
		int[] ages = {18, 33, 24, 64, 45};
		
		for(int x=0;x<ages.length;x++) {
			System.out.println(ages[x]);
		}
	}
}
```

We used the x variable of the loop as the index for our array. During each iteration of the loop, the next item of the array is accessed.

#### Arrays

We can also use a for loop to make calculations using array values. For example, let's calculate the sum of all values in an array:

```java
public class Demo {
	public static void main(String[] args) {
		int[] ages = {18, 33, 24, 64, 45};
		int sum = 0;
		for(int x=0;x<ages.length;x++) {
			sum += ages[x];
		}
		System.out.println(sum);
	}
}
```

In the code above, we declared a variable sum to store the result and assigned it 0.

Then we used a for loop to iterate through the array, and added each item's value to the variable.

#### Quiz 03.02.02

**Question**

Fill in the blanks to calculate the sum of the items of the double array called nums using a for loop, then output it to the screen.

```java
double sum = 0.0;
_____ (int x=0; x<nums._____; x++) {
	sum += _____[x];
}
System.out.println(_____);
```

**Answer**

`for`, `length`, `nums` and `sum`

```java
double sum = 0.0;
for (int x=0; x<nums.length; x++) {
	sum += nums[x];
}
System.out.println(sum);
```

#### for-each Loop

Java provides another version of the for loop, called the for-each loop, to loop over arrays, making the code shorter and easier to read.

Here it is:

```java
public class Demo {
	public static void main(String[] args) {
		int[] nums = {2, 3, 5, 7};
		
		for (int x: nums) {
			System.out.println(x);
		}
	}
}
```

The loop creates a variable, which automatically is assigned to each value of the array during the loop.

You can call the variable anything you want: we called it x in our example.

> :warning: Notice the colon after the variable - it reads as "for each x in nums".

#### Quiz 03.02.03

**Questions**

Fill in the blanks to create a valid for-each loop, iterating over an array of Strings called names.

```java
_____ (String n _____ names) _____ 
	System.out.println(n);
}
```

**Answers**

`for`, `:` and `{`

```java
for (String n: names) { 
	System.out.println(n);
}
```

#### for-each Loop

Let's use a for-each loop to calculate the sum of all values of an array:

```java
public class Demo {
	public static void main(String[] args) {
		int[] ages = {18, 33, 24, 64, 45};
		int sum = 0;
		for(int x: ages) {
			sum += x;
		}
		System.out.println(sum); 
	}
}
```

Note, that in this case we do not have the index, we have the value of each item of the array.

#### Quiz 03.02.04

**Questions**

What is the output of this code?

```java
int[ ] nums = {3, 8, 5, 2};
int res = 0;
for(int x: nums) {
	if(x > res) {
		res = x;
	}
}
System.out.println(res);
```

**Answer**

`8`

#### Lesson Takeaways

Looping over arrays is fun!

You can use a for loop to loop over an array.

The length property is used to get the number of items of the array.

```java
for(int x=0;x<arr.length; x++) {
	// current item is arr[x]
}
```

Another way to loop over arrays is the for-each loop:

```java
for(int x: arr) {
	// current item is x
}
```

We will learn about multidimensional arrays in the next lesson!

##### Annual Revenue

###### Annual Revenue

The given code declares an array that holds the monthly revenues for a company for a year.

You need to calculate the average monthly revenue for the year.

For that, calculate the sum of the revenue for all the months and divide it by the number of items in the array.

> :warning: You can find the number of items in the array using the length property. As the array is of type double, output the result as a double.

###### Solution

```java
public class Program {
	public static void main(String[] args) {
	double[] revenueMonths = {88750, 125430, 99700, 14500, 158000, 65000, 99000, 189000, 210000, 42000, 165800, 258900};
	double revenueYear = 0.0; 
	for (double r: revenueMonths){
		revenueYear += r; 
	}
	int months = revenueMonths.length; 
	System.out.println(revenueYear/months); 
	}
}
```

#### Quiz 03.02.05

**Questions**

Rearrange to create a valid for-each loop, that creates an array called arr and outputs each item of the array.

- `System.out.println(item);`
- }
- int[] arr = {1, 2, 3, 4};
- for(int item: arr){

**Answer**

1. int[] arr = {1, 2, 3, 4};
2. for(int item: arr){
3. `System.out.println(item);`
4. }

### Lesson 03.03: Multidimensional Arrays

#### Multidimensional Arrays

Arrays can have multiple dimensions (or number of indices).

For example, imagine a ticketing program that is storing seat numbers in a stadium, which have a row and column number.

Or a chess board, where each square has 2 coordinates: a letter and a number

> :warning: The arrays in these examples have 2 dimensions.

#### Multidimensional Arrays

To create multidimensional arrays, place each array within its own set of square brackets:

```java
int[ ][ ] sample = { {1, 2, 3}, {4, 5, 6} };
```

Note that the array is created using two square brackets, specifying the two-dimensionality.

#### Multidimensional Arrays

To access an element in the two-dimensional array, provide two indexes, one for the array, and another for the element inside that array. 

The following example accesses the first element in the second array of sample:

```java
public class Demo {
	public static void main(String[] args) {
		int[][] sample = { {1, 2, 3}, {4, 5, 6} };
		int x = sample[1][0];
		System.out.println(x);
	}
}
```

#### Quiz 03.03.01

**Questions**

Fill in the blanks to create a 2-dimensional array, then output the 2nd item of the 3rd row.

```java
int[][] grid = {{8, 4}, {2, 5}, {9, 6}_____;
int x = grid[_____][_____];
System.out.println(x);
```

**Answer**

`}`, `2` and `1`

```java
int[][] grid = {{8, 4}, {2, 5}, {9, 6}};
int x = grid[2][1];
System.out.println(x);
```

#### Multidimensional Arrays

The array's two indexes are called row index and column index.

Here is how we can visualize it:

```java
public class Demo {
	public static void main(String[] args) {
		int[][] sample = { 
			{1, 2, 3}, 
			{4, 5, 6} 
		}; 
		int x = sample[1][0];
		System.out.println(x);
	}
}
```

Each row is an item, which is an array. So, to access a value, we provide the row index, then the column index.

#### Quiz 03.03.02

**Questions**

What is the output of this code?

```java
int array[ ][ ] =  {{3, 5, 8}, {7, 54, 1, 12, 4}}; 
System.out.println(array[0][2]);
```

**Answer**

`8`

#### Looping

To loop over a 2-dimensional array, we need nested for loops:

```java
public class Demo {
	public static void main(String[] args) {
		int[][] sample = {
		{1, 2, 3},
		{4, 5, 6}
		};
		for(int x=0; x<sample.length; x++) {
			for(int y=0; y<sample[x].length; y++) {
				System.out.println(sample[x][y]);
			}
		}  
	}
}
```

The first loop iterates over the rows, and the second one over their items.

#### Quiz 03.03.03

**Questions**

Fill in the blanks to create nested for loops that iterates over a 2-dimensional array called arr and calculates the sum of all items.

```java
int sum = 0;
for(int x=0; x<arr._____; x++) {
	for(int y=0; y<_____[x].length; y++) {
		sum += _____[x][_____];
	}
}
System.out.println(sum);
```

**Answer**

`length`, `arr`, `arr` and `y`

```java
int sum = 0;
for(int x=0; x<arr.length; x++) {
	for(int y=0; y<arr[x].length; y++) {
		sum += arr[x][y];
	}
}
System.out.println(sum);
```

#### Lesson Takeaways 

Arrays with multiple dimensions are simply arrays that contain other arrays.

The number of square brackets match the dimension of the array, for example [][] denotes a 2-dimensional array.

To access the items of the array, specify the row index in the first square brackets, followed by the column index in the second.

##### Movie Theater

###### Movie Theater

You are creating a ticketing program for a small movie theater.

The seats are represented using a 2-dimensional array.

Each item can have the values 1 and 0 - 1 is occupied, and 0 if it's free.

Your program needs to take as input the row and the column of the seat and output Free if it's free, and Sold if it's not.

###### Solution

```java
import java.util.Scanner;

public class Program {
	public static void main(String[] args) {
		int[][] seats = {
		    {0, 0, 0, 1, 1, 1, 0, 0, 1, 1},
		    {1, 1, 0, 1, 0, 1, 1, 0, 0, 0},
		    {1, 1, 1, 1, 1, 1, 1, 1, 1, 1},
		    {0, 0, 0, 1, 1, 1, 1, 0, 0, 0},
		    {0, 1, 1, 1, 0, 0, 0, 1, 1, 1}
		};
		// Take inputs
		Scanner input = new Scanner(System.in);
		// System.out.println("Row number:"); 
		int row = input.nextInt();
		// System.out.println("Column number:");  
		int col = input.nextInt();
		// Occupancy
		if (seats[row][col] == 0){
			System.out.println("Free");
		}
		else if (seats[row][col] == 1) {
			System.out.println("Sold"); 
		}
	}
}
```

### Quiz 03: Module 3 Quiz

**Question M03.01**

The array dates stores birth years of a group of people. You need to calculate how many of them were born in the year 2000. 

Fill in the blanks to create a loop and calculate the result.

```java
int count = 0;
for(int x = 0; x<dates._____; _____++) {
	if(dates[x] _____ 2000) {
		_____ ++;
	}
} 
System.out.println(count)
```

**Question M03.02**

What is the output of this code?

```java
int arr[ ] = new int[3];
for (int i = 0; i < 3; i++) {
	arr[i] = i;
} 
int res = arr[0] + arr[2];
System.out.println(res);
```

**Question M03.03**

Fill in the blanks to create an array of even integers, then calculate the sum of the first and last elements and output it.

```java
int even = {2, 4, 6, 8};
int res = _____[0]+even_____;
System.out.println(_____);
```

**Question M03.04**

Fill in the blanks to calculate the sum of all elements in the array arr using a for-each loop:

```java
int res = 0;
_____ (int el _____ arr) {
	res += _____;
}
```

**Question M03.05**

The array matrix has 2 dimensions, and it is composed of 5 rows and 3 columns.

Fill in the blanks to add the last element of the first row with the first element of the last row.

```java
matrix[0][_____] + matrix[_____][0];
```

[Check Module 03 Quiz Answers](./module-quiz-solutions/module-03-quiz-solutions.md)

&nbsp;

---

&nbsp;

## Module 04: Methods

### Lesson 04.01: Methods

#### Methods

A method is a block of code designed to perform a particular task.

For example, our app can have methods like login(), logout(), convert(), etc.

The println() that we use for output is also a method.

> :warning: The purpose of a method is to create it once and call it multiple times when needed to perform particular tasks.

#### Methods

You can define your own methods to perform your desired tasks.

Here is an example:

```java
static void welcome() {
	System.out.println("Welcome");
	System.out.println("I am a method");
	System.out.println("End of method");
}
```

The code above declares a method called welcome, which prints 3 lines of text.

> :warning: Note that the name of the method is followed by parentheses (). The statements of the method are inside curly braces.

#### Methods

Let's look at the code again:

```java
static void welcome() {
	System.out.println("Welcome");
	System.out.println("I am a method");
	System.out.println("End of method");
}
```

`static` is needed to be able to use the method in `main`. You will learn about the static keyword in more advanced lessons.

`void` means that this method does not have a return value. You will learn more about return values later in this module.

`welcome` is the name of the method.

#### Quiz 04.01.01

**Questions**

Drag & drop to declare a valid method called login.

```java
_____ _____ _____() {
	System.out.println("Login");
}
```

**Answer**

`static`, `void` and `login`

```java
static void login() {
	System.out.println("Login");
}
```

#### Calling a Method

After defining the method, we can use it in our program by "calling" it.

To call a method, type its name followed by a set of parentheses.

For example:

```java
public class Demo {
	static void welcome() { 
		System.out.println("Welcome"); 
		System.out.println("I am a method"); 
		System.out.println("End of method"); 
	}
	public static void main(String[] args) {
		welcome();
	}
}
```

> :warning: Run the code to see the result.

#### Quiz 04.01.02

**Questions**

Fill in the blanks to call the login() method in main.

```java
public static void main(String[] args) {
	login_____;
}
```

**Answer**

`()`

```java
public static void main(String[] args) {
	login();
}
```

#### Calling a Method

You can call a method as many times as necessary.

Example:

```java
class Demo {
	static void welcome() { 
		System.out.println("Welcome"); 
		System.out.println("I am a method"); 
		System.out.println("End of method"); 
	}
	public static void main(String[] args) {
		welcome();
		//some code
		welcome();
		welcome();
	}
}
```

#### Lesson Takeaways

Great job! Here are the main points to remember when defining your own methods:

- Methods are reusable, we define them once and can call them multiple times.
- To call a method, use its name, followed by parentheses.
- The void keyword means that the method does not return a value.

We will learn about return values in the next lessons, so stay tuned!

##### Bot

###### Bot

You are making an automated response program for a store.

The bot should take a number from the user as input and reply with an automated message. There are currently 3 responses, that you need to a handle:

- User message: "1", Reply: "Order confirmed"
- User message: "2", Reply: "info@sololearn.com"
- For any other number, the reply should be: "Try again".

The given code calls a method called bot(). Define the method, which should take an integer input from the user, and handle the above mentioned cases, by outputting the corresponding reply. Do not change the method call in main().

###### Solution

```java
import java.util.Scanner;

public class Program {
	static void bot(){
		/*
		User message: "1", Reply: "Order confirmed"
		User message: "2", Reply: "info@sololearn.com"
		For any other number, the reply should be: "Try again". 
		*/
		Scanner input = new Scanner(System.in); 
		int choice = input.nextInt(); 
		if (choice == 1){
			System.out.println("Order confirmed"); 
		}
		else if (choice == 2){
			System.out.println("info@sololearn.com"); 
		}
		else {
			System.out.println("Try again"); 
		}
	}
	public static void main(String[] args) {
		bot();
	}
}
```

#### Quiz 04.01.03

**Questions**

Fill in the blanks to define a method called shoot, and call it twice in main.

```java
class Program {
	_____ void _____() { 
		System.out.println("Boom"); 
	}
	public static void main(String[] args) {
		shoot_____;
		shoot()_____
	}
}
```

**Answer**

`static`, `shoot`, `()` and `;`

```java
class Program {
	static void shoot() { 
		System.out.println("Boom"); 
	}
	public static void main(String[] args) {
		shoot();
		shoot();
	}
}
```

### Lesson 04.02: Method Parameters

#### Method parameters

Methods can have parameters that can be used in their code. Parameters are defined in parentheses and can act as variables in a method.

For example, let's add a String parameter called name to our welcome() function:

```java
static void welcome(String name) {
	System.out.println("Welcome, " + name);
}
```

> :warning: The above method takes a String called name as its parameter, which is used in the method.

#### Method Parameters

Now, when calling the method, we need to pass it a value for the name parameter inside the parentheses:

```java
class Demo {
	static void welcome(String name) { 
		System.out.println("Welcome, "+name);
	}
	public static void main(String[] args) {
		welcome("James");
		welcome("Amy");
	}
}
```

This way, we can call our method with different parameters and generate different results based on them.

> :warning: The values passed as parameters are called arguments.

#### Quiz 04.02.01

**Questions**

Fill in the blanks to define a method doubleNum that takes an integer as its parameter and outputs its double.

Then call it in main with the argument 42.

```java
static void doubleNum(_____ num) {
	System.out.println(num _____ 2);
}
public static void main(String[] args) {
	_____ (42);
}
```

**Answer**

`int`, `*` and `doubleNum`

```java
static void doubleNum(int num) {
	System.out.println(num * 2);
}
public static void main(String[] args) {
	doubleNum(42);
}
```

#### Multiple Parameters

Methods can take multiple parameters. For that, we simply need to separate them using commas, for example:

```java
static void welcome(String name, int age) {
	System.out.println("Welcome, "+name);
	System.out.println("Your age: "+age);
}
```

Now, our welcome() method takes a String and an integer as its parameters.

#### Multiple Parameters

Now, when calling the function, we need to provide all the parameters:

```java
class Demo {
	static void welcome(String name, int age) {
		System.out.println("Welcome, "+name);
		System.out.println("Your age: "+age);
	}
	public static void main(String[] args) {
		welcome("James", 42);
		welcome("Amy", 25);
	}
}
```

> :warning: Note that the arguments need to match the parameters and must be passed in the same order.

#### Quiz 04.02.02

**Questions**

Fill in the blanks to define a method that takes two integers and outputs their sum.

Then call it in main for the arguments x and y.

```java
static void sum(int a, _____ b) {
	System.out.println(_____+b);
}
public static void main(String[] args) {
	int x = 8;
	int y = 11;	
	_____(x _____ y);
}
```

**Answer**

`int`, `a`, `sum` and `,`

```java
static void sum(int a, int b) {
	System.out.println(a+b);
}
public static void main(String[] args) {
	int x = 8;
	int y = 11;
	sum(x, y);
}
```

#### Method Parameters

Method parameters are really handy! They allow our method to work with different values and produce results.

For example, we can create a method to calculate a given percentage of a number and output it:

```java
class Demo {
	static void perc(double num, int percentage) {
		double res = num*percentage/100;
		System.out.println(res);
	}
	public static void main(String[] args) {
		perc(530, 23);
	}
}
```

Open the code to see the method in action!

#### Quiz 04.02.03

**Questions**

What is the result of demo(8, 3)?

```java
static void demo(int x, int y) {
	if(x<y) {
		System.out.println(x+y);
	}
	else {
		System.out.println(x%y);
	}
}
```

**Answer**

`2`

#### Lesson Takeaways

Method parameters are awesome!

Here is a summary:
- You can define parameters in the parentheses.
- Multiple parameters need to be separated by commas.
- The parameters are available in the method, like variables of the given names.
- When calling a method, you need to provide its parameters in the same order, as defined.

You will learn how to return values in the next lesson.

##### Feet to Inches Converter

###### Feet to Inches Converter

You need to make a method that converts a foot value to inches.

1 foot has 12 inches. 

Define a convert() method, that takes the foot value as its argument and outputs the inches value. The result must be a double.

> :warning: The given code takes the foot value as input and passes it to the convert method. Define the convert method, so that the given code works.

###### Solution

```java
import java.util.Scanner;

public class Program {
	static void convert(double foot){
		System.out.println(foot * 12); 
	}
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		double num = input.nextDouble(); 
		// Convert foot to inch
		convert(num);
	}
}
```

#### Quiz 04.02.04

**Questions**

Fill in the blanks to define a method with 2 parameters called area. It should calculate and output the area of a rectangle based on the width and height.

```java
_____ void _____ (double w _____ double h) {
	double res = w*h;
	System._____.println(_____);
}
```

**Answer**

`static`, `area`, `,`, `out` and `res`

```java
static void area (double w, double h) {
	double res = w*h;
	System.out.println(res);
}
```

### Lesson 04.03: Returning From Methods

#### Return Values

The methods we have seen so far output their result. In some cases we do not need to output the result, but need to assign it to a variable, to work with it in our program.

In these cases, we need our method to return the result value.

#### The Return Type

Consider a method from our previous lesson, that was used to output a percentage of the given value:

```java
static void perc(double num, int percentage) {
	double res = num*percentage/100;
	System.out.println(res);
}
```

The void keyword in the definition specifies that the method does not return any value.

#### Quiz 04.03.01

**Questions**

Which of the following specifies that a method does not return any value?

**Answer**

`void`

#### The Return Type

Here is the same function definition, specifying the return type to be a double:

```java
static double perc(double num, int percentage) {
	...
}
```

This means that our perc method will return a value of type double.

#### Quiz 04.03.02

**Questions**

What is the return type of the following method?

```java
static String msg(int a, double b)
```

**Answer**

`String`

#### Returning a Value

Now, we can return our result using the return keyword:

```java
static double perc(double num, int percentage) {
	double res = num*percentage/100;
	return res;
}
```

The return keyword stops the method from executing. If there are any statements after return, they won't run.

#### Returning a Value

After we have created our method that returns a value, we can call it in our code and assign the result to a variable:

```java
class Demo {
	static double perc(double num, int percentage) {
		double res = num*percentage/100;
		return res;
	}
	public static void main(String[] args) {
		double x = perc(530, 23);
		System.out.println("Result is: "+x);
	}
}
```

> :warning: Returning is useful when you don't need to print the result of the method, but need to use it in your code. For example, a bank account's withdraw() method could return the remaining balance of the account.

#### Quiz 04.03.03

**Questions**

Fill in the blanks to create a method that takes two integers and returns their sum. Then, call it in main.

```java
static _____ sum(int x _____ int y) {
	int res = x+y;  
	_____ res;
} 
public static void main(String[] args) {
	int n1 = 33;
	int n2 = 12;
	int n = _____ (n1, n2);
}
```

**Answer**

`int`, `,`, `return` and `sum`

```java
static int sum(int x, int y) {
	int res = x+y;  
	return res;
} 
public static void main(String[] args) {
	int n1 = 33;
	int n2 = 12;
	int n = sum(n1, n2);
}
```

#### Returning a Value

Let's create a method that takes integer parameter, checks if the grade is over 70 and returns a boolean result.

Then, let's use it in main:

```java
class Demo {
	static boolean check(int grade) {
		if(grade >=70) {
			return true;
		}
		else {
			return false;
		}
	}
	public static void main(String[] args) {
		int x = 89;
		if(check(x) == true) {
			System.out.println("Congrats!");
		} 
	}
}
```

As you can see, we can use the method in an if statement, because it returns a boolean value.

> :warning: The method can be used anywhere in our program to check if the grade is passing or not. In case anything changes in the logic of the check, we will need to modify the method only, without touching the rest of the program.

#### Lesson Takeaways

You did it! This was the last lesson of this course.

Here is a quick recap for returning from methods:

- Use the return statement to return a value from your method.
- The method needs to have its return type specified before its name.
-  The returned value can be assigned to a variable when calling the method.

##### Celsius to Fahrenheit

###### Celsius to Fahrenheit

You are making a Celsius to Fahrenheit converter. 

Write a method to take the Celsius value as an argument and return the corresponding Fahrenheit value.

Sample Input
36

Sample Output
96.8

The given code takes the celsius value as input and passes it to a fahr() method, which you need to create.

> :warning: The following equation is used to calculate the Fahrenheit value: 1.8 * celsius + 32.

###### Solution

```java
import java.util.Scanner;

public class Program {
	static double fahr(double celsius){
		double fahrenheit = 1.8 * celsius + 32;
		return fahrenheit;
	}
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		double c = sc.nextDouble(); 

		System.out.println(fahr(c));
	}
}
```

#### Quiz 04.03.04

**Question**

Fill in the blanks to create a method called checkAge, which returns true, in case its age parameter is greater than 18.

```java
static _____ checkAge(int age) {
	_____ (age >= 18) {
		return _____;
	}
	else {
		_____ false;
	}
}
```

**Answer**

`boolean`, `if`, `true` and `return`

```java
static boolean checkAge(int age) {
	if (age >= 18) {
		return true;
	}
	else {
		return false;
	}
}
```

### Quiz 04: Module 4 Quiz

**Question M04.01**

Fill in the blank to define a method that does not return a value.

```java
static _____ printBill(double amount) {
	// some code
}
```

**Question M04.02**

Rearrange the code to declare a method that returns the square of its argument.

- `int result = a*a;`
- `return result;`
- `public int max(int a){`
- `}`

**Question M04.03**

Fill in the blanks to declare a method that takes one argument of type int and returns the factorial of that number. The factorial is the product of all whole numbers from 1 to the given number.

```java
static int fact(_____ num) {
	int res = 1;
	for(int x=1; x <= _____; x++) {
	res *= _____;
	}
	_____ res;
}
```

**Question M04.04**

Fill in the blanks to create a method called check that takes two parameters, a name and an age. Output the name if the age is greater than 17, and Error, if it's not.

```java
static _____ check(String name, int age) _____ 
	if(age > 17) {
		System.out.println(_____);
	}
	_____ {
		System.out.println("Error");
	}
}
```

&nbsp;

---

&nbsp;
