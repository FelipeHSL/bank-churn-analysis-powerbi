<div align="center">
  <a href="#english-version">🇺🇸 English Version</a> | <a href="#versao-em-portugues">🇧🇷 Versão em Português</a>
</div>

---

<a name="english-version"></a>
# 🏦 Bank Customer Churn Analysis — Power BI

[![Live Dashboard](https://shields.io)](https://app.powerbi.com/view?r=eyJrIjoiNjg5YzkyZWQtZjI2ZS00ZGM0LTkyMDUtNTE1M2U4ZGE0YjlkIiwidCI6ImYyOWU0MDQ5LTM2YjctNDIxMC04NDhmLWE2YTYxMWI5M2FjZCJ9)

## 📋 Project Overview
This end-to-end Business Intelligence project analyzes customer attrition (churn) across a banking institution's customer base. The primary goal is to identify behavioral patterns, demographic profiles, and product-related triggers that lead clients to close their accounts, enabling data-driven retention strategies.

### 📊 Dashboard Preview
![Bank Churn Dashboard](images/dashboard_churn.png)

> 🔗 **[Click here to explore the interactive live dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjg5YzkyZWQtZjI2ZS00ZGM0LTkyMDUtNTE1M2U4ZGE0YjlkIiwidCI6ImYyOWU0MDQ5LTM2YjctNDIxMC04NDhmLWE2YTYxMWI5M2FjZCJ9)**

---

## 💡 Key Business Insights
* **Overall Attrition & Financial Impact:** Out of **10,000** analyzed customers, **2,037** churned, representing a **20.37%** churn rate and a total lost balance of **$185.59M**.
* **Critical Age Group:** Customers aged **41 to 50** represent the highest volume of churn (**788 clients**), followed by the **31 to 40** age bracket (**538 clients**).
* **Product Overload Risk:** While customers with **2 products** show the highest retention (only **7.58%** churn), clients holding **3 or 4 products** experience critical churn rates of **82.71%** and **100.00%**, respectively—indicating potential cross-selling friction or poor product fit.
* **Geographic Concentration:** **Germany** stands out on the map with a disproportionately high churn concentration compared to France and Spain.
* **Credit Card Ownership:** Customers without a bank credit card churn at nearly double the rate (**26.85%**) of cardholders (**14.27%**).

---

## 🛠️ Tools & Techniques Applied
* **Power Query (ETL):** Data cleaning, type standardization, and creation of custom age brackets.
* **Data Modeling & DAX:** Development of dynamic measures for total customers, churn count, churn rate (%), and lost account balance.
* **Data Storytelling & UI Design:** Custom dark-mode canvas layout designed in **PowerPoint** (1920x1080px) using a high-contrast emerald and coral alert palette to guide executive decision-making.

---

## 📂 Repository Structure
* `data/`: Raw dataset used for the analysis.
* `dashboard/`: Native Power BI file (`.pbix`).
* `images/`: High-resolution dashboard screenshots.

---
---

<a name="versao-em-portugues"></a>
# 🏦 Análise de Churn Bancário — Power BI

[![Dashboard Interativo](https://shields.io)](https://app.powerbi.com/view?r=eyJrIjoiNjg5YzkyZWQtZjI2ZS00ZGM0LTkyMDUtNTE1M2U4ZGE0YjlkIiwidCI6ImYyOWU0MDQ5LTM2YjctNDIxMC04NDhmLWE2YTYxMWI5M2FjZCJ9)

## 📋 Visão Geral do Projeto
Este projeto de Business Intelligence de ponta a ponta analisa a evasão de clientes (*churn*) em uma instituição bancária. O objetivo principal é identificar padrões comportamentais, perfis demográficos e gatilhos relacionados aos produtos contratados que levam os clientes a encerrarem suas contas, fornecendo insumos para estratégias de retenção baseadas em dados.

### 📊 Visualização do Dashboard
![Dashboard Análise de Churn](images/dashboard_churn.png)

> 🔗 **[Clique aqui para explorar o dashboard interativo ao vivo](https://app.powerbi.com/view?r=eyJrIjoiNjg5YzkyZWQtZjI2ZS00ZGM0LTkyMDUtNTE1M2U4ZGE0YjlkIiwidCI6ImYyOWU0MDQ5LTM2YjctNDIxMC04NDhmLWE2YTYxMWI5M2FjZCJ9)**

---

## 💡 Principais Insights de Negócio
* **Evasão Geral e Impacto Financeiro:** De um total de **10 mil** clientes analisados, **2.037** encerraram suas contas, representando uma taxa de churn de **20,37%** e um saldo perdido acumulado de **185,59 Milhões**.
* **Faixa Etária Crítica:** Clientes entre **41 e 50 anos** concentram o maior volume absoluto de cancelamentos (**788 clientes**), seguidos pela faixa de **31 a 40 anos** (**538 clientes**).
* **Risco de Sobrecarga de Produtos:** Enquanto clientes com **2 produtos** apresentam a maior retenção (apenas **7,58%** de churn), clientes com **3 ou 4 produtos** atingem taxas alarmantes de **82,71%** e **100,00%**, respectivamente — sinalizando possível atrito na venda cruzada (*cross-selling*) ou inadequação dos pacotes.
* **Concentração Geográfica:** A **Alemanha** destaca-se no mapa com uma concentração desproporcional de evasão em comparação à França e à Espanha.
* **Posse de Cartão de Crédito:** Clientes sem cartão de crédito apresentam quase o dobro da taxa de cancelamento (**26,85%**) em relação aos que possuem o cartão (**14,27%**).

---

## 🛠️ Ferramentas e Técnicas Aplicadas
* **Power Query (ETL):** Limpeza de dados, padronização de tipos e criação de faixas etárias personalizadas.
* **Modelagem de Dados e DAX:** Criação de medidas dinâmicas para total de clientes, volume de evasão, taxa de churn (%) e saldo financeiro perdido.
* **Storytelling de Dados e Design UI:** Layout customizado em *dark mode* desenhado no **PowerPoint** (1920x1080px), utilizando contraste entre verde esmeralda e vermelho coral para destacar alertas críticos e facilitar a leitura executiva.

---

## 📂 Estrutura do Repositório
* `data/`: Base de dados bruta utilizada na análise.
* `dashboard/`: Arquivo original do Power BI (`.pbix`).
* `images/`: Capturas de tela do painel em alta resolução.
