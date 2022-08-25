# Linguagem-c-positivo/negativo?

#include <stdio.h>
#include <stdlib.h>
#include <locale.h>
#include <windows.h>

int main(){
    setlocale(LC_ALL, "portuguese-brazilian");
    UINT CPAGE_UTF8 = 65001;
    int num;

    printf("Insira um número inteiro:\n");
    scanf("%d", &num);

    if(num >0){
        
        printf("O número %d é positivo", num);
    }
    else if(num <0){
        
        printf("O número %d é negativo", num);
    }
    else if(num == 0){

        printf("O número %d não e positivo é nem negativo", num);
    }    
    return 0;
}
