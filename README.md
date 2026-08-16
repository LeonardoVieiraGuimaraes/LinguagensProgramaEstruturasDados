# Linguagens de Programação e Estruturas de Dados

Material didático que apresenta as mesmas estruturas de dados em **três linguagens**:
C, Java e JavaScript.

## Estrutura

| Pasta | Unidades |
| :--- | :--- |
| `C` | `U01`, `U02` |
| `Java` | `U01`, `U02`, `U03` |
| `JavaScript` | — |

## A ideia por trás da divisão por linguagem

Uma lista encadeada é a mesma ideia nas três — o que muda é o que a linguagem te obriga a
enxergar:

- **Em C**, você gerencia a memória. Ponteiro, `malloc`, `free`. A estrutura fica explícita
  porque não há para onde escondê-la
- **Em Java**, a coleção já existe pronta. O exercício passa a ser entender o que
  `ArrayList` faz por dentro, e por que às vezes `LinkedList` é melhor
- **Em JavaScript**, arrays são dinâmicos e tipagem é fraca. O foco vira o comportamento,
  não a alocação

Quem só aprende em uma linguagem tende a confundir a estrutura com a implementação dela.
Ver as três desfaz essa confusão.

## Conteúdo

Listas, pilhas, filas, árvores, ordenação e busca — com análise de complexidade.

## Como rodar

```bash
# C
gcc arquivo.c -o programa && ./programa

# Java
javac Arquivo.java && java Arquivo

# JavaScript
node arquivo.js
```

---

## Autor

**Leonardo Vieira Guimarães** — desenvolvedor backend e Product Owner no IMA.
Mestre em Modelagem Computacional e Sistemas (UNIMONTES), doutorando em Modelagem
Matemática e Computacional (CEFET-MG).

[![Portfólio](https://img.shields.io/badge/Portf%C3%B3lio-leoproti.com.br-0A0A0A?style=flat)](https://leoproti.com.br)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--3118--4664-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0000-3118-4664)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-perfil-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leonardo-vieira-guimaraes/)
