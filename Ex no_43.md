# EX 43 C program to Write a function to display queue elements using array.
## AIM:
To Write a function to display queue elements using array.

## Algorithm
1. Check if queue is empty (front == -1 or front > rear); if yes, print "Queue is empty" and stop.
2. Start from front index.
3. Loop through queue elements till rear index.
4. Print each element during the loop.


## Program:
```
/*
C program to write a function to display queue elements using array.
Developed by:  Mariam Sherin
RegisterNumber: 212222060143
char queue[50];
int rear=-1, front=-1;
void display()
{
    int i;
    if(front == -1 || front >rear)
    {
        printf("No elements to display");
    }
    else
    {
        for(i=front;i<=rear;i++)
        {
            printf("%c\n",queue[i]);
 }
}
}  
*/
```

## Output:

![image](https://github.com/user-attachments/assets/44bb7ad1-57a1-45c1-89cc-b63f1d600d81)


## Result:
Thus the program was executed and the output was verified successfully.
