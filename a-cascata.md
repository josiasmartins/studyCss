# A Cascata (cascading)

A escolha do browser de qual regra aplicar, caso haja muita regra para aplicar para o mesmo elemento

* Seu estilo é lido de cima para baixo

É levado em consideração três fatores:
    1. Origem do estilo
    2. Especifidade
    3. Importância

### Origim do estilo
inline > tag style > tag link

### Especifidade
É um cálculo matemático, onde, cada tipo de seletor e origem do estilo, possuem valores a serem considerados.

0. Universal selector, combinators e negation pseudo-class (:not())
1. Element type selector e pseudo-elements (::before, ::after)
10. Classes e atributte selectors ([type="radio"])
100. ID selector
1000. Inline

## A regra !important

* cuidaddo, evite o uso
* não é consideado uma boa prático
* quebra o fluxo natural da cascata