# Page Layouts

    - Tables
    - Floats e clear
    - Frameworks e Grid Systems
    - Flexbox
    - Grid

## Posicionamentos

Controlar onde, na página, o elemento irá ficar,
alterando o fluxo normal dos elementos;

- Name: position
- Value: static|relative|absolute|fixed

## Relative 

- top, right, bottom, left, z-index

## Absolute

- Tem a mesma propriedade do relative mas sua posição
não muda em relação aos outros

## Fixed
- Fica fixa na pagina, mesmo dando scrools

## Element Stacking
- É o empilhamento de elementos (z-index)


============ flexbox =========

# Flexbox

* Nos permite posicionar os  elemnentos dentro da caixa.
* Controle em uma dimensão (horinzontal ou vertical).
* Alinhamento, direcionamento, ordenar e tamanhos

```css
div.parent {
    display: flex;
}
```

## flex-direction

* Qual a direção  do flex: horizontal ou vertical
* row | column

## alinhamento

* justify-content
* align-items



========= GRID =======

# Grid 

* Posicionamentos de elementos dentro da caixa 
* Posicionamento horizontal e vertical ao mesmo tempo
* Pode ser flexível ou fixo
* Cria espaços para os elementos filhos habitarem
