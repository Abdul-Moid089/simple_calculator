# simple_calculator
Here, I have created a simple calculator using C programming language.
#include<stdio.h>
int main(){
	int a,b,sum,min,div,mul;
	char ch;

	printf("Enter two numbers for the calculations:");
	scanf("%d %d",&a,&b);
	printf("Choose your operator for the calculation:");
	fflush(stdin);
	scanf("%c",&ch);

	
	switch(ch){
		case '+':
		 sum=a+b;
			printf("The sum of %d and %d = %d",a,b,sum);	
			break;
			case '-':
				 min=a-b;
				printf("The subtraction of %d and %d = %d",a,b,min);
				break;
				case '*':
					 mul=a*b;
					printf("The multiplication of %d and %d = %d",a,b,mul);
					break;
					case '/':
					 div=a/b;
					printf("The division of %d and %d = %d",a,b,div);
					
		
					
	}
}
