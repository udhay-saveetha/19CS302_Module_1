
# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1.Start the program and declare an array for 7 subject marks.

2.Input marks for all 7 subjects using a loop.

3.Calculate total by summing all subject marks.

4.Calculate average and percentage (percentage = total / max_total × 100).

5.Display total, average, and percentage.
## Program:
```
/*
Program to calculate the total marks, average, and percentage of marks obtained in seven subjects.


#include <stdio.h>

int main()
{
    int marks[7], i, total = 0;
    float average, percentage;

    printf("Enter marks for 7 subjects:\n");
    for(i = 0; i < 7; i++)
    {
        scanf("%d", &marks[i]);
        total += marks[i];
    }

    average = total / 7.0;
    percentage = (total / 700.0) * 100;

    printf("Total Marks = %d\n", total);
    printf("Average Marks = %.2f\n", average);
    printf("Percentage = %.2f%%\n", percentage);

    return 0;
}


```

## Output:

![image](https://github.com/user-attachments/assets/1e1eb468-a26a-492d-bbd5-ce767633f47d)


## Result:
Thus the program was executed and the output was verified successfully.
