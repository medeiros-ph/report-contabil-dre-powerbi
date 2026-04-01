# 📊 Report Contábil (DRE) | Power BI

Projeto desenvolvido com o objetivo de representar a Demonstração do Resultado do Exercício (DRE) em formato de dashboard interativo no Power BI, permitindo análise financeira estruturada e geração de insights de negócio.

---

## 🚀 Objetivo

Construir um relatório contábil dinâmico que permita analisar o desempenho financeiro de uma empresa, considerando:

- Receita Bruta e Receita Líquida  
- Custos (CMV / CPV / CSP)  
- Despesas Operacionais  
- Resultado Operacional  
- Lucro Líquido  

---

## 📷 Preview do Dashboard

![Preview](/imagens/preview.png)

---

## 🧩 Estrutura da DRE

A DRE foi estruturada seguindo o modelo contábil tradicional:

- Receita Bruta  
- (-) Deduções  
- = Receita Líquida  
- (-) Custos  
- = Lucro Bruto  
- (-) Despesas Operacionais  
- = Resultado Operacional  
- (-) Impostos  
- = Lucro Líquido  

---

## 🧠 Modelagem de Dados

O modelo foi desenvolvido com base em boas práticas de BI, utilizando separação entre fato e dimensões.

### 🔹 Tabela Fato
- `f_lancamentos`
  - data  
  - valor  
  - conta  

### 🔹 Tabelas Dimensão
- `d_plano_contas` → estrutura hierárquica contábil  
- `d_calendario` → suporte a análises temporais  

---

## 📊 Principais Métricas

- Receita Líquida  
- Lucro Bruto  
- Resultado Operacional  
- Lucro Líquido  
- Margem de Lucro (%)  

---

## ⚙️ Tratamento e Preparação dos Dados

- Estruturação do plano de contas  
- Classificação contábil das movimentações  
- Padronização de dados  
- Criação de tabela calendário  
- Modelagem relacional no Power BI  

---

## 🛠️ Tecnologias Utilizadas

- Power BI  
- Excel  
- DAX (Data Analysis Expressions)  

---

## 📂 Estrutura do Projeto

```bash
report-contabil-dre-powerbi/
│
├── assets/
│   └── backgrounds/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── pbix/
│   └── dre_dashboard.pbix
│
├── images/
│   └── preview.png
│
├── docs/
│   └── dre_structure.md
│
├── README.md
├── data_dictionary.md
└── .gitignore
```

---

## 📊 Fonte dos Dados

Os dados utilizados neste projeto são simulados, com base em estruturas reais de relatórios contábeis, sendo utilizados exclusivamente para fins de estudo e portfólio.

---

## 📈 Possíveis Evoluções
Comparação entre períodos (Ano vs Ano)
Análise de margem por categoria
Integração com banco de dados
Automatização de carga de dados (ETL)
Publicação no Power BI Service

---

## 👨‍💻 Autor

**Raphael Medeiros**  
📍 Rio de Janeiro | RJ

🔗 LinkedIn: [https://www.linkedin.com/in/raphael-s-medeiros/]

---

## ⭐ Sobre o Projeto

Este projeto foi desenvolvido com foco em Business Intelligence e análise financeira, aplicando conceitos de modelagem de dados, contabilidade e visualização para suporte à tomada de decisão.