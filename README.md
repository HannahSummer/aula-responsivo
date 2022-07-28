# Aula-responsivo
Primeiro projeto responsivo
## Grid
-Bidimensional
-Divisão de toda apagina em linhas e colunas 
-Colocar elementos onde quiser nessa divisão

## Grid ou Flexbox
-Grid: Duas dimensoes (colunas e linhas)
-Flexbox uma dimensao (ou colunas ou linhas)
-Um complementa o trabalho do outro
-Verificar quais navegadores aindea não estão aceitando o Grid

## Propriedades

Vamos separar em 2 grupos 
`container` e `itens`

## Container
-display:grid;
-grid-template-columns;
-grid-temnplete-rows;
-gid-gap;
-grid-row-gap;
-grid-columns-gap;
-grid-template-areas;
... e mais 4 propriedades e **alinhamentos**


## itens
-grid-column
-grid-column-start
-grid-column-end
-grid-row
-grid-row-start
-grid-row-end
-grid-area
.. e mais 2 propriedades de **alinhamneto**

## GRid: alinhamentos
 
Existem 6 propriedades de alinhamentos:
1.`justify-content`
2.`align-content`
3.`justify-items`
4.`align-items`
5.`justify-self`
6.`align-self`

Vamos separá-los em 2 grupos:
1.`justify` e `align`
2.`content`, `items` e `self`

## justify e align

Sabendo que o grid é bidimensional, nós temos o eixo x e y.
o **eixo x** é o posicionamento horizontal, da esquerda para a direta.
o **eixo y** é o posicionamento vertical, de cima para baixo.

## content, items e self
 
 Juntando o `justify`, ou `align`, com esses elementos:`content`, `items` e `self`; nós observamos nossas propriedades

 ## Content

 `justify-content` e `align-content` nos premitem alinhar o próprio grid, relativo ao espaço fora do grid.

 O uso dessas prpriedades são9 raras, pois só é aplicado caso o grid seja menor que a area definida. (Por exemplo, quando usamos em px o tmanho do grid, podemos terminar com um grid pequeno,para o tamanho da area do grid)

 Podemos usar **7 valores**
 1.start
 2.end
 3.center
 4.stretch
 5.space-between
 6.space-around
 7.space-evenly

 ## Items

 `justify-items` e `align-items` nos permitem alinhar os items do nosso grid, em qualquer espaço disponivel, na celula que ele habitar.

podemos usar **4 valores**:
 1.start
 2.end
 3.center
 4.stretch

 ## Self
 `justify-self` e `align-self` vão nos permitem alinhar os items em si.

 Faz a mesma coisa que o `justify-items` e `align-items`, porem, é aplicado diretamente no item de um grid.
