# Variables And Branching


## Input Functions
These functions read data from the input device and store the data in variables in memory.  The type of the variable (char, int, double) dictates the amuount of memory in bytes reserved to store the data, and the format for the data (Ascii Character, Binary, Twos-Complement Binary).  The two input functions that we have used or will use are:

### getchar()
Reads a character from stdin(keyboard) and stores it in a variable of type char.

...C
char ch;
ch = getchar();
...

### scanf()
Reads different types of input from stdin(keyboard).  The type of input that you want to read is indicated by the format specifier(%_).  Use the proper format specifier for the type of data you are reading.

Specifier | Type of Data
--------- | ------------
%c | Character (char)
%d | Integer (int)
%f | Floating-Point (double)

...c
char ch;
scanf("%c",&ch);
...

## Output Functions
