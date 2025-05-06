# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:
## Aim:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm:
1. Start. 
2. Declare three variable value of type int for marks. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Find total and average. 
6. Print the result 
7. End.    

## Program:
```
#include <stdio.h>
int main()
{
    int marks[6];
    int total = 0;
    for (int i = 0; i < 6; i++)
{
        scanf("%d", &marks[i]);
        total += marks[i];
    }
    float average = (float)total / 6;
    float percentage = (float)(total * 100) / (6 * 100);
    printf("Total marks = %.2f\n", (float)total);
    printf("Average marks = %.2f\n", average);
    printf("Percentage = %.2f\n", percentage);
    return 0;
}
```
## Output:

![Screenshot_6-5-2025_11534_training saveetha in](https://github.com/user-attachments/assets/5b55b761-9b55-4160-90bb-bfd3692c1b78)

## Result:
Thus the program was executed and the output was verified successfully.
