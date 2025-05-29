# Notebooks de Processamento de Linguagem Natural (PLN)

Este repositório contém notebooks utilizados durante as aulas e projetos de PLN na FATEC Mauá, abrangendo desde conceitos introdutórios até técnicas avançadas de análise textual com Python.

---

## Arquivos e Objetivos

### `pln_aula02_Python_e_Bibliotecas`
**Objetivo:** Introdução ao uso do Python e bibliotecas voltadas ao processamento de linguagem natural.  
**Técnicas/Bibliotecas:** Python básico, manipulação de strings, bibliotecas `nltk`, `spacy`, `re`.  
**Observações:** Serve como base para os demais notebooks, apresentando as bibliotecas mais comuns da área.

---

### `pln_aula03_Processamento_de_Texto`
**Objetivo:** Realizar o pré-processamento de textos, etapa fundamental em qualquer pipeline de PLN.  
**Técnicas:** Tokenização, remoção de stopwords, stemming e lematização.  
**Observações:** Prepara o texto bruto para análises mais complexas.

---

### `pln_aula04_Extracao_de_Características`
**Objetivo:** Transformar textos em representações numéricas.  
**Técnicas:** Bag of Words (BoW), TF-IDF, vetorização com `CountVectorizer` e `TfidfVectorizer`.  
**Observações:** Importante para alimentar modelos de aprendizado de máquina com dados textuais.

---

### `pln_aula05_Analise_Sintatica`
**Objetivo:** Explorar a estrutura gramatical das frases.  
**Técnicas:** POS Tagging, análise de dependência, árvores sintáticas com `spacy`.  
**Observações:** Fundamenta a análise estrutural de sentenças.

---

### `pln_aula06_Interpretacao_Semantica_Gramaticas`
**Objetivo:** Analisar o significado das sentenças e aplicar gramáticas formais.  
**Técnicas:** Gramáticas com `nltk`, análise semântica e árvores sintáticas manuais.  
**Observações:** Aproxima o PLN da linguística computacional.

---

### `pln_aula07_Descoberta_Conhecimentos_Textos`
**Objetivo:** Extrair conhecimento e padrões relevantes a partir de grandes volumes de texto.  
**Técnicas:** Named Entity Recognition (NER), coocorrência, nuvem de palavras.  
**Observações:** Muito útil para análise exploratória de dados textuais.

---

### `pln_aula10_Analise_Sentimentos`
**Objetivo:** Analisar sentimentos expressos em textos.  
**Técnicas:** Classificação de polaridade, uso de léxicos de sentimentos, visualizações.  
**Observações:** Introduz conceitos de análise de sentimentos aplicados a dados textuais.

---

### `pln_aula11_Machine_learning`
**Objetivo:** Aplicar técnicas de aprendizado de máquina em tarefas de PLN.  
**Técnicas:** Modelos de classificação, validação cruzada, métricas de desempenho.  
**Observações:** Integra o aprendizado de máquina com o processamento de linguagem natural.

---

### `pln_aula12_Redes_Neurais`
**Objetivo:** Implementar redes neurais aplicadas ao processamento de linguagem natural..  
**Técnicas:** Redes neurais artificiais, embeddings de palavras, uso de bibliotecas como Keras e TensorFlow.  
**Observações:** Introduz conceitos de deep learning no contexto de PLN.

---


### `pln_projeto01_Corpus`
**Objetivo:** Construção e exploração de um corpus textual.  
**Técnicas:** Coleta, limpeza e análise exploratória de corpus.  
**Observações:** Base para projetos mais robustos em PLN, a partir de dados reais.

---

### `pln_projeto02_Analise_Estatistica`
**Objetivo:** Aplicar estatísticas básicas sobre textos.  
**Técnicas:** Frequência de palavras, medidas de centralidade e dispersão.  
**Observações:** Integra conhecimento de estatística com dados textuais.

---

### `pln_projeto03_Analise_Relevancia`
**Objetivo:** Avaliar a relevância de palavras em diferentes documentos.  
**Técnicas:** TF-IDF, visualização de palavras-chave.  
**Observações:** Complementa as técnicas vistas em vetorização, com foco em aplicações reais.

---

## Requisitos

- Python 3.x  
- Bibliotecas: `nltk`, `spacy`, `scikit-learn`, `matplotlib`, `wordcloud`, `pandas`

---

## Observações Gerais

- Os notebooks seguem uma sequência lógica para facilitar o aprendizado progressivo de PLN.
- É recomendável executar os notebooks em ambiente Jupyter Notebook ou Google Colab.
- Algumas bibliotecas (como `spacy`) podem exigir downloads adicionais de modelos de linguagem.
