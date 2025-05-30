## Lab1: Determinando a Conexidade de Vértices em um Grafo

Este lab consiste em desenvolver um programa que analise um grafo não orientado e determine sua conexidade de vértices, indicando se ela é zero, um, dois ou pelo menos três.

### Entrada

O programa deve ler o grafo da entrada padrão. A primeira linha conterá dois inteiros, $n$ e $m$, representando o número de vértices e o número de arestas, respectivamente. Os vértices serão identificados pelos inteiros de $0$ a $n-1$. As $m$ linhas seguintes descreverão as arestas, cada uma contendo um par de inteiros $(u, v)$ indicando uma conexão entre os vértices $u$ e $v$.

### Saída

A saída do programa deve seguir as seguintes especificações:

* **Conexidade Zero:** Se o grafo for desconexo, imprima:
    ```
    Grafo desconexo.
    ```

* **Conexidade Um:** Se a conexidade de vértices for um, imprima:
    ```
    Grafo 1-conexo.
    ```
    Em seguida, liste cada **vértice de corte** (também conhecido como ponto de articulação) em uma linha separada, em ordem lexicográfica.

* **Conexidade Dois:** Se a conexidade de vértices for dois, imprima:
    ```
    Grafo 2-conexo.
    ```
    Em seguida, liste cada **par de vértices de corte** (pares de vértices cuja remoção desconecta o grafo) em uma linha separada, em ordem lexicográfica e sem repetir pares.

* **Conexidade Três (ou mais):** Se a conexidade de vértices for igual ou superior a três, imprima:
    ```
    Grafo 3-conexo.
    ```
