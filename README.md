# Am-Gm
#include<stdio.h>
void main()
{
float a;
printf("enter the value of first number :-");
scanf("%f",&a);

float b;
printf("enter the value of second number :-");
scanf("%f",&b);

float AM=(a+b)/2;
printf("The arithmetic mean of the numbers is =%f\n",AM);

float HM=a*b/(a+b);
printf("The harmonic mean of the numbers is =%f",HM);

}
