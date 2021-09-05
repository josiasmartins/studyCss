# Seletores

Conecta um elemento HTML com o CSS a fim de alterar o elemento

## Tipos

* Element Selector
    - Todos os elementos HTML
* ID selector
    - um elemento que tenha um atributo `id`
    - Cada id deverá ser único
* Class Selector
    - Os elementos que contenha um atributo `class`.
    - Podemos ter uma ou mais classes
* Atribute Selector
    - Um elemto que tenha um atributo específico
* Pseudo-class Selector
    - Elementos em um estado específico.

## Multiplos 

Você poderá selecionar multiplos elementos e aplicar alguma regra de css para todos eles

Usamos uma separação por virgulas para isso

````css
h1, p, a {
    color: red;
}
`````
/* muda o estado do elemento do psudo-class para cor, size etc */
exemplo p:hover {
    color: blue; 
}
