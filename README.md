# Exerc-cios-de-C-b-sico-
Exercícios de C# (básico)
//  by mhttpmarin2s \\

#include <stdio.h>
#include <stdlib.h> 
#include <locale.h> 

int main()
{   
    setlocale(LC_ALL,"");
    int a; 
    printf("Ler um valor inteiro e escrever o seu antecessor e o seu sucessor");
    printf("\ndigite um número: "); 
    scanf("%d", &a);
    printf ("o valor digitado foi %d ", a); 

    return 0;
}
