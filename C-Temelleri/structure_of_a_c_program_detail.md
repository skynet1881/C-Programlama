# Structure of a C Program (With Example and Diagrams)

1- Documentation: Comments describing the program's purpose.  
```c
// This program prints "Hello World!" to the console
```

2- Preprocessor Directives: Instructions for the compiler to include files or define constants.  
```c
#include <stdio.h> // Standard Input Output header file
```

3- Definition Section: Declaration of constants, macros, and global variables.  
```c
#define PI 3.14 // Defining a constant
```

4- Global Declarations: Declaration of global variables and function prototypes.  
```c
int globalVar; // Global variable declaration
```

5- Main Function: The entry point of the program where execution begins.  
```c
int main() {
    int n; // Local variable declaration
    printf("Enter your number here: ");
    scanf("%d", &n); // Taking input from user
    printf("You entered: %d\n", n); // Displaying the input
    return 0; // Indicating successful completion
}
```

6 - Variable Declarations: Declaration of local variables within functions.
```c
int n; // Local variable declaration
```

7- Statements & Expressions: Instructions that perform actions and calculations.  
```c
for(int i = 1; i <= n; i++) {
    printf("%d\n", i); // Printing numbers from 1 to n
}
```

8- Sub Programs/Functions: Blocks of code that perform specific tasks, which can be called from the main function or other functions.  
```c
int factorial(int num)
{
    int fact = 1;
    for(int i = 1; i <= num; i++)
    {
        fact *= i; // Calculating factorial
    }

    return fact; // return final result
}
```

9- Return Statement: Indicates the end of a function and optionally returns a value to the caller.  
```c
return 0; // Indicating successful completion
```




