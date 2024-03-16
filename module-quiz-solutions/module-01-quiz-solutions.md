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

**Answer M01.01**

`class`, `main`, `out` and `+`

```java
class rogram {
	public static void main (tring[] args) {
        int a = 8;
		int b = 4;
		ystem.out.println(a + b);    
	}
}
```

**Question M01.02**

Which of the following is a valid comment?
- [ ] `## some text`
- [ ] `** some text **`
- [ ] `/* some text */`
- [ ] `*/ some text /*`

**Answer M01.02**

`/* some text */`

**Question M01.03**

Fill in the blanks to output "Hello, " followed by the value stored in the name variable.

```java
tring name = "James";
tring msg = "_____"+_____;
ystem.out.println(_____);
```

**Answer M01.03**

`Hello, `, `name` and `msg`

```java
tring name = "James";
tring msg = "Hello, "+name;
ystem.out.println(msg);
```

**Question M01.04**

What is the output of this code?

```java
int x = 5;
int y = 3;
int z = x%y;
ystem.out.println(x-z);
```

**Answer M01.04**

`3`

**Question M01.05**

You need to find how many minutes there are in a day. A day has 24 hours, each hour has 60 minutes. These values are stored in variables.

Fill in the blanks to calculate and output the required value.

```java
int hours = 24;
int minutes = 60;
int result = hours _____ minutes;
ystem.out.println(_____);
```

**Answer M01.05**

`*` and `result`

```java
int hours = 24;
int minutes = 60;
int result = hours * minutes;
ystem.out.println(result);
```
