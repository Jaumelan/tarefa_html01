
# Tarefa 5 HTML
## Jaime 

### Responda quais são as diferenças entre os elementos 'div' e 'span' na construção de páginas HTML.
Cada elemento HTML pertence alguma ou algumas categorias de conteúdo. O ```<div>``` é um container genérico para conteúdo de fluxo, para agrupar elementos em blocos com fins de estilo. O ```<span``` por também é um container genérico, porém ele é usado para conteúdo fraseado. Dentro de um ```<div>``` agrupando um bloco de elementos,  podem ter alguns elementos ```<span>``` agrupando estilos específicos para conteúdo fraseado.

### Elabore um formulário com o uso do elemento ‘label’ que seja ‘clicável’ para o controle de elemento de entrada do tipo ‘radio button’, isto é, ao clicar no ‘label’ o ‘radio button’ também é selecionado.

```<form>```\
        ```<p>Escolha sua mascote preferida</p>```\
            ```<div>```\
                ```<input  type="radio"  id="opcao1"  name="mascote"  value="cachorro">```\
                ```<label  for="opcao1">cachorro</label>```\
                ```<input  type="radio"  id="opcao2"  name="mascote"  value="gato">```\
                ```<label  for="opcao2">Gato</label>```\
                ```<input  type="radio"  id="opcao3"  name="mascote" value="hamster">```\
                ```<label  for="opcao3">Hámster</label>```\
            ```</div>```\
            ```<div>```\
                ```<button  type="submit">Enviar</button>```\
            ```</div>```\
    ```</form>``` 

### Por que não se aconselha o uso indiscriminado de elementos ‘div’? Explique quais seriam as alternativas para reduzir o uso destes elementos.
Os elementos do HTML possuem uma semântica, e estruturar um site com uso excessivo da tag  ```<div>``` dificulta a:
1. acessibilidade do conteúdo, pois ele não informa sobre a estrutura do documento. Há como colocar atributos na tag identificando uma espécie de estrutura, porém para o navegador continuará sendo um elemento div.
2. Leitura: ler o código identificando cada class pode ser cansativo e podemos errar em qual elemento div estamos.
3. Consistência e standard: podemos aprender a programar em HTML, mas se em cada lugar se programa usando uma base de código diferente, dificulta o entendimento entre os programadores.
Alternativas: **header**, **main**, **footer**, incluir dentro deles **sections**.