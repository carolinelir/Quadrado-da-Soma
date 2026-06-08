#include<stdio.h>

int main()
{
	float A,B,C,resultado;
	
	printf("Digite A: ");
	scanf("%f",&A);
	
	printf("Digite B: ");
	scanf("%f",&B);
	
	printf("Digite C: ");
	scanf("%f", &C);
	
	resultado =(A+B+C)*(A+B+C);
	
	printf("Quadrado da Soma: %.2f\n",resultado);
}
