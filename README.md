# food
Developed by deepanshi
#include <stdio.h>
int main()
{
int b,f,p,s,Burger,FrenchFries,Pizza,Sandwiches;
char ch,B,F,P,S;
printf("\n 1=Burger\n 2=FrenchFries\n 3=pizza\n 4=Sandwiches\n");
printf("Enter your order .please Enter the choice 1,2,3,4\n");
scanf("%d",&ch);
switch(ch)

{
case 1:
printf("your order is Burger\n");
printf("please enter your quantity ");
scanf("%d",&b);
Burger=200*b;
printf("your total charges is: %d",Burger);
break;
case 2:
printf("your order is FrenchFries\n");
printf("please enter your quantity ");
scanf("%d",&f);
FrenchFries=50*f;
printf("your total charges is: %d",FrenchFries);
break;
case 3:
printf("your order is Pizza\n");
printf("please enter your quantity ");
scanf("%d",&p);
Pizza=500*p;
printf("your total charges is: %d",Pizza);
break;
case 4:
printf("your order is Sandwiches\n");
printf("please enter your quantity ");
scanf("%d",&s);
Sandwiches=150*s;
printf("your total charges is: %d",Sandwiches);
break;
default:
printf("invalid your choice");
break;
}
}
