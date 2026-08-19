#include <stdio.h>

// Escreva um algoritmo que ordene 5 valores inteiros de forma crescente ......... OK

int vetor[5]={5, 3, 1, 4, 2};

int main() {
    int qtd=5;
    int i, j;
    int trocas;
    int aux;
    int cont=0;
    
    printf("\n Vetor original: ");
    for (int i=0; i<qtd; i++)
        printf("%i, ", vetor[i]);
    cont=0;
    
    for(int i=1; i<qtd; i++){               // Estamos percorrendo o arranjo por fora
        aux = vetor[i];                     // Começamos guardando a posição atual
        j = i-1;                            // 
        while(j>=0 && aux<vetor[j]) {
            vetor[j+1] = vetor[j];
            j--;
            cont++;
        }
        vetor[j+1] = aux;
    }    
    printf("\n Vetor ordenado: ");
    for (int i=0; i<qtd; i++)
    printf("%i, ", vetor[i]);
    printf("\n Quantidade de trocas: %i", cont);
}
