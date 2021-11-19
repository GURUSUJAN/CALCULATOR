#include<stdio.h>
int main()
{
    int a,b;
    char ch;
    printf("enter 2 numbers ");
    scanf("%d%d",&a,&b);
    printf("+\n");
    printf("-\n");
    printf("*\n");
    printf("/\n");
    printf("%\n");
    scanf(" %c",&ch);
    
switch(ch)
{
    case '+':
    printf("%d",a+b);
    break;
    case '-':
    printf("%d-%d=%d",a,b,a-b);
    break;
    default:
    printf("select properly;see your mistake ");
    break;
     case '*':
    printf("%d*%d=%d",a,b,a*b);
    break;
    case '/':
    printf("%d/%d=%d",a,b,a/b);
    break;
     case '%':
    printf("%d%d=%d",a,b,a%b);
    break;
   
}
}

