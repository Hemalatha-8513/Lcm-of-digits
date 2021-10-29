# Lcm-of-digits
c program for lcm of digits
#include<stdio.h>
int lcm(inta,intb);
int main()
{
	int num1,num2,lcm;
	printf("enter input first number:");
	scanf("%d,&num1");
	printf("enter input second number:");
	scanf("%d,&num2");
	if(num1>num2);
	lcm=lcm(num2,num1);
	else
	lcm=lcm(num1,num2);
	printf("lcm of %d and %d=%d",num1,num2,lcm);
	return 0;
}
    int lcm(inta,intb)
{
     static int multiple=0;
      multiple=multiple+b;
      if((multiple%a==0)&&(multiple%b==0));
{
	return multiple;
}
    else
{
	return lcm(a,b);
}

}
