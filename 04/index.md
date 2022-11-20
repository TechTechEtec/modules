## Apresentação do módulo 

Nesse módulo você aprenderá conceitos muito utilizados por profissionais da área de programação, não só, mas também como utiliza-los na prática.  
Você já ouviu falar em variável? Matriz?   
Não preocupe-se, esses termos serão dominados por você em-breve.

**Conteúdo:**
- 	Declaração de variável
-	Declaração de constante
-	Declaração de vetores
-	Funções 
-	Matrizes 

# Declaração de variável

## **O que é variável? 

Variável é um termo muito utilizado quando se aprende lógica de programação, ela é basicamente um espaço reservado na memória do computador cujo valor pode ser alterado. Isso quer dizer que, enquanto o programa estiver sendo executado, os valores atribuídos as variáveis podem mudar.  
Existem algumas regras para a criação de variáveis, essas regras demonstram a ordem de sintaxe da linguagem: 

1.	O nome da variável tem que começar por uma letra ou pelo carácter undescore (_) e não pode ser uma palavra de uso da linguagem de programação. 
2.	O valor que a iniciará deve ser compatível com o tipo de dado da variável.
Caso o valor de inicialização seja omitido ela apresentará o valor por defeito:
0, 0.0, falso ou “”.   
3.	É possível definir mais que uma variável utilizando a vírgula (,) entre elas. 

A sintaxe é a seguinte:  

![Sintaxe de declaração de variável](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

A palavra “variável” pode ser omitida:  

![Sintaxe omitindo a palavra](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

Veja um exemplo:  
Criou-se a variável Idade, seu tipo de dado é inteiro e seu valor de inicialização é 10, (a segunda linha mostra a criação sem o uso da palavra “variável”).  
![Exemplo de uso de variáveis](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

Para utilizar qualquer variável e atribuir algum valor a ela é necessário cria-la antes, dessa forma ao modificar o valor da idade o código deve conter a declaração da variável e posteriormente o novo valor que ela assumirá.  

![Atribuindo valor as variáveis](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

# Declaração de constante

## **O que é uma constante?**

Foi visto que as variáveis são valores que precisam ser alterados no programa, porém existem valores que não devem ser alterados, nesse caso utiliza-se a constante.  
As constantes são espaços reservado na memória do computador em que os valores são fixos, ou seja, depois de declarada não pode ter seu valor modificado.  
A sintaxe para elas é muito semelhante a da variável, mas deve-se atentar que nesse caso não é permitido omitir o “constante”, pois assim criamos uma variável.  

![Sintaxe de uma constante](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)
Exemplo:  
Existem muitas constantes matemáticas, uma delas é o número pi, ele vale aproximadamente 3,14. Veja a declaração dessa constante.  

![Exemplo de uma constante](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS "Essa é a constante pi")

# Declaração de vetores

## **Vetores**

O conceito de vetores é essencial no mundo da programação, geralmente ele é denominado Array. Os vetores são necessários por permitirem que vários valores de variáveis distintas estejam armazenados, em sequência, em um único local, mas todas as variáveis devem ser do mesmo tipo e também possuir o mesmo nome.  
Para que a ideia não permaneça tão abstrata imagine que seu/a professor/a precisa criar um programa que leia todas as notas dos alunos, para os quais ela dá aula, e calcule a nota média de cada um. Ela provavelmente iria utilizar a variável de nome dos alunos diversas vezes, porém isso não é necessário, já que os nomes de todos os alunos pertencem á mesma variável.  
Então, ela pode simplesmente criar um vetor para armazenar todos os nomes.  
Isso quer dizer que sempre que uma variável for ser utilizada muitas vezes assumindo valores diferentes no mesmo código pode-se simplificar o código com o mecanismo dos vetores.  
Sintaxe para vetores:  

![Sintaxe de um vetor](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

Como várias variáveis são criadas ao mesmo tempo é necessário indicar quantas existe, essa informação deve ser inserida entre os “[]” logo depois do nome, além disso, para acessar um item dentro do vetor utiliza-se um índice, esse índice é sempre um número inteiro. Todos os dados armazenados no vetor chamam-se itens do vetor.  
Exemplo:  
Vetor do caso cita acima.  

![Declaração um vetor com valores](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

# Declaração de funções

## **Funções**
Uma função é uma série de comandos que constroem um passo a passo para a realização de uma tarefa específica de um código, elas podem ser usadas varias vezes no mesmo programa, e isso além de deixar o código mais eficiente e curto, também diminui as chances de alguma parte do código ser duplicada na hora de resolver algum problema.  
Assim, quando se tem um código suficientemente longo é como se ele fosse dividido em pequenas partes para chegar ao objetivo final do programa, e para cada pequena parte ou tarefa declara-se uma função.  
Existem muitas funções em diversas linguagens de programação, mas em Portugol a principal delas é a função início ().  
Ela é uma função obrigatória, dessa forma, sempre será a primeira função a ser declarada, pois sem ela o programa não inicializa.  
Sintaxe de funções mais a função início ():  

![Sintaxe das funções](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

Lembre-se que o código dessa função será escrito dentro das chaves ( {} ) e que nenhuma outra função pode ser declarada dentro delas.  
**Regras das funções Portugol:**
1.	Uma função não pode ser declarada dentro de outra.
2.	O nome de uma função sempre começa com uma letra minúscula ou underscore (_). 
3.	Por convenção uma função deve ter um nome que descreve uma que ela faz.

Exemplo:  
Essa função escreve uma mensagem para você.  
Repare que existe a função início e o nome da função escreva dentro da função início, isso ocorre porque a função início é a única a ser executada e todas as funções são chamadas, somente pelo nome, dentro dela para que sejam executadas também.  

![Exemplo de Função](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

Ademais, as funções podem ter parâmetros, eles funcionam como as variáveis, porém só existem dentro das funções em que foram criados, isto é, não podem ser utilizados sem elas.  
Esses parâmetros são definidos dentro dos “()” da função e separados por vírgula. Sua estrutura é como a de uma variável só que sem um valor de abertura, Por exemplo: Declarou-se uma função notaMédia, que soma duas notas quaisquer e divide por dois. Essa função será escrita dessa forma:  

![Exemplo da Função calcula a média](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

Para que essa função seja executada, deve-se colocar o nome dela na função inicio e adicionar os valores para os parâmetros nota.  

![Exemplo da Função calcula a média dois](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

# Matrizes

## **Funções**

Uma matriz é um conjunto de variáveis do mesmo tipo, assim como um vetor, a diferença é que o vetor é unidimensional e a matriz é bidimensional.  
Para ficar mais claro a matriz é como uma tabela, cada linha dessa tabela é como um vetor e cada coluna também.  
Um exemplo para isso é uma tabela é o tabuleiro de xadrez, onde cada posição é associada a uma letra e um número no tabuleiro.  
Sintaxe:  

![Sintaxe de matrizes](https://drive.google.com/drive/folders/1aTJW0f6ZgA0wGxFKLKGbil16SpuP3fXS)

Veja a seguir:  
Uma matriz com quatro colunas e quatro linhas foi criada, ela é do tipo inteiro e seus valores serão colocados em ordem crescente de 01 à 16.  

![Exemplo de matriz com números](https://drive.google.com/drive/folders/17GyWSTEj7N8KiYR7rHub_Eo3eEU7CpEw)

Para localizar um item dentro de uma matriz basta indicar a linha e a coluna em que o item está.  

# Resumo do capítulo 

## Parabéns você concluiu mais um capítulo!
Nesse módulo foram apresentados conceitos importantes de programação, que são frequentemente utilizados pelos programadores, são esses: variáveis as quais atribuímos valores temporários enquanto o programa está funcionando, constante, são aquelas que não trocamos os valores atribuídos durante o funcionamento do programa, vetores, que são basicamente um conjunto linear de variáveis com o mesmo tipo de dados, e matrizes.  
Além disso, foi demonstrado nesse capítulo as declarações de algumas funções muito importantes em Portugol, como por exemplo, a função inicio(), que estará presente em todos os códigos em Portugol e onde todo o sistema será escrito. 
Lembre-se: Esse material é inteiramente seu, sempre que precisar reveja esses conceitos ou a sintaxe da linguagem.  



