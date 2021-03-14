In this tutorial, we are going to discuss what are [structure in c programming](https://usemynotes.com/what-are-structures-in-c-programming/), how to create structure variables, and how to accessing structure members. So, let’s start with this wonderful concept.

## Introduction to Structure in C Programming
C also provides user-defined data types, like predefined data types (int, char, float, etc.). One such user-defined data type structure is. Structures are user-defined data types.

## Defining a Structure
The structure is defined using the struct keyword, after this keyword is defined, a unique name of the structure is assigned. The curly braces ({) are then used to create the variables and terminate the program by placing a semicolon (;) after the ending curly bracket (}).

```
struct struct_Name
{
  structure member 1;
  structure member 2;
  ..................
  structure member N;
};
```
## Creating Structure Variables
These variables can be created with 2 methods.
- With structure definition
- Without structure definition

### With Structure Definition
When we create variables with the Structure Definition type along with the structure definition, the variables are written by separating them with a comma (,) before the semicolon (;) of the end.
Like:-
```
struct shoes
{
  int price;
}t1,t2;
```
### Without Structure Definition
When we create variables without structure definition, then we use struct keyword. After using the struct keyword, the name of the structure is defined. You can define unlimited variables by separating from and then before the comma (,).
Like:-
```
struct shoes t1, t2, t3;
```
## Accessing Structure Members
We access Structure members for two reasons.
- To assign values ​​to members
- To print the values ​​of the members as output
Whenever we have to access a structure member, we do it using the dot operator.
Example -
``` 
#include<stdio.h>
/* Defining shoes structure */
struct shoes
{
  int price;
};
int main()
{
  /* Declaring variables of shoes structure */
  struct shoes t1;
  /* Assigning value to price of shoes */
  t1.price=999;
  printf(“The Price of the shoes is: %d”,t1.price);
return 0;
}
```

**Output**

```
The price of the shoes is: 999
```

Originally posted on - [Structure in C](Programminghttps://alimammiya.hashnode.dev/structure-in-c-programming)
