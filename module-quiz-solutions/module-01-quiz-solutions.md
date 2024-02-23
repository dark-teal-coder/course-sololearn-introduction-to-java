### Quiz: Module 1 Quiz

**Problem M01.P01**

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

**Solution M01.S01**

`class`, `main`, `out` and `+`

```java
class Program {
	public static void main (String[] args) {
        int a = 8;
		int b = 4;
		System.out.println(a + b);    
	}
}
```

**Problem M01.P02**

Which of the following is a valid comment?
- [ ] `## some text`
- [ ] `** some text **`
- [ ] `/* some text */`
- [ ] `*/ some text /*`

**Solution M01.S02**

`/* some text */`

**Problem M01.P03**

Fill in the blanks to output "Hello, " followed by the value stored in the name variable.

```java
String name = "James";
String msg = "_____"+_____;
System.out.println(_____);
```

**Solution M01.S03**

`Hello, `, `name` and `msg`

```java
String name = "James";
String msg = "Hello, "+name;
System.out.println(msg);
```

**Problem M01.P04**

What is the output of this code?

```java
int x = 5;
int y = 3;
int z = x%y;
System.out.println(x-z);
```

**Solution M01.S04**

`3`

**Problem M01.P05**

You need to find how many minutes there are in a day. A day has 24 hours, each hour has 60 minutes. These values are stored in variables.

Fill in the blanks to calculate and output the required value.

```java
int hours = 24;
int minutes = 60;
int result = hours _____ minutes;
System.out.println(_____);
```

**Solution M01.S05**

`*` and `result`

```java
int hours = 24;
int minutes = 60;
int result = hours * minutes;
System.out.println(result);
```
