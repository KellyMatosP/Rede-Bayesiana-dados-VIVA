# Modelagem Preditiva da Violência Sexual com Redes Bayesianas

Este repositório contém o notebook utilizado no Trabalho de Conclusão de Curso (TCC) intitulado **"Modelagem preditiva da violência sexual no Brasil em 2022"**, com foco na aplicação de **redes bayesianas** e **regressão logística** para análise de risco social.

## 📄 Arquivo principal

- [`TCC_Viol_SEXU_REDEBAYESIANA.ipynb`](TCC_Viol_SEXU_REDEBAYESIANA.ipynb): Notebook com todo o processo de modelagem em ambiente R via Google Colab, incluindo pré-processamento, construção dos modelos, avaliação preditiva e simulações.

## 📊 Objetivo do estudo

O projeto visa estimar a probabilidade de vitimização por violência sexual a partir de variáveis sociodemográficas, relacionais e de reincidência, utilizando dados do sistema VIVA/SINAN (2022). A abordagem com redes bayesianas permite identificar fatores de risco, construir inferências condicionais e orientar estratégias de proteção social.

## 🧠 Metodologia

- **Algoritmo Structural EM** para aprendizado da estrutura da rede
- **Extração do Markov Blanket** da variável alvo (`VIOL_SEXU`)
- Comparação com **modelo de regressão logística**
- Avaliação por métricas como acurácia, sensibilidade e F1-score
- Simulação de cenários de risco por idade, sexo, local e vínculo com o agressor

## 📁 Dados

Os dados utilizados são oriundos do sistema **VIVA/SINAN (Ministério da Saúde - Brasil, 2022)**. Por questões de confidencialidade, os microdados não são disponibilizados neste repositório. Para acesso, consulte o [DATASUS](https://datasus.saude.gov.br/).

## 📚 Requisitos

Este notebook foi executado em ambiente **Google Colab com suporte a R**. Para reprodução local, é necessário:

- R 4.0 ou superior
- Pacotes: `bnlearn`, `gRain`, `ggplot2`, `dplyr`, `caret`, `readr`, `stringr`

## 🧾 Autoria

Este trabalho foi desenvolvido por **Kelly Matos** como parte do TCC em **Ciências Atuariais**, com orientação de [nome da orientadora, se desejar].

---

