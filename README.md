# Notebooks de Processamento de Linguagem Natural (PLN)

Este repositório contém notebooks utilizados durante as aulas e projetos de PLN na FATEC Mauá, cobrindo desde os conceitos introdutórios até técnicas mais avançadas de análise textual com Python.

---

## Arquivos e Objetivos

### pln_aula02_Python_e_Bibliotecas.ipynb
**Objetivo:** Introdução ao uso do Python e bibliotecas voltadas ao processamento de linguagem natural.  
**Técnicas/Bibliotecas:** Python básico, manipulação de strings, bibliotecas `nltk`, `spacy`, `re`.  
**Observações:** Serve como base para os demais notebooks, apresentando as bibliotecas mais comuns da área.

---

### pln_aula03_Processamento_de_Texto.ipynb
**Objetivo:** Realizar o pré-processamento de textos, etapa fundamental em qualquer pipeline de PLN.  
**Técnicas:** Tokenização, remoção de stopwords, stemming e lematização.  
**Observações:** Prepara o texto bruto para análises mais complexas.

---

### pln_aula04_Extracao_de_Características.ipynb
**Objetivo:** Transformar textos em representações numéricas.  
**Técnicas:** Bag of Words (BoW), TF-IDF, vetorização com `CountVectorizer` e `TfidfVectorizer`.  
**Observações:** Importante para alimentar modelos de aprendizado de máquina com dados textuais.

---

### pln_aula05_Analise_Sintatica.ipynb
**Objetivo:** Explorar a estrutura gramatical das frases.  
**Técnicas:** POS Tagging, análise de dependência, árvores sintáticas com `spacy`.  
**Observações:** Fundamenta a análise estrutural de sentenças.

---

### pln_aula06_Interpretacao_Semantica_Gramaticas.ipynb
**Objetivo:** Analisar o significado das sentenças e aplicar gramáticas formais.  
**Técnicas:** Gramáticas com `nltk`, análise semântica e árvores sintáticas manuais.  
**Observações:** Aproxima o PLN da linguística computacional.

---

### pln_aula07_Descoberta_Conhecimentos_Textos.ipynb
**Objetivo:** Extrair conhecimento e padrões relevantes a partir de grandes volumes de texto.  
**Técnicas:** Named Entity Recognition (NER), coocorrência, nuvem de palavras.  
**Observações:** Muito útil para análise exploratória de dados textuais.

---

### pln_projeto01_Corpus.ipynb
**Objetivo:** Construção e exploração de um corpus textual.  
**Técnicas:** Coleta, limpeza e análise exploratória de corpus.  
**Observações:** Base para projetos mais robustos em PLN, a partir de dados reais.

---

### pln_projeto02_Analise_Estatistica.ipynb
**Objetivo:** Aplicar estatísticas básicas sobre textos.  
**Técnicas:** Frequência de palavras, medidas de centralidade e dispersão.  
**Observações:** Integra conhecimento de estatística com dados textuais.

---

### pln_projeto03_Analise_Relevancia.ipynb
**Objetivo:** Avaliar a relevância de palavras em diferentes documentos.  
**Técnicas:** TF-IDF, visualização de palavras-chave.  
**Observações:** Complementa as técnicas vistas em vetorização, com foco em aplicações reais.

---

## Requisitos
- Python 3.x  
- Bibliotecas: `nltk`, `spacy`, `scikit-learn`, `matplotlib`, `wordcloud`, `pandas`
