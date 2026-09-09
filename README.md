# 📚 BookVerse Analytics - Dashboard de Análise de Acervo e Vendas

![Power BI Dashboard](BookVerse%20Analytics.png)

## 📌 Visão Geral do Projeto
Este projeto foi desenvolvido como um estudo de caso analítico para a empresa fictícia **BookVerse Analytics**. 

O objetivo do relatório é fornecer uma visão clara sobre o acervo de livros, permitindo acompanhar métricas de preço médio, volumetria de catálogo, distribuição por gêneros e filtragem de lançamentos versus títulos clássicos.

---

## 🎯 Métricas Chave
* **Total de Livros Analisados:** 20 títulos.
* **Preço Médio:** $23,64.
* **Segmentação por Categoria:** Classificação dinâmica entre livros "Recent" (publicados após 2015) vs. "Classic".
* **Interatividade:** Segmentação por gênero e filtros cruzados aplicados a todos os visuais.

---

## 🛠️ Tecnologias & Habilidades Aplicadas
* **Power BI Desktop:** Construção do modelo de dados, visuais e navegação.
* **DAX (Data Analysis Expressions):** Criação de medidas agregadas e colunas calculadas.
* **Power Query (ETL):** Limpeza, conversão e tratamento de tipos de dados.
* **UI/UX Design:** Desenvolvimento de layout escuro (*Dark Mode*) com foco em contraste e conforto visual.

---

## 📐 Regras de Negócio & Fórmulas DAX

### 1. Medidas
* **Preço Médio:**
```dax
Preço Médio = AVERAGE('Copy of Books'[Price])
