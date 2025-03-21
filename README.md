# hello-world9
futebol, churras e samba
este é o trabalho 
//teste 1 
#include <stdio.h>
#include <string.h>

int main() {
    char input[100];

    // Solicita a entrada do usuário
    printf("Digite 'hello world': ");
    fgets(input, sizeof(input), stdin);

    // Remove o caractere de nova linha, se houver
    input[strcspn(input, "\n")] = 0;

    // Verifica se a entrada é igual a "hello world"
    if (s
