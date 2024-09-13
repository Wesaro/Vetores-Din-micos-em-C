# Tarefa: Manipulação de Vetores Dinâmicos em C

Este projeto trata da implementação de manipulação de vetores dinâmicos utilizando a linguagem C. A tarefa inclui a criação, busca, inserção e remoção de elementos em vetores dinâmicos, explorando o uso de alocação dinâmica de memória para expandir ou reduzir o tamanho do vetor conforme necessário.

## Funcionalidades Implementadas

### 1. Criação e Manipulação de Vetores Dinâmicos
- Foi feita a alocação dinâmica de vetores, permitindo ao usuário definir o tamanho do vetor em tempo de execução.
- O vetor é alocado utilizando a função `malloc`, e a memória é liberada adequadamente com `free` ao final do programa.

### 2. Busca em Vetores Dinâmicos
- Implementação de busca sequencial em um vetor dinâmico. O usuário pode procurar por valores específicos dentro do vetor, e o índice do elemento, caso encontrado, é retornado.

### 3. Inserção de Elementos em Vetores Dinâmicos
- Foi implementada a inserção de novos elementos no vetor dinâmico. Quando um novo elemento é adicionado, o vetor é realocado com a função `realloc` para aumentar seu tamanho.

### 4. Remoção de Elementos de Vetores Dinâmicos
- O programa permite a remoção de elementos específicos do vetor dinâmico, ajustando o tamanho do vetor ao remover o valor e realocar a memória, se necessário.

## Descrição Resumida

Este projeto exemplifica o uso de alocação dinâmica de memória em C para manipulação de vetores, permitindo a expansão e contração do vetor conforme as operações de inserção e remoção são realizadas. Além disso, foram desenvolvidas funcionalidades de busca sequencial e uma gestão eficiente da memória alocada durante o processo.

