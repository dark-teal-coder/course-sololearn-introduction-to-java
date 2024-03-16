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

**Answer M02.01**

`if`, `Passed`, `else` and `Failed`

```java
if (grade>70) {
	System.out.println("Passed");
}
else {
	System.out.println("Failed");
}
```

**Question M02.02**

Drag & drop to create a program that takes a number as input, and checks if it's in the range of 1 to 5. 

In case it is, output Correct.

```java
Scanner sc = new _____(System.in);
int num = _____.nextInt();
_____ (num>=1 _____ num<=5) {
	System.out.println("Correct");
}
```

- `++`
- `for`
- `&&`
- `||`
- `if`
- `sc`
- `and`
- `Scanner`

**Answer M02.02**

1. `Scanner`
2. `sc`
3. `if`
4. `&&`

```java
Scanner sc = new Scanner(System.in);
int num = sc.nextInt();
if (num>=1 && num<=5) {
	System.out.println("Correct");
}
```

**Question M02.03**

Fill in the blanks to create a loop that outputs all the numbers from 1 to 100, except the number 42.

```java
_____ (int x=1; x<=100 _____ x++) {
	_____ (x==42) {
		continue;
	}
	System.out.println(_____);
}
```

**Answer M02.03**

`for`, `;`, `if` and `x`

```java
for (int x=1; x<=100; x++) {
	if (x==42) {
		continue;
	}
	System.out.println(x);
}
```

**Question M02.04**

How many numbers will the following while loop output?

```java
int x = 8;
while(x>0) {
	System.out.println(x);
	x-=3;
}
```

**Answer M02.04**

3

**Question M02.05**

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

**Answer M02.05**

`:`, `case`, `;`, `3` and `break`

```java
switch(position) {
	case 1:
		System.out.println("A");
		break;
	case 2:
		System.out.println("B");
		break;
	case 3: 
		System.out.println("C");
		break;
}
```
