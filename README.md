# Projeto: Implementação de uma Árvore AVL com Índice Remissivo

## Descrição

Este projeto implementa uma árvore AVL em Python para construir um índice remissivo de um arquivo de texto. A árvore AVL é uma árvore binária de busca auto-balanceada, que garante um tempo de busca, inserção e deleção eficiente,
mantendo a altura balanceada automaticamente após cada inserção ou remoção.

A árvore é usada para armazenar palavras de um arquivo de texto, permitindo buscas rápidas e eficientes. Além disso, o código cria um arquivo de índice remissivo que contém cada palavra distinta, seguida pelas linhas em que elas
aparecem no arquivo original.

## Estrutura do Projeto

O projeto contém os seguintes arquivos:

- **`no.py`**: Define a classe `NO`, que representa os nós da árvore AVL. Cada nó armazena a informação (a palavra), sua altura, os ponteiros para os filhos esquerdo e direito, e uma lista com as linhas em que a palavra aparece.
  
- **`avl.py`**: Implementa a classe `AVL`, que contém as funções necessárias para inserir palavras, balancear a árvore (rotacionar), buscar palavras, e gerar o índice remissivo. As funções principais incluem:
  - Inserção de palavras mantendo o balanceamento da árvore.
  - Busca de palavras e verificação da frequência em diferentes linhas.
  - Geração do arquivo `indice_remissivo.txt` contendo o índice remissivo.

## Funcionalidades

- **Inserção e Balanceamento**: A árvore é balanceada automaticamente após a inserção de cada nova palavra.
- **Busca**: Permite buscar uma palavra específica e verificar em quantas linhas ela aparece.
- **Geração de Índice Remissivo**: Cria um arquivo `indice_remissivo.txt` que lista todas as palavras distintas e suas respectivas linhas.
- **Frequência de Palavras**: Identifica qual palavra aparece no maior número de linhas.


