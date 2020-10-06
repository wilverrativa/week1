#include <stdio.h>
#include <cs50.h>

int main(void){
    int altura;
    
    do{
    altura=get_int("ingrese la altura de la escalera\n");
    }while (altura<1||altura>8);

      for (int escalon1=1;escalon1<=altura;escalon1++){

            for(int escalon2=1;escalon2<=altura-escalon1;escalon2++)
            printf(" ");

            for(int escalon2=1;escalon2<=0+escalon1;escalon2++)
            printf("*");

            for(int escalon2=1;escalon2<=altura;escalon2++)
            printf(" ");


           printf("\n");

            }
}
