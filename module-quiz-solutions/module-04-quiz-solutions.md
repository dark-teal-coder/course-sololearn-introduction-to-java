### Quiz 04: Module 4 Quiz

**Question M04.01**

Fill in the blank to define a method that does not return a value.

```java
static _____ printBill(double amount) {
	// some code
}
```

**Answer M04.01**

`void`

```java
static void printBill(double amount) {
	// some code
}
```

**Question M04.02**

Rearrange the code to declare a method that returns the square of its argument.

- `int result = a*a;`
- `return result;`
- `public int max(int a){`
- `}`

**Answer M04.02**

1. `public int max(int a){`
2. `int result = a*a;`
3. `return result;`
4. `}`

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

**Answer M04.03**

`int`, `num`, `x` and `return`

```java
static int fact(int num) {
	int res = 1;
	for(int x=1; x <= num; x++) {
	res *= x;
	}
	return res;
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

**Answer M04.04**

`void`, `{`, `name` and `else`

```java
static void check(String name, int age) { 
	if(age > 17) {
		System.out.println(name);
	}
	else {
		System.out.println("Error");
	}
}
```
