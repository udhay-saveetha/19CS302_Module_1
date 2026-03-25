# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1.Start the program.

2.Declare a variable to store age.

3.Read the age from the user.

4.Use if to check if age ≥ 21 and display eligibility.

5.End the program.  

## Program:
```
/*
Program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

*/

#include <stdio.h>

int main()
{
    int age;
    
    printf("Enter age: ");
    scanf("%d", &age);
    
    if (age >= 21)
    {
        printf("Eligible for marriage.\n");
    }
    else
    {
        printf("Not eligible for marriage.\n");
    }
    
    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/c4976aa9-cf55-45a9-b516-b43cf4643a7a)



## Result:
Thus the program was executed and the output was verified successfully.
