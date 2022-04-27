#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>
#include <conio.h>
#include <stdbool.h>

------- MAIN ------

int main(){
	
	int i=0;
	char estado[]="";
	bool ciclo1 = true;
	printf("Ingrese el estado del restaurante: "); scanf("%s", &estado);
	printf("%s", estado);
	
	while(ciclo1){
		printf("\nHola desea seguir?: ");
		scanf("%i", &i);
		if(i==1){
			ciclo1 = true;
		}
		
		else{
			ciclo1 = false;
		}
	}
	
	getch();
	return 0;
}
