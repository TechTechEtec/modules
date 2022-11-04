# Operadores Aritméticos
Os operadores aritméticos definem as operações aritméticas que podem ser realizadas sobre os números inteiros e reais. Para os inteiros, as operações aritméticas são a adição, subtração, multiplicação e resto. Para os números reais, as operações aritméticas são a adição, subtração, multiplicação e divisão. os operadores aritméticos correspondentes às operações definidas sobre os inteiros são:

| Símbolo |  Definição | 
| :---------- | :--------------------------------------------------- | 
| +, - | Operadores unários, isto é, são aplicados a um único operando. São os operadores aritméticos de maior precedência. Exemplos: -3, +x. Enquanto o operador unário - inverte o sinal do seu operando, o operador + não altera o valor em nada o seu valor. O operador menos muda o sinal de seu argumento. Um número positivo torna-se negativo e um número negativo torna-se positivo.      |
| + | adição 0|
| - | subtração |
| * | multiplicação | 
| \ | Divisão Inteira |
| % | Resto |
| ^ | Potência |


Com os operadores acima, podemos escrever expressões aritméticas que envolvem constantes e variáveis inteiras. Por exemplo, suponha que a, b e c sejam variáveis do tipo inteiro. Então, temos que 

                                        a + b + c 

                                        a − b ∗ c % 2

                                      − 5 + 3 ∗ 8 \ 2

são todas expressões aritméticas válidas na linguagem Portugol.

## Regras de Precedência 
Qual é o valor da expressão aritmética 5 ∗ 3 % 2? Podemos dizer que o valor da expressão é igual a 1, se avaliarmos 5 ∗ 3 primeiro e, depois, 15 % 2, ou podemos dizer que é igual a 5 se avaliarmos 3 % 2 primeiro e, depois, 5 ∗ 1. As duas respostas são igualmente válidas. No entanto, como não podemos permitir ambiguidades em algoritmos, devemos definir regras de precedência de operadores, que são regras para definir a ordem em que os operadores aritméticos que vimos são aplicados em uma expressão aritmética qualquer. 

Na linguagem Portugol, os operadores possuem prioridades associadas com eles. A operação associada a um operador com prioridade p é sempre executada antes da operação associada a um operador com prioridade q sempre que p > q. Quando p = q, a operação correspondente ao operador mais à esquerda é executado.

O operador de maior prioridade é o menos unário, −. Em seguida, temos os operadores ∗, \ e %. Finalmente, com a prioridade mais baixa, temos os operadores + e −, onde + e − são os operadores de adição e subtração, respectivamente.

|  Operador  | Símbolo       | Prioridade                                  |
| :---------- | :--------- | :------------------------------------------ |
| Unários | +,- | Mais alta |
| Potência | ^ | Mais alta entre operadores binários, ou seja, que têm dois números sendo calculados |
| Multiplicação, Divisão Interna e Resto | *,\,% | Segunda mais alta |
| Adicção e Subtração | +,- | Mais baixa |

Por exemplo, em 
                                        
                                        a + b + c

A operação a + b é realizada e, em seguida, o resultado dela é adicionado ao valor de c, pois os operadores possuem a mesma prioridade e, portanto, as operações são realizadas da esquerda para a direita. 

Na expressão aritmética 
                                     
                                     a − b ∗ c % 2^3 

A operação2^3 é efetuada primeiro, b ∗ c em seguida, então vem o resto da divisão de b ∗ c pelo resultado de 2^3 é calculado. Finalmente, o resto é subtraído de a. Note que a multiplicação foi efetuada antes da divisão, pois os operadores ∗ e % possuem a mesma prioridade, mas ∗ está mais à esquerda.  

## Alteração de Prioridades
Algumas vezes é desejável alterar a ordem (imposta pelas regras de precedência) segundo a qual as operações são realizadas em uma expressão aritmética. Para tal, fazemos uso de parênteses. Por hipótese, todo operador possui prioridade mais baixa do que a dos parênteses. Isto garante que os operandos correspondentes ao valor das expressões entre parênteses sejam calculados antes de serem usados pelos demais operadores. É importante destacar que os parênteses devem ocorrer em pares (um aberto e um fechado) nas expressões e podem ocorrer “aninhados” em diversos níveis.

Por exemplo, na expressão 

                                    (a − b) ∗ (c % 2)

A operação a − b é realizada primeiro. Em seguida, a operação c % 2 é realizada e, por último, a multiplicação dos resultados das duas operações anteriores entre os parênteses é realizada, ao contrário do que aconteceria se não houvessem parênteses, pois a multiplicação, *, aconteceria primeiro por ordem de prioridade e posicionamento, sendo ela a primeira da esquerda para a direita.

Mas, como sabemos disso? A idéia é imaginar as expressões entre parênteses como operandos a serem “descobertos”. Com isso em mente, a expressão acima pode ser imaginada como tendo a forma op1 ∗ op2, onde op1 e op2 são as expressões (a − b) e (c % 2). Então, o que temos é uma simples multiplicação de dois valores, op1 e op2. No entanto, para que esta multiplicação seja realizada, precisamos dos valores op1 e op2. Para tal, assumimos que o valor, op1, à esquerda do operador de multiplicação, ∗, será obtido antes do valor, op2, à direita dele. 

Para calcular op1, avaliamos a expressão a − b, que se encontra dentro dos parênteses. Neste momento, descobrimos que a subtração a − b é a primeira operação aritmética realizada. Uma vez que o valor op1 tenha sido descoberto, avaliamos c % 2, que é a expressão correspondente ao valor op2. Neste momento, descobrimos que a operação de resto de divisão, c % 2, é a segunda operação aritmética realizada. 

Assim, dispomos dos valores op1 e op2 e, portanto, podemos realizar a multiplicação op1 ∗ op2 , que passa a ser a terceira operação realizada. Logo, os operadores são aplicados na ordem −, % e ∗.


# Operadores Relacionais:
Primeiro é necessário entender, basicamente por enquanto, o que são declarações condicionais. Como o nome já diz, uma declaração condicional apresenta uma condição, dá ao algoritmo a capacidade de tomar decisões, que faça uma coisa ou outra. 

Exemplo: 

Um algoritmo possui uma variável chamada idade, cujo valor é digitado pelo usuário. O algoritmo precisa imprimir duas mensagens distintas a depender do valor contido nessa variável.
- Dessa maneira, se o valor contido na variável idade for menor que 18, o algoritmo deverá exibir a mensagem “Você não pode acessar o sistema! É menor de idade!".
- Em contrapartida, caso o valor contido na variável idade seja maior ou igual a 18, o algoritmo deverá exibir a mensagem “Bem vindo ao sistema!".

No código, essas declarações são feitas, também, através dos operadores relacionais, são eles:

| Símbolo |  Definição | 
| :---------- | :--------- | 
| =   | Igual que |
| =/= | Diferente que |
| >   | Maior que |
| >=  | Maior ou igual que |
| <   | Menor que |
| <=  | Menor ou igual que |

As operações com operadores relacionais sempre retornam um valor FALSO ou VERDADEIRO.
Por exemplo:

                                O número 5 é maior que o número 6? FALSO
                                O número 5 é menor que o número 6? VERDADEIRO 


Para atestar essas informações na programação, usamos estes símbolos, de maneira que:
                                      
                                      a=b – a é IGUAL a b
                                      a>b – a é MAIOR que b
                                      a>=b - a é MAIOR OU IGUAL que b
                                      a<b – a é MENOR que b
                                      a<=b - a é MENOR OU IGUAL que b
                                      a=/=b - a é DIFERENTE de b


# Resumo do Módulo

### Operadores Aritméticos

Os operadores aritméticos definem as operações aritméticas que podem ser realizadas sobre os números inteiros e reais. Para os inteiros, as operações aritméticas são a adição (+), subtração (-), multiplicação (*) o e resto (%). Para os números reais, as operações aritméticas são a adição(+), subtração(-), multiplicação(*) e divisão(\).

Temos também os operadores unários (+,-), que são aplicados em um único número, Exemplos: -3, +x. Enquanto o operador unário - inverte o sinal do seu operando, o operador + não altera o valor em nada o seu valor. O operador menos muda o sinal de seu argumento. Um número positivo torna-se negativo e um número negativo torna-se positivo.

### Regras de Precedência
São as regras de ordem de resolução das operações, são importantes pois não pode haver ambiguidade nos resultados das operações, por isso temos essa ordem de prioridade padronizada.

A ordem de prioridade sempre será:

    1. Unários
    2. Potência
    3. Multiplicação, divisão inteira e resto
    4. Adição e subtração
    5. Multiplicação, divisão e resto estão no mesmo nível de prioridade, assim como adição e subtração, nesses casos, as primeiras operações que devem ser resolvidas são as que aparecem da esquerda para direita.

### Alteração de Prioridades
Pode ocorrer uma alteração nessas prioridades, ela ocorre através dos parênteses (), por hipótese, todo operador possui prioridade mais baixa do que a dos parênteses, isso garante que as expressões dentro dos parênteses sejam calculados antes de serem usados pelos demais operadores, ou seja, resolver o que está dentro deles independente da operação, antes de resolver tudo da maneira recorrente.

Por exemplo, na expressão:

(a − b) ∗ (c % 2)

A operação a − b é realizada primeiro. Em seguida, a operação c % 2 é realizada e, por último, a multiplicação dos resultados das duas operações anteriores entre os parênteses é realizada, ao contrário do que aconteceria se não houvessem parênteses, pois a multiplicação, *, aconteceria primeiro por ordem de prioridade e posicionamento, sendo ela a primeira da esquerda para a direita.

### Operadores Relacionais
Os operadores relacionais estão ligados com as declarações condicionais, eles ajudam a formular as condições apresentadas ao sistema, que retorna as respostas como VERDADEIRO ou FALSO.

São eles:

    =    Igual que 

    =/= Diferente que

    >    Maior que

    >=   Maior ou igual que

    <    Menor que

    <=   Menor ou igual que
