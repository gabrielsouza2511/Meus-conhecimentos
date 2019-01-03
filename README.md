# Meus-conhecimentos
Um pouco do que aprendi na faculdade
#include <stdio.h>
#include<conio.h>
#include<string.h>

void main(){
   // char nome;
    int idade, valor;

    //printf("ENTRE COM o nome\t");
    //scanf("%c", &nome);
    printf("ENTRE COM A idade\t");
    scanf("%d", &idade);
    
    if (idade <= 10){
        valor = 30;
    }
    else{
        if (idade <= 29){
            valor = 60;
        }
        else{
            if (idade <= 45){
                valor = 150;
            }
            else{
                    if (idade <= 65){
                        valor = 250;
                    }
                    else{
                        valor = 400;
                    }
            }
        }
    }
    //printf("Nome: %c ", nome);
    printf(" Idade: %d", idade);
    printf(" Pagara: %d", valor);
}
