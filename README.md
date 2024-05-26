## Projeto: Composição da função $gof\left( x\right)$} 

## Descrição

Documento LaTex que calcula `gof(x)`, dada a composição das funções `f(2x - 3)` e `g(x{2} - 1)`.

## Funções

* `f(x)`: Esta função recebe um valor `x` e retorna `2x - 3`.
* `g(x)`: Esta função recebe um valor `x` e retorna `(x^2 - 1)^2 - 1`.
* `gof(x)`: Esta função (composta) aplica `g` ao resultado de `f(x)`. Em outras palavras, `gof(x)` é equivalente a `g(f(x))`.


## Resultado da função 

O resultado para o valor de `gof(x)` de acordo com o valor fornecido de `x` será: `4x^{2} - 12x + 8` 

## Explicação

A composição de funções envolve a aplicação de uma função (`g`) ao resultado de outra função (`f`). Nesse caso, `gof(x)` é calculado como:

 ```
 gof(x) = g(f(x))
 = g(2x - 3) // Substituindo x por f(x) em g
 = (2x - 3)^2 - 1 // Aplicando g
 = 4x^2 - 12x + 8 // Expandindo o quadrado
 ```
