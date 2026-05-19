# Sistema de Recomendação de Medicamentos

Projeto desenvolvido para a disciplina **Projeto Aplicado III** do curso de **Ciência de Dados da Universidade Presbiteriana Mackenzie**.

O objetivo do projeto é desenvolver um **sistema de recomendação de medicamentos baseado em dados**, capaz de sugerir tratamentos adequados a partir de **sintomas ou condições clínicas informadas pelos usuários**, utilizando o dataset **UCI ML Drug Review**. 

*Link do Vídeo*: <a href='https://youtu.be/4B-HijaPbgo'>Vídeo Explicativo</æ>

## Autores

* Cainã Fernandes Guimarães da Silva
* Gabriel de Oliveira Meloni
* Humberto Guttau Bravo
* Jimmy Paiva Gomes

Universidade Presbiteriana Mackenzie
São Paulo — 2026

---

# Visão Geral

O avanço das tecnologias de dados tem possibilitado o desenvolvimento de soluções inteligentes aplicadas à saúde, especialmente no apoio à tomada de decisão.

Neste contexto, os **sistemas de recomendação** podem ser utilizados para sugerir medicamentos com base em:

* sintomas informados pelo usuário
* condições clínicas associadas
* avaliações de outros usuários
* padrões identificados em dados históricos

Este projeto propõe a construção de um sistema que analisa o dataset **UCI Drug Review**, contendo avaliações reais de usuários sobre medicamentos, para gerar recomendações fundamentadas em evidências empíricas. 

---

# Contexto do Estudo

O projeto está inserido no contexto da **transformação digital na área da saúde**, com foco no ambiente farmacêutico.

Atualmente, é comum que indivíduos recorram à automedicação, muitas vezes sem orientação adequada, o que pode gerar riscos à saúde. Segundo o trabalho, essa prática é amplamente disseminada e representa um desafio relevante de saúde pública. 

Diante disso, o sistema proposto busca:

* auxiliar na escolha mais informada de medicamentos
* reduzir riscos associados à automedicação inadequada
* ampliar o acesso à informação confiável

⚠️ **Importante:** O sistema não substitui profissionais da saúde, atuando apenas como ferramenta de apoio à decisão.

---

# Objetivos

## Objetivo Geral

Desenvolver um **sistema de recomendação de medicamentos** capaz de sugerir tratamentos com base em sintomas ou doenças informadas, utilizando dados históricos de avaliações de usuários.

## Objetivos Específicos

* Explorar o dataset **UCI ML Drug Review**
* Identificar padrões entre doenças, medicamentos e avaliações
* Aplicar técnicas de:

  * análise de dados
  * processamento de linguagem natural (NLP)
  * agrupamento (clustering)
* Desenvolver um modelo de recomendação baseado em similaridade e evidências empíricas
* Avaliar a qualidade das recomendações geradas

---

# Abordagem do Projeto

O sistema será desenvolvido combinando diferentes técnicas de ciência de dados:

### 1. Análise de Dados

* Exploração das variáveis (condição, medicamento, avaliação)
* Identificação de padrões relevantes

### 2. Processamento de Linguagem Natural (NLP)

* Análise de reviews textuais
* Extração de informações semânticas

### 3. Agrupamento (Clustering)

* Identificação de grupos semelhantes de medicamentos/doenças
* Uso de métricas como **Silhouette Score** para validação 

### 4. Sistema de Recomendação

* Baseado em similaridade entre casos
* Possível uso de abordagem híbrida (conteúdo + padrões de dados)

---

# Etapas do Projeto

O projeto segue três frentes principais:

## A) Ciência de Dados

1. Coleta e entendimento dos dados
2. Pré-processamento
3. Análise exploratória (EDA)
4. Engenharia de features
5. Modelagem
6. Avaliação
7. Interpretação dos resultados

## B) Engenharia de Software

1. Definição de requisitos
2. Arquitetura do sistema
3. Implementação
4. Testes
5. Validação
6. Deployment

## C) Engenharia de Dados

1. Preparação do dataset
2. Pipeline de processamento
3. Integração de dados estruturados e textuais

---

# Tecnologias Utilizadas

* Python
* Bibliotecas de Data Science (pandas, numpy, scikit-learn)
* Ferramentas de visualização de dados

---

# Resultados Esperados

Espera-se que o sistema seja capaz de:

* Identificar relações entre sintomas e medicamentos
* Gerar recomendações baseadas em experiências reais de usuários
* Auxiliar na tomada de decisão em contextos de baixa complexidade
* Demonstrar a aplicação de **ciência de dados na área da saúde**

Além disso, o projeto contribui com o **ODS 3 — Saúde e Bem-Estar**, promovendo o uso mais consciente de medicamentos. 

---

# Considerações Éticas

* O sistema não substitui orientação médica
* Deve ser utilizado apenas como apoio informacional
* Considera aspectos de:

  * confiabilidade
  * transparência
  * uso responsável de dados

---

# Referências

Baseado no dataset:

* UCI ML Drug Review Dataset

E em conceitos de:

* Sistemas de recomendação
* Machine Learning aplicado à saúde
* Processamento de linguagem natural
* Mineração de dados
