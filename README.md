#include<stdio.h>
void main()
{
int is_prime;
long int i,n;
printf("enter any number");
scanf("%d",&n);
printf("%d\n",sizeof(n));
if(n<=1)
{
is_prime=0;
}
else
{
for(i=2;i<=n-1;i++)
{
if(n%i==0)
{
is_prime=0;
break;
}
}
}
if(is_prime)
    printf("prime=%d",n);
    else
    printf("not prime=%d",n);
}
