<img src="https://raw.githubusercontent.com/dark-teal-coder/dark-teal-coder/main/images/coder-no-background-000-128-128.png"
    alt="coder-black-background-000-128-128.png" width="100" height="100" align="right" style="margin:0px 5%; padding: 5px;">
<p>
    GitHub: <a href="https://github.com/dark-teal-coder">@dark-teal-coder</a>
    <br />
    First Published Date: 2022-08-26
    <br />
    Last Modified Date: 2024-02-22
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

- [01 Basic Concepts](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#01-basic-concepts)
- [02 Control Flow](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#02-control-flow)
- [03 Arrays](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#03-arrays)
- [04 Methods](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#04-methods)

&nbsp;

---

&nbsp;

## 01 Basic Concepts

&nbsp;

### Lesson 01: Getting Started with Java

#### Welcome to Java!

Java is one of the most popular programming languages.

Java's slogan is "Write once, run anywhere". Java programs can run on different platforms, including mobile, desktop, and other portable systems. You can use Java to build apps, games, banking applications, web apps, and much more!

#### Coding

Humans use computer programs to communicate with machines. Without computer programs, we wouldn't have smartphones, websites, or even exploration in outer space.

<p align="center">
    <img src="./images/java-introduction-01-01-p02-a.png" alt="./images/java-introduction-01-01-p02-a.png" width="50%" height="50%">
</p>

Learning some coding can help you innovate and create different solutions to problems, giving you a competitive edge in this technology-driven world. 

#### Quiz 01.01

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

#### Quiz 01.02

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

#### Quiz 01.03

**Question**

Drag and drop to write a line of code that outputs "New message".

**Answer**

"New message"

#### The Code Playground

Ready to write, run and test real code?

Open the Code Playground below. Then hit "run" to see the output on the screen.

```java
public class Program
{
    public static void main(String[] args) {
		System.out.println("Welcome to the Code Playground");
	}
}
```

You'll see other lines of code when you open the Code Playground. They are needed for the code to run without errors. You will learn everything about these lines in the upcoming lessons.

#### Quiz 01.04

**Question**

Drag and drop to complete a line of code that outputs "Game Over".

**Answer**

`println`

#### Quiz 01.05

**Question**

The `println` instruction needs to be followed by parentheses. Drag and drop to create a line of code that runs without errors.

**Answer**

`(` and `)`

#### Quiz 01.06

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

### Lesson 02: Multiple Statements

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

#### Quiz 02.01

**Question**

Each statement needs to end with a

**Answer**

Semicolon `;`

#### Multiple Statements

You can add as many statements (or lines of code) as you need.

The following piece of code consists of 2 statements. It outputs two messages in different lines.

```java
public class Program
{
    public static void main(String[] args) {
        System.out.println("Name:");
        System.out.println("Surname:");
	}
}
```

> :warning: Remember your code will result in an error if you forget the semicolons `;` at the end of the statements.

#### Quiz 02.02

**Question**

Drag and drop to complete code that runs without errors

**Answer**

`(`, `;` and `)`

#### Quiz 02.03

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
public class Program
{
    public static void main(String[] args) {
        System.out.println("Points:");
        System.out.println(500);
	}
}
```

> :warning: Your code will result in an error if you forget the quotes around the text.

#### Quiz 02.04

**Question**

Drag and drop to write code that runs without errors

**Answer**

`"` and `(`

#### Quiz 02.05

**Question**

Drag and drop to write code that runs without errors

**Answer**

`println`, `;` and `out`

#### Quiz 02.06

**Question**

Java is a case-sensitive language. This means that you need to pay attention to the correct input of uppercase and lowercase letters.

Drag and drop to write code that runs without errors:

**Answer**

`System`

#### Quiz 02.07

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

###### Solution

```java
public class Program
{
    public static void main(String[] args) {
        System.out.println("My first Java Code Coach!");
	}
}
```

&nbsp;

### Lesson 03: Program Structure

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

#### Quiz 03.01

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

#### Quiz 03.02

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

#### Quiz 03.03

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

#### Quiz 03.04

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

###### Solution

```java
class Demo{
    public static void main(String[] args) {
        System.out.println("Coding is fun");
    }
}
```

&nbsp;

### Lesson 04: Variables

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

#### Quiz 04.01

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

#### Quiz 04.02

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

#### Quiz 04.03

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

#### Quiz 04.04

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

#### Quiz 04.05

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

#### Quiz 04.06

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

###### Solution 

```java
public class Program {
    public static void main(String[] args) {
        String alphabet = "abcdefghijklmnopqrstuvwxyz";
        System.out.println(alphabet);
    }
}
```

#### Quiz 04.06

**Question**

Drag & drop to create a valid Java program that declares a variable, assigns it to a value and outputs it.

**Answer**

`class`, `main`, `String`, `println` and `color`

&nbsp;

### Lesson 05: Variable Types

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

#### Quiz 05.01

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

#### Quiz 05.02

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

#### Quiz 05.03

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

#### Quiz 05.04

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

#### Quiz 05.05

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

###### Solution 

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

#### Quiz 05.06

**Question**

Drag & drop to fill in the correct data types for the given variables.

**Answer**

`int`, `boolean`, `double` and `String`

&nbsp; 

### Lesson 06: Doing Math

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

#### Quiz 06.01

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

#### Quiz 06.02

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

#### Quiz 06.03

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

#### Quiz 06.04

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

#### Quiz 06.05

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

#### Quiz 06.06

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

###### Solution

```java
public class Program {
    public static void main(String[] args) {
        int wins = 54;
        int ties = 31;
        System.out.println(wins + ties*0.5); 
    }
}
```

#### Quiz 06.06

**Question**

You are packing eggs in baskets, each holding 8 eggs. All packed baskets need to be full.

Fill in the blanks to create a program that calculates how many of the given eggs will be leftover.

**Answer**

`eggs`, `%` and `result`

### Lesson 07: Java Comments

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

#### Quiz 07.01

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
        //int height = 122;
        System.out.println(age);
        //System.out.println(height);
    }
}
```

> :warning: The commented lines of code will get ignored when you run the program.

#### Quiz 07.02

**Question**

What is the output of this code?

```java
int x = 8;
//x = 2;
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
        /*  This is just a
        demo program
        that outputs a number */
        int age = 23;
        
        System.out.println(age);
    }
}
```

Anything between the `/*` and `*/` symbols becomes a comment.

> :warning: You can also use multi-line comments to comment out multiple lines of code.

#### Quiz 07.03

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

###### Solution

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

### Quiz: Module 1 Quiz

**Question 01.01**

Fill in the blanks to create a valid program that declares two variables and outputs their sum.

```java
_____ Program {
	public static void _____ (String[] args) {
		int a = 8;
		int b = 4;
		System._____.println(a _____ b);    
	}
}
```

**Question 01.02**

Which of the following is a valid comment?

**Question 01.03**

Fill in the blanks to output "Hello, " followed by the value stored in the name variable.

```java
String name = "James";
String msg = "_____"+_____;
System.out.println(_____);
```

**Question 01.04**

What is the output of this code?

```java
int x = 5;
int y = 3;
int z = x%y;
System.out.println(x-z);
```

**Question 01.05**

You need to find how many minutes there are in a day. A day has 24 hours, each hour has 60 minutes. These values are stored in variables.

Fill in the blanks to calculate and output the required value.

```java
int hours = 24;
int minutes = 60;
int result = hours _____ minutes;
System.out.println(_____);
```

[Check Module 01 Quiz Solutions](./module-quiz-solutions/module-01-quiz-solutions.md)

&nbsp;

---

&nbsp;

## 02 Control Flow

### Lesson 08: Taking User Input

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

#### Quiz 08.01

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

#### Quiz 08.02

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

#### Quiz 08.03

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

###### Solution

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

#### Quiz 08.04

**Question**

Fill in the blanks to create a valid program that takes a String and an integer as input, then outputs a welcome message.

**Answer**

`import`, `main`, `new`, `sc`, `.` and `out`

### Lesson 09: Conditionals

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
  //some code 
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

#### Quiz 09.01

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

#### Quiz 09.02

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
        } else { 
           System.out.println("Welcome!");
        }
    }
}
```

> :warning: As age equals 30, the condition in the if statement evaluates to false and the else statement is executed.

#### Quiz 09.03

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
			} else {
				System.out.println("Too Young");
			}
		} else {
			System.out.println("Error");
		}
	}
}
```

> :warning: You can nest as many if-else statements as you want, however the code will become harder to read and understand.

#### Quiz 09.04

**Question**

What is the value of x after this code is run?

```java
int x = 3;
if(x > 2) {
    if(x >= 5) {
        x = 4;
    }else{
        x = 6;
    }
} else {
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
        } else if(age <= 16) {
           System.out.println("Too Young");
        } else if(age < 100) {
           System.out.println("Welcome!");
        } else {
           System.out.println("Really?");
        }
    }
}
```

> :warning: You can include as many else-if statements as you need.

#### Quiz 09.05

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
  //some code
} else if(condition) {
//some other code
} else {
  //some other code
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

###### Solution

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

#### Quiz 09.06

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

### Lesson 10: The switch Statement

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

#### Quiz 10.01

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

#### Quiz 10.02

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

#### Quiz 10.03

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

###### Solution

```java
import  java.util.Scanner;

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

#### Quiz 10.04

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

### Lesson 11: Multiple Conditions

### Lesson 12: While Loops

### Lesson 13: For Loops

### Quiz: Module 2 Quiz

&nbsp;

xxx

&nbsp;

---

&nbsp;

## 03 Arrays

### Lesson 14: Arrays

### Lesson 15: Looping Over Arrays

### Lesson 16: Multidimensional Arrays

### Quiz: Module 3 Quiz

&nbsp;

xxx

&nbsp;

---

&nbsp;

## 04 Methods

### Lesson 17: Methods

### Lesson 18: Method Parameters

### Lesson 19: Returning From Methods

### Quiz: Module 4 Quiz

&nbsp;

xxx

&nbsp;

---

&nbsp;
