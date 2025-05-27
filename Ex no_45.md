# EX 45 C program to insert elements in queue using array.
## AIM:
To write a C program to insert elements in queue using array.

## Algorithm
1. Check if queue is full (rear == SIZE - 1); if yes, print "Queue Overflow" and exit.
2. If queue is empty (front == -1), set front = 0.
3. Increment rear by 1 and insert the element at queue[rear].
4. Ensure display prints "no elements to display" if front == -1 or front > rear.


## Program:
```
/*
C program to insert elements in queue using array.
Developed by: Mariam Sherin
RegisterNumber: 212222060143
float queue[50];
int front,rear,size=10;
void enqueue(float data)
{
    if(rear<size)
    {
        if(front==-1)
        {
            front=0;
        }
        rear++;
        queue[rear]=data;
    }
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/39658659-49f8-4fb8-abf1-4417068ba516)


## Result:
Thus the program was executed and the output was verified successfully.
