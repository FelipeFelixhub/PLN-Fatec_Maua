# Notebooks de Processamento de Linguagem Natural (PLN)

Este repositório contém notebooks utilizados durante as aulas de PLN na FATEC Mauá, cobrindo desde os conceitos introdutórios até técnicas mais avançadas de análise textual com Python.

---

## Arquivos e Objetivos

### pln_aula02_Python_e_Bibliotecas.ipynb
**Objetivo:** Introdução ao uso do Python e bibliotecas voltadas ao processamento de linguagem natural.  
**Técnicas/Bibliotecas:** Python básico, manipulação de strings, bibliotecas `nltk`, `spacy`, `re`.  
**Observações:** Este notebook serve como base para os demais, preparando o ambiente e apresentando as bibliotecas mais comuns na área de PLN.

---

### pln_aula03_Processamento_de_Texto.ipynb
**Objetivo:** Realizar o pré-processamento de textos, etapa fundamental em qualquer pipeline de PLN.  
**Técnicas:** Tokenização, remoção de stopwords, stemming e lematização.  
**Observações:** O foco é transformar o texto bruto em um formato mais estruturado, facilitando etapas posteriores como vetorização ou análise sintática.

---

### pln_aula04_Extracao_de_Características.ipynb
**Objetivo:** Transformar textos em representações numéricas.  
**Técnicas:** Bag of Words (BoW), TF-IDF, vetorização com `CountVectorizer` e `TfidfVectorizer`.  
**Observações:** Essencial para alimentar modelos de machine learning com dados textuais.

---

### pln_aula05_Analise_Sintatica.ipynb
**Objetivo:** Explorar a estrutura gramatical das frases.  
**Técnicas:** Part-of-Speech Tagging (POS), parsing com `spacy`, árvores sintáticas.  
**Observações:** Auxilia na compreensão da função de cada palavra e da estrutura das sentenças.

---

### pln_aula06_Interpretacao_Semantica_Gramaticas.ipynb
**Objetivo:** Analisar o significado das sentenças e criar gramáticas formais.  
**Técnicas:** Análise semântica, gramáticas com `nltk`, árvores sintáticas manuais.  
**Observações:** Tópico mais teórico, mas fundamental para aplicações que exigem compreensão de linguagem natural mais profunda.

---

### pln_aula07_Descoberta_Conhecimentos_Textos.ipynb
**Objetivo:** Descobrir padrões e extrair conhecimento útil a partir de textos.  
**Técnicas:** Extração de entidades nomeadas (NER), análise de coocorrência de palavras, geração de nuvens de palavras.  
**Observações:** Apresenta aplicações práticas para extração de informações relevantes em bases textuais grandes.

---

### pln_aula08_Relevancia_Palavras.ipynb
**Objetivo:** Avaliar a relevância das palavras em documentos e coleções de textos.  
**Técnicas:** TF-IDF avançado, análise de frequência, visualizações com `matplotlib` e `wordcloud`.  
**Observações:** Ideal para entender quais termos são mais importantes dentro de um contexto, auxiliando em classificações e buscas.

---

## Requisitos
- Python 3.x  
- Bibliotecas: `nltk`, `spacy`, `scikit-learn`, `matplotlib`, `wordcloud`

---

## Observações Gerais
- Os notebooks seguem uma sequência lógica para facilitar o aprendizado progressivo de PLN.
- É recomendável executar os notebooks em ambiente Jupyter Notebook ou Google Colab.
- Algumas bibliotecas (como `spacy`) podem exigir downloads adicionais de modelos de linguagem.
