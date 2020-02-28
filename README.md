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

Zenzo é um aluno de matemática promissor e está encantado com a mais recente aula de recursões de seu professor. Ele esta em busca de maneiras de aproximar recursões e, para isso, precisa da sua ajuda para calcular seus valores exatos, para poder comparar os resultados$

De maneira geral, uma recursão de ordem n pode ser escrita na forma ![equation](https://latex.codecogs.com/gif.latex?f_k%3D%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%20a_i%20.%20f_k_-_i).

Dados os valores de **n**, **k** e **m**, bem como os valores de $$a_1,a_2,\dots,a_n$$ descubra o valor de $$f_k \mod m$$.
​

**Entrada**

A primeira linha da entrada contém três inteiros: **n**, **k** e **m**. A segunda linha contém n inteiros: $$a_1,a_2,\dots,a_n$$.
A terceira linha contém os n valores base da recursão: $$f_1, f_2, \dots, f_n \mod m$$.
​
**Saída**

Seu programa deve imprimir um único inteiro: o valor de $$f_k \mod m$$.

**Subtask 1 (20 pontos)**
* n=2
* 1 ≤ k ≤ 10^3
* 1 ≤ m ≤ 10^6
* -10^6 ≤ a1,a2 ≤ 10^6
​​
**Subtask 2 (40 pontos)**
* 1 ≤ n ≤ 10
* 1 ≤ k ≤ 10
* 1 ≤ m ≤ 10^6
* 0 ≤ ai ≤ 10^6	∀i, 1 ≤ i ≤ n

​​**Subtask 3 (40 pontos)**
* 1 ≤ n ≤ 10^3
* 1 ≤ k ≤ 10^3
* 1 ≤ m ≤ 10^6
* 0 ≤ ai ≤ 10^6 ∀i, 1 ≤ i ≤ n

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
