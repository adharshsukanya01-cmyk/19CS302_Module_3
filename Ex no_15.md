
# EX 15 C program to replace all odd elements by 'O' in one dimensional array
## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1. Start. 
2. Declare a array size value of type int. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Initialize array elements. 
6. Replace all even elements to E 
7. End. 
## Program:
```
#include<stdio.h>
int main()
{
    int i,n;
    scanf("%d",&n);
    int a[10];
    char re[n];
    for(i=0; i<n; i++)
    scanf("%d",&a[i]);
    for(i=0; i<n; i++)
    {
        if(a[i]%2!=0)
        {
        re[i] = 'O';
        }
        else 
        {
         re[i] = a[i];
        }
    }
        for(i=0; i<n; i++)
        {
            if(re[i] == 'O')
            {
            printf("O ");
            }
            else
            {
            printf("%d ",a[i]);
            }
        }
    return 0;
}
```

## Output:
<img width="1127" height="187" alt="Screenshot 2026-06-08 141244" src="https://github.com/user-attachments/assets/cb0b5969-c513-4e57-91b8-363ea02de775" />



## Result:
Thus the program was executed and the output was verified successfully.
