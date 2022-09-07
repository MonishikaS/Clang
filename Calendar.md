```c
#include <stdio.h>
int main()
{
    char Operator;
    int num1,num2,result;
    printf("Enter any one operator like +, -, *, / : ");
    scanf("%c", &Operator);
    printf("Enter Operand num1 : ");
    scanf("%d", &num1);
    printf("Enter Operand num2 : ");
    scanf("%d", &num2);
    switch(Operator){
        case '+': result = num1 + num2;
           break;
        case '-': result = num1 - num2;
           break;
        case '*': result = num1 * num2;
           break;
        case '/': result = num1 / num2;
           break;
        default: printf("\n Invalid Operator ");
   }
   printf("The value = %d",result);
   return 0;
}

##OUTPUT
Enter any one operator like +, -, *, / : *
Enter Operand num1 : 2
Enter Operand num2 : 3
The value = 6
```
