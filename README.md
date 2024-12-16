# recursive_factorial_function
Code to find the factorial of a number with a recursive function.


#include <stdlib.h>
#include <stdio.h>

int factorial(int number)
{
	if(number == 0)
	{ 
		return 1;
	}
	else
	{
		return number*factorial(number-1);
	}
}

int main()
{
	int number;
	printf("enter a number:");
	scanf("%d",&number);
	printf("factorial of a number: %d",factorial(number));
	
	return 0;
}
