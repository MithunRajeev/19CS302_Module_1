# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:
## Aim:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm:
1. Start. 
2. Declare a variable value of type char. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Check eligible for marriage. 
6. If age >= 21, print "Eligible". 
7. If false, print " Not Eligible". 
8. End.  

## Program:
```
#include <stdio.h>
int main()
{
    int age;
    scanf("%d",&age);
    if(age>=21)
    printf("He is eligible for marriage\n");
    else
    printf("He is Not eligible for marriage\n");
    return 0;   
}
```
## Output:
![Screenshot_6-5-2025_114950_training saveetha in](https://github.com/user-attachments/assets/7a58f5a5-7c60-401f-bfbc-16b710cdfff4)

## Result:
Thus the program was executed and the output was verified successfully.
