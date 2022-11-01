# algoritimo
Exame nota//

#include <stdio.h>
float n1,n2,media;

int main(){
	printf("digite a n1: ");
	scanf("%f",&n1);
	printf("digite a n2: ");
	scanf("%f",&n2);
if (n1>=0 && n1<=10 && n2>=0 && n2<=10)
{
	media=(n1+n2)/2;
	if(media>=7 && media<=10){
		printf("\nAluno aprovado com media: %.2f",media);
	}
	else if (media>=3 && media<7){
		printf ("\nExame com media: %.2f\n",media);
	}
	else if (media>=0 && media<3)
	{
	printf("\nAluno reprovado com media: %.2f\n",media);
	}
else {
	printf("\nNota invalida\n");
   }
}
return 0;
}

