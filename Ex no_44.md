# EX 44 C functions to perform enqueue, dequeue, display, peek in Queue using Array.
## AIM:
To write a C Write a functions to perform enqueue, dequeue, display, peek in Queue using Array.

## Algorithm
 1. Enqueue: If queue is full, print "Queue Overflow"; else increment rear and add element. If front == -1, set front = 0.
2. Dequeue: If queue is empty (front == -1 or front > rear), print "Queue Underflow"; else increment front to remove element.
3. Display: If queue is empty, print "Queue is empty"; else print elements from front to rear.
4. Peek: If queue is empty, print "Queue is empty"; else print element at front.


## Program:
```
/*
C functions to perform enqueue, dequeue, display, peek in Queue using Array.
Developed by:  Mariam Sherin
RegisterNumber: 212222060143
int front,rear,i,size=10;
float queue[50];
void enqueue(float data)
{
    if(rear<size-1)
    {
        if(front==-1)
        {
            front=0;
        }
        queue[++rear]=data;
    }
}
void display()
{
    if(front==-1 || front>rear)
    {
        printf("No elements to display\n");
    }
    else
    {
        for(i=front;i<=rear;i++)
        {
            printf("%.1f\n",queue[i]);
        }
    }
}

void dequeue()
{
    if(front==-1 || front>rear)
    {
        printf("Queue Underflow\n");
    }
    else
    {
        front++;
    }
}

void peek()
{
    printf("%.1f\n",queue[front]);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/4b48f76e-48fa-4b56-bb30-b0da5a14f722)


## Result:
Thus the program was executed and the output was verified successfully.
