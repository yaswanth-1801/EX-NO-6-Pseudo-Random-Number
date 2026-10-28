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
    int i;

    srand(time(0));

    printf("Pseudo-Random Numbers:\n");

    for (i = 0; i < 5; i++)
        printf("%d\n", rand() % 100);

    return 0;
}
```

# OUTPUT:
<img width="1105" height="605" alt="image" src="https://github.com/user-attachments/assets/36722885-868b-4e19-96da-34cb9610a5a2" />

# RESULT:
Thus, The above Pseudo Random Number Generation Program is executed successfully.
