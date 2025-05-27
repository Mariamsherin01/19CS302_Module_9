# EX 42 C program to write a fuctions to perform push,pop,display,peek in stack using array.
## AIM:
To write a fuctions to perform push,pop,display,peek in stack using array.

## Algorithm
1. Check if top == SIZE - 1:
   - If true, stack is full → print "Stack Overflow".
2. Else:
   - Increment top (top = top + 1).
   - Insert the value at stack[top].


## Program:
```
/*
C program to write a fuctions to perform push,pop,display,peek in stack using array.
Developed by:  Mariam Sherin
RegisterNumber: 212222060143
float stack[100];
int size=3,top=-1,i;
void push (float data)
{
  if(top==size-1)
  {
      printf("stack is full\n");
  }
  else
  {
      stack[++top]=data;
  }
}
void display()
{
    if(top==-1)
    {
        printf("stack is empty");
    }
    else
    {
        for(i=top;i>=0;i--)
        {
            printf("%.2f ",stack[i]);
        }
    }
}
void pop ()
{
    if(top==-1)
    {
        printf("stack is empty");
    }
    else
    {
        top--;
    }
}
void peek()
{
    printf("%.2f ",stack[top]);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/ae037200-5ea1-46f9-a61c-c20e3cd0dd95)


## Result:
Thus the program was executed and the output was verified successfully.
