# Grade
#include<stdio.h>
#include<conio.h>
void main()
{
int s;
printf("Enter the marks\n");
scanf("%d",&s);
if(s>=85 && s<=100)
printf("Grade A\n");
else if(s>=70 && s<=84)
printf("Grade B\n");
else if(s>=55 && s<=69)
printf("Grade C\n");
else if(s>=40 && s<=54)
printf("Grade D\n");
else
printf("Grade F\n");
getch();
}
