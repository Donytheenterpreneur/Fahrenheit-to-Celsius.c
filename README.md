#include<stdio.h>
int main()
{
	float C,F;
	printf("enter the temperature in farenhiet: ");
	scanf("%f",&F);
	C=(F*5/9)-32;
	printf("temperature in celcius= %.2f",C);
	return 0;
	
}
