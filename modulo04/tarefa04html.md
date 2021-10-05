# Tarefa 3 HTML
## Jaime 

**Qual a última versão do HTML?**
A última versão é o HTML5.

**O que é uma 'tag' em HTML? Dê um exemplo.**
As tags estão dentro dos símbolos <>, servem para separar o código HTML do texto. Tudo que seja escrito dentro da tag indica como o texto aparecerá no navegador.
Exemplo: ```<p></p> ```

**O que é um 'atributo' em HTML? Dê um exemplo.**
Atributos servem para agregar informação sobre um elemento, se escrevem dentro das tags, e geralmente têm um nome e um valor.
Exemplo: ```<p ```==style="color=red;"==>```</p>```

**O HTML é sensível ao caso?**
Ele não é sensível ao caso, mas é uma boa prática manter tudo em minúsculas. A maioria da sintaxe do HTML (nomes dos elementos e atributos) não são sensíveis ao caso, porém é para os caracteres U+0041 até U+007A.

**O que é o 'DOM' e qual é sua importância?**
Quando uma página web é carregada no navegador, ele o transforma na árvore DOM: Document Object Model. A árvore DOM é representação do documento contendo diferentes tipos de nós: DocumentType, Elements, Text, Comment e em alguns casos ProcessingInstruction. Cada elemento na árvore DOM é representada como um objeto, e cada um deles tem API's para que possam ser manipulados.
Em resumo, o DOM é a interface que representa como documentos HTML e XML são lidos no navegador. Ele permite que uma linguagem (JavaScript) manipule, estruture e estile o site.

**O que é uma 'URL'? Dê exemplo.**
URL significa Uniform Resource Locator, é um endereço que é dado a um recurso único na Web. Cara URL válida aponta a um único recurso. Esses recursos podem ser páginas HTML, documentos CSS, imagens, etc.
Exemplo: https://github.com

**Qual a importância do atributo 'charset'?**
Para apresentar corretamente uma página HTML, um navegador precisa saber quais caracteres deve usar. Para isso ele usa o atributo 'charset' que receberá um valor.

**O que é 'UTF-8'? Qual sua importância?**
Em HTML5 é recomendado usar charset="UTF-8", pois inclui a maioria de caracteres e símbolos mundiais, sendo essa sua importância. UTF-8 é uma codificação de caracteres. É o valor dado ao atributo charset, por exemplo:
charset="UTF-8".

**Qual a importância da programação HTML considerando-se a semântica nos arquivos criados? Dê 4 exemplos de elementos HTML que servem para definição de semântica.**
O HTML foi desenhado para ser uma linguagem para descrever textos científicos de forma semântica. Devido a que cada elemento em HTML tem sua semântica isso ajuda na acessibilidade do seu conteúdo para pessoas com necessidades especiais. Ao usar os elementos para seus dados propósitos, facilita tanto aos computadores como às pessoas entendê-los.

![Importancia da semântica] (semantics.jpg)

Exemplos:
1. ```<h1></h1>```: Título de maior importância na seção;
2. ```<h2></h2>```: Título de segunda maior importância na seção;
3. ```<main></main>```: Especifica o conteúdo primário do documento;
4. ```<strong></strong>```: Especifíca um texto que é importante.

**Para que serve o atributo 'lang' colocado no elemento 'html'? Altera o comportamento da página ao abri-la? Explique**
O atributo global 'lang' declara o idioma do conteúdo do site Web, ajuda os buscadores e navegadores. Em acessibilidade, para os leitores de páginas, indica a linguagem em que será lido o site.
Ele não altera o comportamento da página ao abri-la.