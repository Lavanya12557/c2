# c2
//fibonaucci series
#include<stdio.h>
main()
{
	int a,f1,f2,f3;
	printf("enter the value of a:");
	scanf("%d",&a);
	f1=0;
	f2=1;
	f3=f1+f2;
	printf("%d\t%d\t%d\t",f1,f2,f3);
	while(f3<=a)
	{
	f1=f2;
	f2=f3;
	f3=f1+f2;
    printf("%d\t",f3);
}
}
