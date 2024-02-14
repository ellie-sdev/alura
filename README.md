# Anotações
Notas para não esquecer!!

## Atalhos vsCode

CTRL+A seleciona tudo
CTRL+K+C comenta um bloco selecionado
CTRL+K+F identa o bloco selecionado

ALT+Z limita o texto no display (quebra de parágrafo)

manter a tecla ALT pressionada e clicar, insere o cursor de texto em vários lugares para digitar ao mesmo tempo

<!--seu comentário aqui--> insere comentários
/*seu comentário aqui*/ insere comentários no arquivo.CSS

! + tab insere script base html no arquivo.html


## Comandos e tags CSS

padding: 2px; /*adiciona o mesmo espaçamento em todos os lados (horizontal e vertical)*/
padding: 2px 3px; /*valor 1 = eixo vertical | valor 2 = eixo horizontal*/
padding: 2px 3px 4px 5px; /*valor 1 = esp superior | valor 2 = esp direita | valor 3 = esp inferior | valor 4 = esp esquerda*/

@import url('https://seuenderecoaqui'); /*importa um outro documento ou link*/

:root{
    --crie-variavel: valor;
}   /*para criar variavel de estilo*/
    
    .body{
        propriedade: var(--cor-terciaria);
    } /*para aplicar na tag ou classe*/
    
   

display: flex; /*cria container flexbox*/

flex-direction: row; /*row (padrão) | row-reverse | column | column-reverse;*/

box-sizing: border-box; /*o box sizing limita o tamanho do conteúdo, de acordo com o tamanho dele (border-content) ou de acordo com o tamanho da borda (border-box)*/

align-items: center; /*alinha os filhos do container verticalmente ao centro*/

justify-content: space-between; /*alinha os filhos do container horizontalmente. space between alinha com espaços entre os elementos, das extremidades até o meio*/

height: 100vh;          /*100% da view port em head*/




