# Factorial-of-a-number
#include<stdio.h>
int main()
{
int i=1,n,fact=1;
printf("Integer: ");
scanf("%d",&n);
while(i<=n)
{ fact=fact*i; i++; }
printf("Factorial: %d\n",fact);
}
