/******************************************************************************

Cilene - 16/02/23 - Calculadora em C

*******************************************************************************/
#include <stdio.h>
int soma (int a, int b)
{
    return a+b;
}
int subtracao (int a, int b)
{
    return a-b;
}
int prod (int a, int b)
{
    return a*b;
}
int resto (int a, int b)
{
    return a%b;
}
int divisao (int a, int b)
{
    if (b==0) return 0;
    return a / b;
}
int main()
{
    int a=46, b=72, soma, prod, divisao, subtracao, resto;
    
    // Processamento
    soma = a + b;
    subtracao = a - b;
    prod = a*b;
    divisao = a / b;
    resto = b % a;
    
    // Saída
    printf("Soma    = %d", soma);    
    printf("\nSubtracao = %d", subtracao);
    printf("\nDivisao   = %d", divisao);    
    printf("\nProduto   = %d", prod);
    printf("\nResto     = %d", resto);
//  printf ("\nsoma=%d Prod=%d", prod,soma);
    return 0;
}


