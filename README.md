# 🚀 AI Business Insights Pipeline

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas)
![Google Gemini](https://img.shields.io/badge/AI-Gemini-orange)
![Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Concluído-success)
![License](https://img.shields.io/badge/License-MIT-green)

<br>


## 📌 Sobre o Projeto

Este projeto implementa um **pipeline de dados ETL (Extract, Transform, Load)** enriquecido com **Inteligência Artificial Generativa**, com o objetivo de transformar dados simples em **insights estratégicos de negócio**.

A solução simula um cenário real de Engenharia de Dados, onde informações brutas são processadas e enriquecidas com IA para apoiar **tomada de decisão orientada a dados**.

<br>


## 🎯 Objetivo

- Construir um pipeline de dados completo utilizando Python  
- Integrar IA generativa para enriquecimento de dados  
- Gerar insights estratégicos automatizados  
- Criar visualizações analíticas (dashboard)  
- Demonstrar boas práticas de Engenharia de Dados  

<br>


## 🧠 Contexto do Projeto

Este projeto foi desenvolvido como parte do desafio:

> **"Explorando IA Generativa em um Pipeline de ETL com Python"**

📚 Ministrado pelo professor **[Venilton Falvo Jr](https://www.linkedin.com/in/falvojr/)**  
🎓 Bootcamp: **[TOTVS](https://www.totvs.com/) - Fundamentos de Engenharia de Dados e Machine Learning**  
🏫 Plataforma: **[DIO (Digital Innovation One)](https://www.dio.me/)**  

🔗 https://web.dio.me/track/totvs-fundamentos-de-engenharia-de-dados-e-machine-learning

<br>


## 🏗️ Arquitetura do Pipeline

O projeto segue o padrão clássico de ETL:

> Extract → Transform → Load → Insights → Dashboard


### 📥 Extract
Coleta de dados de empresas (simulação de fonte externa)

### 🔄 Transform
Enriquecimento com IA (Google Gemini), gerando:
- Setor
- Maturidade digital
- Potencial de inovação
- Risco de mercado

### 💾 Load
Armazenamento dos dados processados em arquivos estruturados

### 📊 Analytics
Geração de insights e visualizações

<br>


## 🤖 Uso de Inteligência Artificial

A IA generativa foi utilizada para:

- Classificação de empresas  
- Geração de atributos estratégicos  
- Criação de insights automatizados  

🔍 A integração foi feita com a API do **Google Gemini**, incluindo:
- Controle de rate limit  
- Retry com backoff exponencial  
- Processamento em batch  

<br>


## 📊 Dashboard

O projeto inclui visualizações analíticas utilizando:

- Matplotlib  
- Seaborn  

### 📈 Gráficos gerados:
- Distribuição por setor  
- Potencial de inovação por empresa  

📌 O objetivo do dashboard é facilitar a interpretação dos dados e apoiar decisões estratégicas.

<br>


## 📂 Estrutura do Projeto

```bash
ai-business-insights-pipeline/
│
├── notebooks/
│   └── etl_ai_business_insights_dashboard.ipynb
│
├── data/
│   ├── raw/
│   ├── processed/
│   │   └── dados_enriquecidos.csv
│   └── outputs/
│       ├── insights.txt
│       └── grafico.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

<br>


## 📁 Arquivos Gerados

### 📊 `dados_enriquecidos.csv`
Dataset final contendo os dados enriquecidos pela IA.

---

### 💡 `insights.txt`
Arquivo com insights estratégicos gerados automaticamente.

---

### 🖼️ `grafico.png`
Visualização do dashboard com os principais indicadores.

<br>


## ⚙️ Tecnologias Utilizadas

- 🐍 Python  
- 📊 Pandas  
- 🤖 Google Generative AI (Gemini)  
- 📈 Matplotlib  
- 🎨 Seaborn  
- ☁️ Google Colab  
- 🔧 Git & GitHub  

<br>


## ☁️ Ambiente de Execução

O projeto foi desenvolvido utilizando o **Google Colab**, garantindo:

- Facilidade de execução  
- Integração com APIs  
- Ambiente pronto para Data Science  

<br>


## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/MarcosWinther/ai-business-insights-pipeline.git
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Configure sua API Key do Gemini

4. Execute o notebook:

```bash
notebooks/etl_ai_business_insights_dashboard.ipynb
```

<br>


## 💡 Diferenciais do Projeto

- ✔️ Pipeline completo (ETL)
- ✔️ Integração com IA generativa
- ✔️ Geração automatizada de insights
- ✔️ Visualização de dados
- ✔️ Estrutura organizada para produção
- ✔️ Controle de erros e rate limit

<br>

## 🧠 Aprendizados

Durante o desenvolvimento, foram aplicados conceitos de:

- Engenharia de Dados
- ETL
- Integração com APIs
- Tratamento de erros
- Visualização de dados
- Versionamento com Git

<br>


## ⭐ Conclusão

Este projeto demonstra como a combinação de Engenharia de Dados + IA Generativa pode transformar dados simples em inteligência de negócio, aproximando soluções técnicas de aplicações reais no mercado.

<br>

## 👨‍💻 Expert

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://avatars.githubusercontent.com/u/44624583?v=4"
    />
    <p>&nbsp&nbsp&nbspMarcos Winther<br>
    &nbsp&nbsp&nbsp
    <a href="https://github.com/MarcosWinther">
    GitHub</a>&nbsp;|&nbsp;
    <a href="https://www.linkedin.com/in/marcoswinthersilva/">LinkedIn</a>
    </p>
</p>
<br/><br/>

---

⌨️ com 💜 por [Marcos Winther](https://github.com/MarcosWinther)
<br>

> ⭐ Se este projeto te ajudou ou foi interessante, considere dar uma estrela no repositório!
