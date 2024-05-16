# att10.07

#include <stdio.h>
#include <stdlib.h>

int main(){
	float pesoPrato;
	
	printf("Digite seu peso: ");
	scanf("%f", &pesoPrato);
	
	float precoPrato = pesoPrato * 45;
	
	printf("O preço que devera ser pago por esse prato sera de : %f", precoPrato);
	
return 0;
}
