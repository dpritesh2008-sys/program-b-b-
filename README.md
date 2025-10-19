# program-b-b-
C module 2
EX NO:2-b) Hollow rectangular pattern. 
Date:19/10/2025 
Name: VASANTH S 
Ref no: 25017538

AIM: To write a C program to print hollow rectangular pattern.

ALGORITHM:

1) Get the inputs row and columns from the user.
2) using for loop and if else statements, print the hollow rectangle.

PROGRAM:
```
#include<stdio.h>
int main()
{
    int row,col;
    scanf("%d",&row);
    scanf("%d",&col); 
    for(int i=1;i<=row;i++)
    {
        for(int j=1;j<=col;j++)
        {
            if(i==1||i==row||j==1||j==col)printf("*");
            else printf(" ");
        }printf("\n");
    }
}
```
OUTPUT:
<img width="331" height="192" alt="Screenshot 2025-10-19 222554" src="https://github.com/user-attachments/assets/3102b4b7-c50c-4fc0-a3fa-2a178f796d16" />

RESULT:
Thus the C program to print hollow rectangle is executed successfully.




