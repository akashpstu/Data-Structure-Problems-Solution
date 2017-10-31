## Welcome to Data Structures Problem Solutions Github Pages

### In this page/reposatory, you can find codes for Data Structure related problems in Computer Science.

#### Linked List - 
A complete code of Linked List with all the functions
1. Create Linked List
2. Read Linked List Data
3. Search Linked List Data
4. Delete Linked List Data

Demo Code - 

```c

#include<stdio.h>
#include<stdlib.h>
typedef struct Node
{
        int data;
        struct Node *next;
}node;


void insert(node *pointer, int data)
{

        while(pointer->next!=NULL)
        {
                pointer = pointer -> next;
        }

        pointer->next = (node *)malloc(sizeof(node));
        pointer = pointer->next;
        pointer->data = data;
        pointer->next = NULL;
}

```

#### Link - <a href="https://github.com/akashpstu/Data-Structure-Problems-Solution/blob/master/LinkedListFull.c" class="btn">Linked List Complete Code </a>



### Support or Contact

Having trouble with Pages? Just Send me a mail  <a href="mailto:manirujjamanakash@gmail.com">manirujjamanakash@gmail.com</a>. I'm here to help some lovely coder.
