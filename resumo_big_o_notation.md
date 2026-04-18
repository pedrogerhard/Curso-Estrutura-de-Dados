# BIG O NOTATION

- fala sobre escalabilidade, e não necessariamente performance

## Complexidade Temporal e Complexidade Espacial

Pensando em um array de exemplo

**Complexidade Temporal:** O tempo que levará para percorrer aquele array  

**Complexidade Espacial:** O tanto de memória alocada para fazer determinada ação  

---

## O (1) (constante)

Independente do tamanho do input o tempo de execução será o mesmo

**Exemplo:** Encontrar o primeiro elemento de um array. (Idependente do tamanho do array o tempo será o mesmo)

---

## O (LOG N)

Fuciona de maneira logaritimica, quando dobramos o input, o tempo de execução não dobra dobra também, mas escala de maneira exponencial

---

## O (N)

Escala na mesma medida que aumenta o input 

**Exemplo:** Quando precisamos percorrer um array de 5 elementos por completo e ai dobramos o tamanho do array,  
ou seja, se o meu input for o dobro o espaço de memória também vai ser o dobro

---

## O (N LOG N)

SORTING (quicksort, mergesort) DIVIDE AND CONQUER

**Exemplo:** Quando percorremos um array e dividimos ele até um único elemento e depois reordenamos em outro array e assim por diante

---

## O (N^2)

Para cada item em um array ele verifica todos os outros itens

**Exemplo:** O caso mais comum é um for dentro de um for