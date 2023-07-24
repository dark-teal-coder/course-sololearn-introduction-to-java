<img src="https://raw.githubusercontent.com/dark-teal-coder/dark-teal-coder/main/images/coder-no-background-000-128-128.png"
    alt="coder-black-background-000-128-128.png" width="100" height="100" align="right" style="margin:0px 5%; padding: 5px;">
<p>
    GitHub: <a href="https://github.com/dark-teal-coder">@dark-teal-coder</a>
    <br />
    First Published Date: 2022-08-26
    <br />
    Last Modified Date: 2023-07-19
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

The `println` instruction needs to be followed by parentheses.

Drag and drop to create a line of code that runs without errors.

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

In Java, every line of code that can actually run needs to be inside a class.

You can call the class anything you want.

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

The main method contains the code that executes when we run our program.

In this case, the `println` method will be executed, when we run our program.

&nbsp;

---

&nbsp;

## Control Flow

&nbsp;

xxx

&nbsp;

---

&nbsp;

## Arrays

&nbsp;

xxx

&nbsp;

---

&nbsp;

## Methods

&nbsp;

xxx

&nbsp;

---

&nbsp;
