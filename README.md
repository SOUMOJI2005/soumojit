#include<math.h>
int main()
{ 
int count=0,num,sum=0,r,temp;
printf("Enter a num:");
scanf("%d",&num);
temp=num;
while(num!=0)
{
	num=num/10;
	count++;
}
num=temp;
while(num!=0)
{
	r=num%10;
	sum=sum+pow(r,count);
	num=num/10;
}
if(sum=temp)
{

printf("%d is a amstrong num",temp);
}
else
{

printf("%d is  not a amstrong num",temp);
}
return 0;
}
