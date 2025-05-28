# <div align="center"> Análise Alura Store - Challenge
</div>

<div align="center"><a target="_blank" href="https://colab.research.google.com/github/vivianebatista92/alura_store_challenge/blob/main/AluraStoreBr.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a></div>  

> ℹ️ **NOTE:** Análise desenvolvida para a formação de Data Science do programa [ONE - Oracle Next Educacion](https://www.oracle.com/br/education/oracle-next-education/) realizada na plataforma [Alura](https://www.alura.com.br/).

## 🎯 Objetivo do Projeto

Avaliar o desempenho das quatro lojas da empresa com base em três indicadores-chave:
- **Faturamento Total**
- **Avaliação Média dos Clientes**
- **Frete Médio**

E com isso, indicar qual loja apresenta menor viabilidade operacional e deve ser considerada para **venda**.

---

## 📂 Bases de Dados

- [Base de Dados das Lojas](https://github.com/alura-es-cursos/challenge1-data-science/tree/main/base-de-dados-challenge-1)

## 🔧 Ferramenta e Linguagem

![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

---

## ✏️ Atividades Realizadas

|   **Atividades** |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <li> Importar os dados para o Google Colab </li> |
 | <li> União das lojas para melhor análise </li>|
 | <li> Entendendo todos os dados </li>|
 | <li> Criação das métricas </li>|
 | <li> Análise por gráficos </li>|
 | <li> Estruturação do relatório </li>|

---
 
 ## 📈 Métricas Realizadas

|   **Métricas** |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <li> Faturamento total de cada loja </li> |
 | <li> Categorias mais populares </li>|
 | <li> Média de avaliação dos clientes </li>|
 | <li> Produtos mais vendidos </li>|
 | <li> Produtos menos vendidos </li>|
 | <li> Custo médio do frete </li>|

---

 ## 📊 Resumo dos Indicadores por Loja

| Critério        | Loja 1           | Loja 2           | Loja 3           | Loja 4           |
|-----------------|------------------|------------------|------------------|------------------|
| **Faturamento** | ✅ R$ 1.534.509,12 | ✅ R$ 1.488.459,06 | ✅ R$ 1.464.025,03 | ❌ R$ 1.384.497,58 |
| **Avaliação**   | ❌ 3.98           | ✅ 4.04           | ✅ **4.05**       | ✅ 4.00           |
| **Frete Médio** | ❌ R$ 34,69       | ✅ R$ 33,62       | ✅ R$ 33,07       | ✅ **R$ 31,28**   |

---

## 🧠 Análise Técnica

#### 📌 Faturamento
- A **Loja 4** tem o menor faturamento, com uma diferença de aproximadamente **R$ 150 mil a menos que a Loja 1**.

#### 📌 Avaliação dos Clientes
- A **Loja 4** possui avaliação média de **4.00**, **inferior às Lojas 2 (4.04) e 3 (4.05)**.

#### 📌 Frete Médio
- A **Loja 4** apresenta **o menor custo logístico**, mas esse diferencial **não se reflete em desempenho geral**.

---

## ⚖️ Balanço Estratégico

| Loja     | Pontos Fortes                    | Pontos Fracos                       |
|----------|----------------------------------|-------------------------------------|
| **Loja 1** | Maior faturamento                | Pior avaliação                      |
| **Loja 2** | Boa avaliação e frete equilibrado | Faturamento inferior à Loja 1      |
| **Loja 3** | Melhor avaliação geral           | Faturamento inferior às Lojas 1 e 2 |
| **Loja 4** | Menor custo de frete             | Menor faturamento, avaliação média |

---

## ✅ Conclusão e Recomendação

**Recomendação Final**: **Vender a Loja 4**

- A Loja 4 apresenta **menor retorno financeiro**.
- **Não lidera em nenhum critério estratégico** de forma isolada.
- O **frete mais barato não compensa o desempenho mediano em avaliação e fraco em faturamento**.

---
