# Avaliação Final (A2) - Séries Temporais

Trabalho válido pela disciplina de Séries Temporais, ministrada pelo professor [Thiago Guerrera Martins](https://emap.fgv.br/professores/thiago-guerrera-martins) na Fundação Getulio Vargas.

## Descrição

O trabalho consiste em um conjunto de análises de uma série temporal de interesse. Neste caso, a série de variáveis econônomicas nos Estados Unidos da América, conhecida como [`us_change`](https://www.rdocumentation.org/packages/fpp3/versions/0.4.0/topics/us_change).

        us_change is a quarterly tsibble containing percentage changes in quarterly personal consumption expenditure, personal disposable income, production, savings and the unemployment rate for the US, 1970 to 2016. Original $ values were in chained 2012 US dollars.

## Objetivo

O objetivo do trabalho é modelar a variável `consumption` da série temporal `us_change`. Para isso, os seguintes modelos serão ajustados:
- Modelo baselines;
- Modelo de suavização exponencial;
- Modelo de regressão linear múltipla;
- Modelo SARIMA;
- Modelo de Convolução 1D;
- Modelo RNN (LSTM);

Além da modelagem, o trabalho também visa apresentar análises de resíduos, diagnósticos com relação aos modelos ajustados e discussões acerca da necessidade de transformações, bem como a necessidade de decomposição entre tendência e sazonalidade.

## Membros do grupo

- Ari Oliveira
- Breno Marques Azevedo
- Daniel Jacob
- Gustavo Ramalho
- Vinicius Hedler
