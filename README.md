# História do Java
Java é uma linguagem de programação orientada a objetos que começou a ser desenvolvida na Sun Microsystems em 1991. O projeto inicial, conhecido como Green Project, foi liderado por Patrick Naughton, Mike Sheridan e James Gosling. A ideia original não era criar uma nova linguagem de programação, mas sim facilitar a interconexão entre computadores e eletrodomésticos dentro de uma residência.

Naquela época, para desenvolver um programa de computador, era necessário escrever o código em uma linguagem específica e, em seguida, compilar esse código para criar um executável para cada sistema operacional ou arquitetura existente. Com isso em mente, o grupo decidiu criar uma linguagem que fosse independente de plataforma. Esta linguagem, inicialmente baseada em C++, foi chamada de GreenTalk. Posteriormente, foi renomeada para Oak, mas devido a problemas de direitos autorais com esse nome, foi renomeada novamente, dessa vez para Java. A linguagem foi então adaptada para suportar também o desenvolvimento de aplicações para a internet.

# O que é if else

- Use if para especificar um bloco de código a ser executado, se uma condição especificada for verdadeira
- Use else para especificar um bloco de código a ser executado, se a mesma condição for falsa
- Use else if para especificar uma nova condição a ser testada, se a primeira condição for falsa

- As condições dentro de um if deve sempre resultar em um valor booleano.
- As chaves {} são obrigatórias se você tiver mais de uma declaração dentro de um bloco;
- para uma única declaração, elas são opcionais, mas recomendadas para melhor legibilidade.
- Utilizando if, else if, e else de maneira apropriada, você pode controlar complexamente o fluxo de decisão

## Observações
- importante ressaltar O uso de else if em Java e em outras linguagens de programação é comum para o controle de fluxo baseado em múltiplas condições.
No entanto, a utilização excessiva ou inadequada de else if pode levar a problemas de desempenho e legibilidade, especialmente em casos com muitas condições.
```
int numero = 15;

if (numero > 20) {
    System.out.println("O número é maior que 20");
} else if (numero > 10) {
    System.out.println("O número é maior que 10 mas não maior que 20");
} else {
    System.out.println("O número é 10 ou menor");
}
```
