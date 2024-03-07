### Quiz: Module 3 Quiz

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

**Answer M03.01**

`length`, `x`, `==` and `count`

```java
int count = 0;
for(int x = 0; x<dates.length; x++) {
	if(dates[x] == 2000) {
		count++;
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

**Answer M03.02**

`2`

**Question M03.03**

Fill in the blanks to create an array of even integers, then calculate the sum of the first and last elements and output it.

```java
int even = {2, 4, 6, 8};
int res = _____[0]+even_____;
System.out.println(_____);
```

**Answer M03.03**

`even`, `[3]` and `res`

```java
int even = {2, 4, 6, 8};
int res = even[0]+even[3];
System.out.println(res);
```

**Question M03.04**

Fill in the blanks to calculate the sum of all elements in the array arr using a for-each loop:

```java
int res = 0;
_____ (int el _____ arr) {
	res += _____;
}
```

**Answer M03.04**

`for`, `:` and `el`

```java
int res = 0;
for (int el: arr) {
	res += el;
}
```

**Question M03.05**

The array matrix has 2 dimensions, and it is composed of 5 rows and 3 columns.

Fill in the blanks to add the last element of the first row with the first element of the last row.

```java
matrix[0][_____] + matrix[_____][0];
```

**Answer M03.05**

`2` and `4`

```java
matrix[0][2] + matrix[4][0];
```
