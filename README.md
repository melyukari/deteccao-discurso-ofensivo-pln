# 🛡️ Detecção de Discurso Ofensivo com Processamento de Linguagem Natural

Projeto desenvolvido para a disciplina de Projeto Integrador IV da Fatec Rubens Lara.

## 📖 Sobre o projeto

Este trabalho tem como objetivo identificar automaticamente conteúdos ofensivos em textos utilizando técnicas de Processamento de Linguagem Natural (PLN) e algoritmos de Aprendizado de Máquina.

Foram utilizadas bases públicas e modelos de classificação para avaliar o desempenho na detecção de linguagem ofensiva em ambientes digitais.

---

## 🎯 Objetivos

- Realizar o pré-processamento dos textos;
- Aplicar a técnica de vetorização TF-IDF;
- Treinar modelos de classificação;
- Comparar métricas de desempenho;
- Analisar a relação entre polaridade textual e discurso ofensivo.

---

## 📂 Bases de dados utilizadas

- **OLID (Offensive Language Identification Dataset)**
- **Toxic Comment Classification Challenge**
- **Davidson Hate Speech Dataset**

---

## ⚙️ Etapas do projeto

✔ Limpeza e normalização dos textos

✔ Remoção de URLs e caracteres especiais

✔ Conversão para letras minúsculas

✔ Remoção de stopwords

✔ Vetorização utilizando TF-IDF

✔ Divisão entre conjuntos de treino e teste

✔ Treinamento dos modelos

✔ Avaliação dos resultados

---

## 🤖 Modelos utilizados

- Regressão Logística
- Naive Bayes
- Random Forest

---

## 📊 Métricas avaliadas

- Acurácia
- Precisão
- Recall
- F1-score
- Matrizes de confusão

---

## 🛠 Tecnologias utilizadas

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Principais resultados

Os modelos apresentaram desempenho satisfatório na classificação dos textos. A Regressão Logística apresentou os resultados mais equilibrados entre as métricas avaliadas, demonstrando elevada capacidade de generalização para a tarefa de detecção de discurso ofensivo.

Além disso, foi observada uma relação significativa entre polaridade negativa e presença de linguagem ofensiva, reforçando o potencial das técnicas de Processamento de Linguagem Natural para auxiliar sistemas automáticos de moderação de conteúdo.

---

## 📁 Estrutura do projeto

```
deteccao-discurso-ofensivo-pln
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── PI4.ipynb
│
├── dados/
│   └── README.md
│
├── artigo/
│   └── DiscursodeOdio_PI4.pdf
```

---

## 📄 Artigo

O artigo científico desenvolvido para o Projeto Integrador IV está disponível na pasta:

```
artigo/DiscursodeOdio_PI4.pdf
```

---

## 🚀 Possíveis trabalhos futuros

- Aplicação de modelos baseados em Transformers (BERT);
- Ampliação das bases de dados utilizadas;
- Detecção de ironia e sarcasmo;
- Análises contextuais mais avançadas;
- Comparação com técnicas de Deep Learning.

---

## 👩‍💻 Autoras

**Mel Yukari Tognoli Atsuji**  
Graduanda em Ciência de Dados — Fatec Rubens Lara

**Ellen Christine Ferreira Ozores**  
Graduanda em Ciência de Dados — Fatec Rubens Lara

---

## 📚 Projeto Integrador IV - 2026

Desenvolvido como parte das atividades do curso de Ciência de Dados da Fatec Rubens Lara.
