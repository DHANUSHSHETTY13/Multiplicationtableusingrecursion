#include<stdio.h>
int main()
{
int n,m;
printf("enter the table =");
scanf("%d",&n);
printf("enter the upto =");
scanf("%d",&m);
fun(n,m);

}
void fun(n,m)
{
int i;
for(i=1;i<=m;i++)
{
printf("%d*%d=%d\n",n,i,i*n);
}
}
