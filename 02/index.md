
## O que são Dados?

Dados são uma coleção de fatos, como números, palavras, medidas, observações ou apenas descrições de coisas.

Esses dados vêm em diferentes formas. Exemplos incluem:

- Seu nome – uma sequência de caracteres
- Sua idade – geralmente um número inteiro
- A quantidade de dinheiro no bolso – geralmente um valor medido em dólares e centavos (algo com uma parte fracionária)

Vale também lembrar que dados são construções humanas. Usamos dados para lidar com uma realidade que é complexa. Ou seja, eles não são representações objetivas ou infalíveis desta realidade. Pelo contrário, os dados podem estar sujeitos a diversos tipos de erros ou vieses, desde a coleta, passando pelo seu tratamento, análise e até a visualização dos dados em gráficos ou mapas. Em todas estas etapas, é possível que erros afetem a forma como uma realidade complexa é representada por meio de dados. 

Como você pode perceber, estamos rodeados por dados. Vamos ver um outro exemplo:

![bolas de golfe]({{BASE}}/imgs/bolasdegolfe.png)

O que você pode dizer sobre essas bolas? Elas são bolas de golfe, correto? Logo, um dos primeiros dados que temos é que elas são usadas para o golfe, um tipo de esporte. Isso já nos ajuda a classificá-las em um grupo, mas há mais coisas. Vejamos:  
- A cor delas: branca;
- A condição delas: usada; 
- Todas têm um tamanho; 
- Há um número determinado delas; 
- Provavelmente, elas têm um valor monetário.

Mesmo os objetos ou situações mais comuns carregam consigo um monte de dados em potencial. Um outro exemplo é você mesmo: você tem um nome, um sobrenome, uma data de nascimento, peso, altura, nacionalidade e etc. Tudo isso são dados. 

Na computação, dados são  informações  que foram traduzidas em uma forma eficiente para movimentação ou processamento. Em relação aos computadores e meios de transmissão atuais, os dados são informações convertidas em  formato digital binário. 

Binário descreve um esquema de numeração no qual existem apenas dois valores possíveis para cada dígito - 0 ou 1 - e é a base para todo código binário usado em sistemas de computação. Esses sistemas usam esse código para entender as instruções operacionais e a entrada do usuário e apresentar uma saída relevante ao usuário.

O código binário é um tipo de codificação que usa 0 e 1 para representar letras, números e símbolos. É chamado de código binário porque é feito de apenas dois símbolos. O “bi” em binário significa dois!

O hardware dos computadores tem apenas dois estados elétricos, ligado ou desligado. Estes podem ser representados por zero (desligado) ou um (ligado). Letras, números e símbolos são convertidos em números binários de oito caracteres à medida que você trabalha com eles por meio do software em seu computador.

Quer saber como dizer olá em código binário? Se parece com isso…

Olá: 01001000 01100101 01101100 01101100 01101111

O termo binário também se refere a qualquer sistema de codificação/decodificação digital no qual existem exatamente dois estados possíveis. Na memória digital de dados , armazenamento , processamento e comunicações, os valores 0 e 1 são às vezes chamados de baixo e alto , respectivamente. Nos transistores , 1 refere-se a um fluxo de eletricidade, enquanto 0 representa nenhum fluxo de eletricidade.

## Como os dados são armazenados

Computadores representam dados, incluindo vídeo, imagens, sons e texto, como valores binários usando padrões de apenas dois números: 1 e 0. Um bit é a menor unidade de dados e representa apenas um único valor. Um byte tem oito dígitos binários. O armazenamento e a memória são medidos em megabytes e gigabytes .
As unidades de medida de dados continuam a crescer à medida que a quantidade de dados coletados e armazenados cresce.

## Tipos de Dados

### Caractere
Um caractere, ou char, é um símbolo (uma letra do alfabeto, um dígito, um símbolo de pontuação, etc). Um char é armazenado em 1 byte de memória.

Consiste de um único símbolo ou de uma concatenação de símbolos do alfabeto usado pela linguagem Portugol. Este alfabeto inclui todas as letras do alfabeto romano, todos os dígitos, 0, 1, . . . , 9 e os caracteres de pontuação, tais como ?, ., . . ., entre muitos outros símbolos. Os elementos do conjunto de valores do tipo caractere devem ser escritos, nos algoritmos, entre aspas duplas, como, por exemplo, "a”, "Esta e uma frase formada por caracteres”. Há um elemento especial, “”, que é denominado de palavra vazia, pois não possui nenhum símbolo.

### Cadeia
Uma cadeia de caracteres (string em inglês) é constituído por uma sequência de caracteres contendo letras, dígitos e/ou símbolos especiais. 
Este tipo de dados é também muitas vezes chamado de alfanumérico, cadeia (ou cordão) de caracteres, ainda, do inglês, STRING. 
Usualmente, os dados literais são representados nos algoritmos pela coleção de caracteres, delimitada em seu início e término com o caractere aspas ("). 
Diz-se que os dados do tipo possuem um comprimento dado pelo número de caracteres nele contido.

Exemplos:

- "QUAL ?” - cadeia de comprimento 6  
- " ” - cadeia de comprimento 1 
- "qUaL ?!$" - cadeia de comprimento 8 
- " AbCdefGHi" - cadeia de comprimento 9 
- "1-2+3=" - cadeia de comprimento 6 
- “0” - cadeia de comprimento 1 

Note que, por exemplo, "1.2" representa um dado do tipo cadeia de comprimento 3, constituído pelos caracteres "1", "." e "2", diferindo de 1.2 que é um dado do tipo REAL.

### Inteiro
Os números inteiros são aqueles que não possuem componentes decimais ou fracionários, podendo ser positivos ou negativos.

Ex.: 
- 24 - número inteiro positivo 
- 0 - número inteiro 
- -12 - número inteiro negativo

### Real
Os dados de tipo REAL são aqueles que podem possuir componentes decimais ou fracionários, e podem também ser positivos ou negativos.

Exemplos de dados do tipo real:
- 24.01 - número real positivo com duas casas decimais 
- 144 - número real positivo com zero casas decimais 
- 13.3 - número real negativo com uma casa decimal 
- 0.0 - número real com uma casa decimal 
- 0. - número real com zero casas decimais 

### Lógico
A existência deste tipo de dado é, de certo modo, um reflexo da maneira como os computadores funcionam. Muitas vezes, estes tipos de dados são chamados de booleanos, devido à significativa contribuição de BOOLE à área da lógica matemática.

O tipo de dados LÓGICO é usado para representar dois únicos valores lógicos possíveis: VERDADEIRO e FALSO. Quando uma condição é verdadeira, vai ser retornado True. Caso contrário, é retornado False.

É comum encontrar em outras referências outros tipos de pares de valores lógicos como SIM e NÃO, 1 e 0, TRUE e FALSE. 

Um booleano é, então, um tipo de dados simples que indica ao computador a veracidade de uma condição ou de uma proposição.

### Vazio
Caracteres vazios são definidos como brancos (espaços), por exemplo: “”, não possui nenhum símbolo, portanto é vazio.

# Entrada e Saída de Dados
A entrada de dados, na programação, é basicamente tudo aquilo que entra de fora pra dentro, ou seja, informações que vem do meio externo para o programa. Por exemplo, quando você digita uma tecla no teclado ou passa o mouse em algum elemento qualquer na tela, você está enviando dados do meio externo para o computador, e esses dados são passados para o programa. Por isso, está ocorrendo uma entrada de dados.

Já a saída de dados é o que vai do programa para fora. Uma impressão de um arquivo é uma saída de dados. A exibição de um texto ou uma imagem na tela é saída de dados. Até mesmo a escrita de um arquivo é uma saída de dados, porque o ponto de vista é do programa para fora e não do computador para fora.

## Saída de dados
Os algoritmos precisam interagir com o usuário e para isso podemos utilizar o comando escreva() para imprimir alguma coisa na tela, dentro do parênteses vai o texto que você deseja que apareça na tela, dessa forma:

```javascript
escreva(“Olá Mundo”)
``` 
Você também você pode usar \n para pular uma linha e \t para dar um tab no texto. 

```javascript
escreva("Primeira linha\n,
         Segunda linha\n")
``` 

## Entrada de Dados
Para que o usuário interaja com o algoritmo, ele precisa ler o dado por meio do comando leia.

Contudo, assim como quando lemos alguma informação e guardamos ela no nosso cérebro, o computador também guardará o dado lido na memória, o dado informado será armazenado em uma variável.

A entrada de dados é feita com o comando leia(). Assim como o comando escreva(), ele também aceita vários argumentos. Lembre-se que o comando leia sempre guardará o valor em uma variável.

Como exemplo, se quisermos saber o nome do usuário basta utilizar os seguintes comandos e veremos a

```javascript
escreva (“Informe o seu nome:”)
leia (nome)
``` 
Na primeira linha temos o comando de saída escreva, que pede ao usuário que informe o seu nome. Sabemos disso por conta dos parênteses ;)

Já na segunda linha temos o comando de entrada leia, que vai pegar o dado informado e armazenar na variável nome. Assim como no comando escreva, tudo o que estiver entre parênteses será armazenado.

ou 

```javascript
inteiro idade

escreva("Digite a sua idade\n")
leia(idade)
``` 
Nesse exemplo, na primeiro linha declaramos a variável idade, na segunda linha temos o comando de saída escreva, que pede ao usuário que informe o sua idade.

Na tercfeira temos o comando de entrada leia, que vai pegar o dado informado e armazenar na variável nome. Assim como no comando escreva, tudo o que estiver entre parênteses será armazenado, assim como no exemplo anterior.

#### Mas e se quisermos que esses dados retornem ao usuário?

Para que esses dados retornem também usamos o escreva(), podemos informar ao usuário qual foi o nome informado utilizando os seguintes comandos:

```javascript
escreva (“Informe o seu nome:”)
  leia (nome)
  escreva (“Seu nome:  ", nome)
``` 
Dessa forma, o dado inserido no comando de entrada será exibido, através do segundo comando de saída escreva(), independente do que for inserido.

## Limpatela()
O comando limpatela() serve para limpar a tela do console, apagando tudo que há nela. 

Você pode ajustar um timer para vê-lo funcionando, dessa forma:

```javascript
inteiro idade

Timer(1000)
escreva("Digite a sua idade\n")
leia(idade)
escreva (“Sua idade:  ", nome)
limpatela()
``` 

Utilizando o timer() todos os comando utilizados terão um tempo limite de execução antes de passar para o próximo, sem que você precise clicar em enter.


# Resumo do Módulo
Dados são uma coleção de fatos, como números, palavras, medidas, observações ou apenas descrições de coisas. 

Na computação, dados são  informações  que foram traduzidas em uma forma eficiente para movimentação ou processamento. Em relação aos computadores, os dados são informações convertidas em formato digital binário. 

O código usa 0 e 1 para representar letras, números e símbolos, que são convertidos em 8 caracteres. É chamado de código binário porque é feito de apenas dois símbolos. O “bi” em binário significa dois.

### Como os dados são armazenados?
Computadores representam dados, incluindo vídeo, imagens, sons e texto, como valores binários usando padrões de apenas dois números: 1 e 0. Um bit é a menor unidade de dados e representa apenas um único valor. Um byte tem oito dígitos binários.

### Quais são os tipos de dados?

**Caractere:** Consiste de um único símbolo ou de uma concatenação de símbolos do alfabeto usado pela linguagem Portugol. Este alfabeto inclui todas as letras do alfabeto romano, todos os dígitos, 0, 1, . . . , 9 e os caracteres de pontuação, tais como ?, ., . . ., entre muitos outros símbolos.

**Cadeia:** Uma cadeia de caracteres, ou string, é uma sequência de caracteres contendo letras, dígitos e símbolos.

**Inteiro:** Os números inteiros são aqueles que não possuem componentes decimais ou fracionários, podendo ser positivos ou negativos.

Exemplo: 24

**Real:** Os dados de tipo REAL são aqueles que podem possuir componentes decimais ou fracionários, e podem também ser positivos ou negativos.

Exemplo: 13.3 ou 8/5

**Lógico:** Também chamados de booleanos, são usados para representar dois únicos valores lógicos possíveis: VERDADEIRO e FALSO. Quando uma condição é verdadeira, vai ser retornado True. Caso contrário, é retornado False.

**Vazio:** Caracteres vazios são definidos como brancos (espaços), por exemplo: “”, não possui nenhum símbolo, portanto é vazio.

### Entrada e saída de dados
Na programação, a entrada de dados é tudo basicamente tudo aquilo que entra de fora pra dentro, ou seja, informações que vem do meio externo para o programa. Já a saída de dados é o que vai do programa para fora.

Em portugol, a saída é feita através do comando **escreva()**, que imprimi algo na tela, lembrando que o retorno da entrada de dados também se dá através desse comando. Já a entrada ocorre através do comando **leia()**, que guarda o valor de uma variável inserido pelo usuário.

Temos também o comando **limpatela()**, que limpa a tela do console deixando-o pronto para receber e retornar informações.
