Curso de Maratona de programação: Algoritmos para sua primeira competição
---------
<img src="https://www.alura.com.br/assets/api/cursos/maratona-de-programacao.svg" data-canonical-src="https://www.alura.com.br/assets/api/cursos/maratona-de-programacao.svg" width="250" height="250" />

https://cursos.alura.com.br/course/maratona-de-programacao

## Temas abordados
* Começando o treinamento
* Ordenação
* Recursão
* Busca binária
* Introdução à Programação dinâmica


## Febre de Recursões

https://neps.academy/problem/279

Zenzo é um aluno de matemática promissor e está encantado com a mais recente aula de recursões de seu professor. Ele esta em busca de maneiras de aproximar recursões e, para isso, precisa da sua ajuda para calcular seus valores exatos, para poder comparar os resultados.

De maneira geral, uma recursão de ordem n pode ser escrita na forma ![equation](https://latex.codecogs.com/gif.latex?f_k%3D%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%20a_i%20.%20f_k_-_i).

Dados os valores de **n**, **k** e **m**, bem como os valores de ![equation](https://latex.codecogs.com/gif.latex?a_1%2Ca_2%2C%5Cdots%2Ca_n) descubra o valor de ![equation](https://latex.codecogs.com/gif.latex?f_k%20%5Cmod%20m).
​


**Entrada**

A primeira linha da entrada contém três inteiros: **n**, **k** e **m**. A segunda linha contém n inteiros: ![equation](https://latex.codecogs.com/gif.latex?a_1%2Ca_2%2C%5Cdots%2Ca_n).
A terceira linha contém os n valores base da recursão: ![equation](https://latex.codecogs.com/gif.latex?f_1%2C%20f_2%2C%20%5Cdots%2C%20f_n%20%5Cmod%20m).
​

**Saída**

Seu programa deve imprimir um único inteiro: o valor de ![equation](https://latex.codecogs.com/gif.latex?f_k%20%5Cmod%20m).

**Subtask 1 (20 pontos)**
* n=2
* ![equation](https://latex.codecogs.com/gif.latex?1%5Cleq%20k%20%5Cleq%2010%5E%7B3%7D)
* ![equation](https://latex.codecogs.com/gif.latex?1%5Cleq%20m%20%5Cleq%2010%5E%7B6%7D)
* ![equation](https://latex.codecogs.com/gif.latex?-10%5E%7B6%7D%5Cleq%20a_1%2Ca_2%20%5Cleq%2010%5E%7B6%7D)
​​

**Subtask 2 (40 pontos)**
* ![equation](https://latex.codecogs.com/gif.latex?1%20%5Cleq%20n%5Cleq%2010)
* ![equation](https://latex.codecogs.com/gif.latex?1%20%5Cleq%20k%5Cleq%2010)
* ![equation](https://latex.codecogs.com/gif.latex?1%20%5Cleq%20m%5Cleq%2010%5E%7B6%7D)
* ![equation](https://latex.codecogs.com/gif.latex?0%20%5Cleq%20a_i%20%5Cleq%2010%5E%7B6%7D)	![equation](https://latex.codecogs.com/gif.latex?%5Cforall%20i%2C%201%20%5Cleq%20i%20%5Cleq%20n)


​​**Subtask 3 (40 pontos)**
* ![equation](https://latex.codecogs.com/gif.latex?1%20%5Cleq%20n%5Cleq%2010%5E%7B3%7D)
* ![equation](https://latex.codecogs.com/gif.latex?1%20%5Cleq%20k%5Cleq%2010%5E%7B3%7D)
* ![equation](https://latex.codecogs.com/gif.latex?1%5Cleq%20m%20%5Cleq%2010%5E%7B6%7D)
* ![equation](https://latex.codecogs.com/gif.latex?0%20%5Cleq%20a_i%20%5Cleq%2010%5E%7B6%7D)	![equation](https://latex.codecogs.com/gif.latex?%5Cforall%20i%2C%201%20%5Cleq%20i%20%5Cleq%20n)

**Exemplos**
```
Entrada:
5 15 100
3 0 -2 4 7
1 1 1 1 1

Saída:
68

Entrada:
2 12 1000
1 1
1 1

Saída:
144
```

**Nota**
**Escrevendo equações no Markdown: https://stackoverflow.com/a/45603559**