# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n, i;
    printf("Enter how many random numbers to generate: ");
    scanf("%d", &n);
    srand(time(0));
    printf("Random numbers:\n");
    for (i = 0; i < n; i++) 
    {
        printf("%d\n", rand());
    }
}
```

# OUTPUT:

<img width="774" height="668" alt="image" src="https://github.com/user-attachments/assets/893fe787-9b0e-41ea-bd2b-171fcf932e47" />



# RESULT:
Thus the Implementation of Pseudorandom Number Generation Using Standard library was executed successfully.
