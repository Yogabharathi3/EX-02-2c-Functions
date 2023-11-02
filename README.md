# EX-02-2c-Functions
## AIM:
Write a C program to perform addition and subtraction of two numbers using functions (with argument and without return type).
## ALGORITHM:
1. Declare two functions, one for addition and one for subtraction. Both functions should take two integer arguments.
2. Inside the addition & subtraction function, add & subtract the two numbers and print the result.
3. In the main function, declare two integer variables and read their values from the user.
4. Call the addition and subtraction functions, passing the two numbers as arguments.
## PROGRAM:
```
#include<stdio.h>
void cal()
{
   int a,b,add,sub;
   scanf("%d%d",&a,&b);
   add=a+b;
   sub=a-b;
   printf("Addition: %d",add);
   printf("\nSubtraction: %d",sub);
}
int main()
{
   cal();
   return 0;
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/EX-02-2c-Functions/assets/118899387/178d3720-673a-4d70-8b14-356ee11ff06c)

## RESULT:
Thus the program to perform addition and subtraction of two numbers using functions has been executed successfully
