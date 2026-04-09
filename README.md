# Data Cleaning - Hospedagens

Este repositório contém um projeto de **Limpeza e Tratamento de Dados** focado em um conjunto de dados de hospedagens. O objetivo principal foi transformar dados brutos (em formato JSON aninhado) em um formato estruturado e pronto para análise estatística ou modelos de Machine Learning.

## Tecnologias Utilizadas
* **Python 3.x**
* **Pandas**: Manipulação e análise de dados.
* **NumPy**: Operações matemáticas.
* **Regex (re)**: Limpeza de strings e caracteres especiais.

## Conceitos e Técnicas Aplicadas
Neste notebook, foram implementadas diversas etapas fundamentais de uma pipeline de dados:

1.  **Normalização de JSON**: Conversão de dados semi-estruturados em tabelas (DataFrames).
2.  **Tratamento de Dados Aninhados**: Uso do método `explode` para lidar com listas dentro de colunas.
3.  **Conversão de Tipos de Dados**: Transformação de colunas para formatos adequados (`int64`, `float64` e `datetime`).
4.  **Limpeza de Strings com Regex**: Remoção de símbolos de moeda ($) e vírgulas para conversão numérica.
5.  **Manipulação de Séries Temporais**: Formatação e agrupamento de dados baseados em datas (Ano/Mês).
6.  **Tokenização Básica**: Processamento inicial de textos descritivos.

## O Dataset
O conjunto de dados apresenta informações detalhadas sobre imóveis para locação, incluindo:
* Disponibilidade e datas.
* Preços e taxas extras.
* Descrições de amenidades.
* Informações geográficas (foco na região de Seattle/Ballard).

## Como Executar
1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)
