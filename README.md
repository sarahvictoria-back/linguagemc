# linguagem C
passo a passo linguagem C.
Esse repositorio terá informações sobre a linguagem de programação C, onde servirá de aprendizado.

## Primeiros passos

exemplo de código:
```
#include <stdio.h>

int main() {
    printf("Hello, World!");
    return 0;
}
```
#include <stdio.h>É um biblioteca de arquivos de cabeçalho que nos permite trabalhar com entrada e saída funções.

int vai ser o tipo de "algo", por exemplo, se a saída for algo inteiro, nós usamos o tipo int.

main() é uma função

printf() é  uma função usada para dar saída/impressão de texto na tela, ou seja, vai escrever uma mensagem na tela.

vale lembrar que cada instrução C termina com um ponto e vírgula ;

return 0 acaba com o main()

e não pode esquecer de adicionar o suporte de fecho } para realmente acabar com a função principal

## Nova linha
para inserir uma nova linha, pode ser usano o \n
### Exemplo
```
#include <stdio.h>

int main() {
printf("Hello, World!\n I am learning C");
return 0;
}
