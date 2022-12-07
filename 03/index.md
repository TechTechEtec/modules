## Bem-vindos ao Módulo 3!

## Operadores Aritméticos
Os operadores aritméticos definem as operações aritméticas que podem ser realizadas sobre os números inteiros e reais. Para os inteiros, as operações aritméticas são a adição, subtração, multiplicação e resto. Para os números reais, as operações aritméticas são a adição, subtração, multiplicação e divisão. os operadores aritméticos correspondentes às operações definidas sobre os inteiros são:

![Operadores Aritméticos](https://drive.google.com/uc?id=1lVtO0aILYaWokbmnZUS18cYNX-tWjJnN)


Com os operadores acima podemos escrever expressões aritméticas com números inteiros. Por exemplo, suponha que x, y e z sejam variáveis do tipo inteiro. Então:

                                        x + y + z  

                                        x − y ∗ z % 2

                                      − 5 + 3 ∗ 8 \ 2

São todas expressões válidas em Portugol.

### Regras de Precedência 
Qual é o valor da expressão aritmética 5 ∗ 3 % 2? Podemos dizer que o valor da expressão é igual a 1, se fizermos na ordem:
                                        5 ∗ 3 
                                        15 % 2 
 
 ou podemos dizer que é igual a 5 se fizermos:

                                        3 % 2 
                                        5 ∗ 1. 

As duas respostas são igualmente válidas, mas não pode haver ambiguidades em algoritmos, por isso definimos regras de precedência para os operadores, que são regras que definem a ordem em que os operadores aritméticos são aplicados em uma expressão aritmética qualquer.

Na linguagem Portugol, os operadores possuem prioridades associadas com eles. A operação associada a um operador com prioridade p é sempre executada antes da operação associada a um operador com prioridade q sempre que p > q. Quando p = q, a operação correspondente ao operador mais à esquerda é executado.

Confira a ordem de precedência: 


![Regras de precedência](https://drive.google.com/uc?id=1vaMq3kvJleeX3D8OUFUTdLwhpmXYfMyS)

Por exemplo, em 
                                        
                                        x + y + z

A operação x + y é feita e depois o resultado dela é adicionado ao valor de z, pois os operadores tem a mesma prioridade e nesse caso as operações são realizadas da esquerda para a direita. 

Na expressão aritmética 
                                     
                                     x − y ∗ z % 2^3  

A operação 2^3 é efetuada primeiro, y ∗ z em seguida, então o resto (%) da divisão de y ∗ z pelo resultado de 2^3 é calculado. Finalmente, o resto é subtraído de x.

A multiplicação foi efetuada antes da divisão, pois os operadores ∗ e % possuem a mesma prioridade, mas ∗ está mais à esquerda.  
  

### Alteração de Prioridades
Às vezes é necessário alterar a ordem em que as operações são realizadas em expressões aritméticas (impostas por regras de precedência). Para isso, usamos parênteses. Por suposição, todo operador tem precedência menor que parênteses. Isso garante que as expressões entre parênteses sejam feitas antes de serem utilizados por outros operadores. É importante observar que os parênteses devem aparecer em pares (um aberto e outro fechado) na expressão e podem aparecer "aninhados" em diferentes níveis.

Por exemplo, na expressão 

                                    (x − y) ∗ (z % 2)

Primeiro execute a operação x − y. Em seguida, é realizada a operação z % 2 e, por fim, é realizada a multiplicação dos resultados das duas operações anteriores entre parênteses, que é o oposto do caso sem parênteses, pois a multiplicação * acontecerá primeiro em prioridade e colocação ordem, primeiro da esquerda para a direita individual.

Então, o que temos é uma simples multiplicação de duas operações que vamos chamar de op1 e op2, valores a serem descobertos. Para tal, assumimos que o valor, op1, à esquerda do operador de multiplicação, ∗, será obtido antes do valor, op2, à direita dele. 

Para calcular op1, fazemos a expressão x − y, que se encontra dentro dos parênteses, descobrindo que a subtração a − b é a primeira operação aritmética realizada. Com o valor de op1 descoberto, fazemos c % 2, a op2. Neste momento, descobrimos que a operação de resto de divisão, c % 2, é a segunda operação aritmética realizada. 

Assim, temos os valores op1 e op2 e podemos realizar a multiplicação op1 ∗ op2, que é a terceira operação a ser realizada. Os operadores então são aplicados na ordem −, % e ∗.


## Operadores Relacionais:
Primeiro é necessário entender, basicamente por enquanto, o que são declarações condicionais. Como o nome já diz, uma declaração condicional apresenta uma condição, dá ao algoritmo a capacidade de tomar decisões, que faça uma coisa ou outra. 

Exemplo:

Um algoritmo tem uma variável chamada "idade", cujo valor é digitado pelo usuário. O algoritmo precisa mostrar duas mensagens distintas a depender do valor contido nessa variável.
- Dessa maneira, se o valor da variável "idade" for menor que 18, o algoritmo deve mostrar a mensagem “Você não pode acessar o sistema! É menor de idade!".
-Em contrapartida, caso o valor contido na variável idade seja maior ou igual a 18, o algoritmo deverá exibir a mensagem “Bem vindo ao sistema!".

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

                                O número 7 é maior que o número 9? FALSO
                                O número 4 é menor que o número 6? VERDADEIRO 


Para atestar essas informações na programação, usamos estes símbolos, de maneira que:
                                      
                                     - a=b – a é IGUAL a b
                                     - a>b – a é MAIOR que b
                                     - a>=b - a é MAIOR OU IGUAL que b
                                     - a<b – a é MENOR que b
                                     - a<=b - a é MENOR OU IGUAL que b
                                     - a=/=b - a é DIFERENTE de b


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

   - =    Igual que 

   - =/= Diferente que

   - >    Maior que

   - >=   Maior ou igual que

   - <    Menor que

   - <=   Menor ou igual que
