# Lab-Report-2
## STudent Information
Name:Tasmim Jannat
ID:26002159
Course:BSC in CSE
## Experiment Title
 Leap Year Determination Using C Programming
 
 ## Objective
 1. To learn how to use conditional statements in C.
 2. To determine whether a given year is a leap year or not 
 3. To understand logical operators and conditions.
    
## Concept 
A leap year is defined as:
•	A leap year must divisible by 4 and not divisible by 100, OR  
•	It’s a leap year divisible by 400. 

## Algorithm
  
Step 1: Start  
Step 2: Input the year 
Step 3: If year is divisible by 400 ( Display Leap year )
Step 4:Else if year is divisible by 4 AND not divisible by 100
            ( Display Leap year )
Step 5:Else ( Display not a leap year )
Step 6:Display result
Step 9: End  

## Code
#include<stdio.h>
int main(){
    int year;
    printf("Enter Year:");
    scanf("%d", &year);
    if (year % 400 == 0)
    printf("%d is a Leap Year.\n", year);
    else if (year % 4 == 0 && year % 100 != 0)
    printf("%d is a Leap Year.\n", year);
    else
    printf("%d is not a Leap Year.\n", year);
  return 0;
}

## Result
Input: EnterYer: 2020
Output:2020 is a Leap Year.
Input: EnterYer: 2022
Output:2022 is not a Leap Year.

## Conclusion
The leap year checking program demonstrates the proper use of nested conditions and logical expressions. This lab improved my problem solving ability and helped me to understand control flow in C.

