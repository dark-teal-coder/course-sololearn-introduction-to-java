<img src="https://raw.githubusercontent.com/dark-teal-coder/dark-teal-coder/main/images/coder-no-background-000-128-128.png"
    alt="coder-black-background-000-128-128.png" width="100" height="100" align="right" style="margin:0px 5%; padding: 5px;">
<p>
    GitHub: <a href="https://github.com/dark-teal-coder">@dark-teal-coder</a>
    <br />
    First Published Date: 2022-08-26
    <br />
    Last Modified Date: 2024-02-18
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

- [Basic Concepts](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#basic-concepts)
- [Control Flow](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#control-flow)
- [Arrays](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#arrays)
- [Methods](https://github.com/dark-teal-coder/course-sololearn-introduction-to-java/blob/main/course-note-sololearn-introduction-to-java.md#methods)

&nbsp;

---

&nbsp;

## Basic Concepts

&nbsp;

### Lesson: Getting Started with Java

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

### Lesson: Multiple Statements

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

### Lesson: Program Structure

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

### Lesson: Variables

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

### Lesson: Variable Types

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

### Lesson: Doing Math

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

### Lesson: Java Comments

### Quiz: Module 1 Quiz

&nbsp;

---

&nbsp;

## Control Flow

### Lesson: Taking User Input

### Lesson: Conditionals

### Lesson: The switch Statement

### Lesson: Multiple Conditions

### Lesson: While Loops

### Lesson: For Loops

### Quiz: Java for Beginners Module 2 Quiz

&nbsp;

xxx

&nbsp;

---

&nbsp;

## Arrays

### Lesson: Arrays

### Lesson: Looping Over Arrays

### Lesson: Multidimensional Arrays

### Quiz: Java for Beginners Module 3 Quiz

&nbsp;

xxx

&nbsp;

---

&nbsp;

## Methods

### Lesson: Methods

### Lesson: Method Parameters

### Lesson: Returning From Methods

### Quiz: Java for Beginners Module 4 Quiz

&nbsp;

xxx

&nbsp;

---

&nbsp;
