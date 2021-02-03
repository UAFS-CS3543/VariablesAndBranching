# Variables And Branching


## Input Functions
These functions read data from the input device and store the data in variables in memory.  The type of the variable (char, int, double) dictates the amuount of memory in bytes reserved to store the data, and the format for the data (Ascii Character, Binary, Twos-Complement Binary).  The two input functions that we have used or will use are:

### getchar()
Reads a character from stdin(keyboard) and stores it in a variable of type char. The following code example defines a variable named **ch** of type **char** and reads the character(byte) from the keyboard and stores (=) it into the variable, **ch**.

```cpp
char ch;
ch = getchar();
```

### scanf()
Reads different types of input from stdin(keyboard).  The type of input that you want to read is indicated by the format specifier(%c).  Use the proper format specifier for the type of data you are reading. The following example accomplishes the same task as the getchar() example.

Specifier | Type of Data
--------- | ------------
%c | Character (char)
%d | Integer (int)
%f | Floating-Point (double)

```cpp
char ch;
scanf("%c",&ch);
```

The following code example defines a variable of type **int** named **value** and reads the integer value from stdin(keyboard) and stores it into the variable, **value**.

```cpp
int value;

scanf("%d",&value);
```

## Output Functions
These functions write data to the output device (screen).  The type of the variable (char, int, double) dictates the amuount of memory in bytes reserved to store the data, and the format for the data (Ascii Character, Binary, Twos-Complement Binary).  The two output functions that we have used or will use are:

### putchar()
This function writes an ASCII character stored in a memory variable to the screen.  Here we have added to the example code to output the character stored in **ch**. The program uses putchar(ch) to write the character stored in the variable **ch** to the screen.

```cpp
char ch;

ch = getchar();
putchar(ch);
```

### printf("format string", variable list)
Allows printing of formatted output using format specifiers for each of the variables in the output.  The type of output that you desire is indicated by the format specifier(%c).  Use the proper format specifier for the type of data you are writing. In the example we have added printf() for output.

Specifier | Type of Data
--------- | ------------
%c | Character (char)
%d | Integer (int)
%5.2f | Floating-Point (double)

```cpp
char ch;

scanf("%c",&ch);
printf("The character stored in ch is %c\n",ch);
```

The following code example defines a variable of type **int** named **value** and reads the integer value from stdin(keyboard) and stores it into the variable, **value**. It then displays the value using printf().

```cpp
int value;

scanf("%d",&value);
printf("The value is %d\n",value);
```

# Problems

## Problem One
Write a program named **prob1.c**, that will read an integer from the keyboard and display the output like the following example:

##### Example 1

Enter a number: 67     
The number entered was 67.


## Problem Two
Write a program named **prob2.c**, that will read an two integers from the keyboard and display the output like the following example:

##### Example 1

Enter the value for x: 5
Enter the value for y: 9

The value for x is 5 and the value for y is 9


## Problem Three
Write a program named **prob2.c**, that will read an two integers from the keyboard and determine which one is larger and display the output like the following example:

##### Example 1

Enter the value for x: 5
Enter the value for y: 9

The value in y is greater than the value in x.

##### Example 2

Enter the value for x: 55
Enter the value for y: 8

The value in y is not greater than the value in x.

