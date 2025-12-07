# Estudo Comparativo dos Algoritmos de Ordenação do LibreOffice Calc

Este repositório armazena todos os artefatos de código e dados brutos gerados para o artigo acadêmico "Estudo Comparativo dos Algoritmos de Busca e Ordenação do LibreOffice Calc".

### Objetivo do Estudo

O objetivo principal do trabalho é preencher uma lacuna na documentação oficial do LibreOffice Calc, identificando e validando empiricamente o algoritmo de ordenação nativo empregado pelo software.

### Conteúdo do Repositório

*   Código-fonte em C++ (padrão C++17) das implementações dos algoritmos de ordenação (Insertion Sort, Shell Sort, Quick Sort, Introsort Manual) e do *wrapper* para `std::sort`.
*   *Scripts Python e Shell utilizados para pré-processamento de dados, execução do benchmark e pós-processamento (geração de tabelas e gráficos).

### Metodologia

O benchmark foi conduzido em um ambiente controlado, utilizando um conjunto de dados realístico de 94.011 registros numéricos. A metodologia envolveu a comparação do tempo de execução dos algoritmos implementados com o desempenho do `std::sort` (que representa o algoritmo do Calc) em diferentes tamanhos de amostra, com o objetivo de analisar a escalabilidade e a eficiência assintótica.

### Palavras-chave

`LibreOffice Calc`, `Algoritmos de Ordenação`, `Introsort`, `C++`, `Benchmark`, `Análise de Desempenho`, `Estrutura de Dados`.
