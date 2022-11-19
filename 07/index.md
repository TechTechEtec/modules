# Encerramento!

# Há sempre o que estudar

Agora iremos conhecer mais sobre algumas das linguagens de programação mais recomendadas para iniciantes e como funcionam, além de colocar em prática o que será visto mais futuramente.  

## Quais seriam essas linguagens?

Você deve estar se fazendo essa pergunta agora, então sem mais enrolação vamos lá. As linguagens de programação que vamos ver neste módulo são as seguintes:  
- HTML
- CSS

# HTML

Vamos começar pelo html, que apesar de ser bastante utilizado para criação de sites não é considerado uma linguagem de programação, pois ele não é capaz de criar funcionalidades mais dinâmicas, ele apenas cria e estrutura seções, links e parágrafos no site a partir de componentes como tags e atributos (que será visto ao decorrer do módulo).  

## Visual Studio Code

Para programar vamos usar o Visual Studio Code (ou VScode) uma IDE desenvolvida pela Microsoft. IDE é um programa que auxilia no desenvolvimento de softwares com ferramentas integradas que agilizam esse processo.  
Para instalar o VScode basta seguir este link:  
 <https://code.visualstudio.com/download>

## Criando um documento HTML

Para criar um arquivo basta selecionar a opção novo arquivo ou apertar Ctrl+Alt+N no teclado. Após criar o documento basta salvá-lo como index.html para começarmos a programar. Para salvar o arquivo é só pressionar Crtl+Shift+s no teclado e depois renomear para index.html.  

## Estrutura de um documento HTML

Agora que já criamos o arquivo vamos para a programação.  
Colocando um ponto de exclamação e apertando a tecla tab o código ficará assim:  
![Imagem do Visual Studio!](http://drive.google.com/uc?id=14P51ctqehaHum-seZXK8PHs9nEai2r_k)
![Exemplo de código HTML!](http://drive.google.com/uc?id=1GUj40oRIKfsn5XCKy8mz6TyegJW2Y7jg)

Antes de continuar é necessário explicar o que é tudo isso na tela:  
- <!DOCTYPE html> - Essa tag informa ao navegador qual versão do html está sendo usada no documento.

- <html> - A tag html é o elemento básico do documento, ela conterá todos os outros elementos e tags do documento, ela recebe o atributo lang=”” que determina o idioma do documento, por padrão ele está em inglês, mas dá para alterar para o português colocando “pt-br” no lugar do “en”.

- <head> - Determina o cabeçalho do documento, apesar de não possuir um valor visível ela é capaz de transmitir informações muito uteis ao navegador.

- <title> - Ela define o título da página, aquele nomezinho que aparece na aba do navegador sabe.

- <meta> - Essa tag insere metadados no código, como aquele charset=”UTF-8”, que garante que oo código vai ser ser compatível com os caracteres do padrão latino americano.

- <body> - Como o nome já diz ela representa o corpo do documento, é nela que os elementos visuais do site devem ser colocados.

## Tags de título e texto

Agora iremos ver algumas das principais tags de texto e título do html:  
- <h1> - A <h1> é a principal tag de título que possui seis níveis hierárquicos, onde o h1 é o título de maior nível e o h6 é o de menor nível.
- <p> - É a principal tag de texto do html, serve para compor um parágrafo.
- <span> - Tem a funcionalidade parecida com a <p>, mas essa tag pode ser usada para pequenas informações como legendas.

![Código "Hello word HTML"](http://drive.google.com/uc?id=1bm_k_dHNGMhmjKYl_lIDzOOhZi2GoJ_2)
![Primeiro site "Hello word HTML"](http://drive.google.com/uc?id=1wC6hD7dUsCU7OU8gnBQBR2ApHZb0sAwQ)

## Adicionando imagens no documento

Utilizando a tag <img> podemos adicionar uma imagem no nosso site, juntamente com essa tag temos o atributo src=”” que é onde devemos digitar o local onde a foto se encontra e o atributo alt=”” que é onde colocamos um nome alternativo para a nossa imagem. Como no exemplo abaixo:

![Código para inserir imagens em HTML](http://drive.google.com/uc?id=19omgcLRqHDZA7IyCaTznUxgaNiHeUYaW)

Neste exemplo foram utilizadas imagens do nosso mascote, o techbô.  
Agora que já vimos um pouco de como o html funciona vamos ver como o css funciona na estilização do html.  

# CSS

O css geralmente é usado junto com o html, e assim como ele o css também não é considerado uma linguagem de programação, mas sim uma linguagem de estilos, ou seja, enquanto o html cria o texto de um site o css atribui estilos a esse texto, alterando seu tamanho, cor etc.  

## Adicionando o css no html

Dentro da tag head no seu documento html você deve adicionar a seguinte sintaxe:  <link rel="stylesheet href="styles.css"">, após isso é só criar um arquivo styles.css.  

## Estilizando com css

Com o css é possível mudar o visual do nosso site de diversas formas, mudando a cor de fundo, alterando o tamanho de objetos, cores dos textos etc. Agora vamos ver como fazer isso na prática.  
- Background-color: serve para definir uma cor de fundo para o site, é só colocar a cor desejada, e como resultado a cor de fundo do site vai mudar. Veja nos exemplos abaixo:  

![Código para estilizar background HTML](http://drive.google.com/uc?id=1dzz9-mkQlFhCqQ3y189vtI28xpqY2BAB)
![Site com background ciano](http://drive.google.com/uc?id=1TwH3RM33ydgrYZEbtjOtjLyju1Sl6q62)

- Height e Width: Isso  serve para definir a largura e altura de um objeto pode ser uma imagem, botão etc. Para definir a altura e largura de um objeto você precisa especificar o tamanho desejado como nos exemplos abaixo:

![Código altura e largura HTML](http://drive.google.com/uc?id=1GAPgXziNdzsCJBJvjjRarWbwuaaj51JP)
![Site com imagem do techbô com altura e largura definida](http://drive.google.com/uc?id=1GAPgXziNdzsCJBJvjjRarWbwuaaj51JP)

- Justify-content: Essa propriedade vai definir como o navegador vai distribuir o espaço entre e ao redor dos objetos. E para que o justify-cintent funcione é preciso declarar o display: flex; que irá transformar os elementos em um flex container, transformando os itens em flex-itens. Veja nos exemplos a seguir:  

![Código de espaço entre objetos HTML](http://drive.google.com/uc?id=1w1eNsZEGgxZMRZ94jrMhbVVjnjw0GUag)
![Site com espaçamento entre objetos](http://drive.google.com/uc?id=1sni9e4RYZGJAnkCCPtj7hdV2cJ18A4-a)

Com o space-around é adicionado um espaço ao redor dos objetos selecionados, nesse exemplo selecionei três imagens do techbô.  

# Agora é com você!!
Agora que você já sabe como o html e o css funcionam é sua vez de criar seu próprio site do jeito que você imaginar. Não se preocupe caso tenha ficado confuso com algo ou não esteja se sentindo seguro ainda, saiba que o melhor jeito de aprender a programar é praticando.  








