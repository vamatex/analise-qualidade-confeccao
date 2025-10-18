# Análise de Qualidade de Produção na Indústria de Confecção

## 🎯 Objetivo do Projeto

Este projeto realiza uma análise exploratória de dados (EDA) a partir de um relatório de produção de uma empresa de confecção. O objetivo principal é identificar padrões de qualidade entre diferentes fornecedores, destacando:
* Os fornecedores com maior volume de entregas por categoria de qualidade (1ª, 2ª e refugo).
* A performance de qualidade de cada fornecedor em termos percentuais.
* Os produtos específicos que apresentam maior incidência de defeitos.

## 🛠️ Ferramentas Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** Pandas (para manipulação de dados), Matplotlib e Seaborn (para visualização de dados).
* **Ambiente:** Jupyter Notebook / Google Colab

## 📂 Estrutura dos Arquivos
* `dados_anonimizados.csv`: O conjunto de dados utilizado na análise, com nomes de fornecedores e produtos substituídos por identificadores genéricos.
* `grafico_01_primeira_qualidade.png`: Gráfico com o Top 10 fornecedores por volume de peças de 1ª qualidade.
* `grafico_02_segunda_qualidade.png`: Gráfico com o Top 10 fornecedores por volume de peças de 2ª qualidade.
* `grafico_03_sacrificio.png`: Gráfico com o Top 10 fornecedores por volume de peças de refugo/sacrifício.
* `grafico_04_produtos_segunda_qualidade.png`: Gráfico detalhado dos 20 produtos com maior incidência de 2ª qualidade.

## 📊 Análise e Insights

### 1. Desempenho dos Fornecedores por Volume
A primeira análise foca em identificar quais fornecedores mais produzem em cada categoria.

**Top 10 Fornecedores por Peças de Primeira Qualidade**
![Gráfico de Primeira Qualidade](https://github.com/vamatex/analise-qualidade-confeccao/blob/main/WhatsApp%20Image%202025-10-18%20at%2019.07.40.jpeg?raw=true)
*Insight: Aqui podemos ver claramente quais parceiros são responsáveis pela maior parte da nossa produção de alta qualidade.*

---

### 2. Análise de Peças com Defeito e Refugo
Identificar os focos de problemas é crucial para a melhoria contínua.

**Top 10 Fornecedores por Peças de Segunda Qualidade**
![Gráfico de Segunda Qualidade](https://github.com/vamatex/analise-qualidade-confeccao/blob/main/WhatsApp%20Image%202025-10-18%20at%2019.08.05.jpeg?raw=true)
*Insight: Este gráfico aponta os fornecedores que mais geram peças de segunda qualidade, indicando uma necessidade de maior atenção no controle de qualidade ou alinhamento técnico.*

**Top 10 Fornecedores por Peças de Sacrifício (Refugo)**
![Gráfico de Sacrifício](grafico_03_sacrificio.png)
*Insight: O volume de refugo representa uma perda direta. Esta visualização ajuda a focar os esforços de redução de desperdício nos parceiros mais críticos.*

---

### 3. Análise Detalhada por Produto
Quais produtos específicos estão falhando mais?

**Top 20 Produtos com Mais Peças de Segunda Qualidade**
![Gráfico de Produtos com Defeito](grafico_04_produtos_segunda_qualidade.png)
*Insight: A análise por produto revela que certos fornecedores podem ter dificuldades com referências específicas. O "Produto 1", por exemplo, é um ponto de atenção para múltiplos fornecedores, sugerindo uma possível complexidade na sua produção.*

## 📈 Conclusão
A análise demonstra como, a partir de um relatório de produção padrão, é possível extrair inteligência acionável. Com estes dados, a gestão de qualidade pode tomar decisões estratégicas, como:
* Realizar auditorias focadas nos fornecedores e produtos mais problemáticos.
* Desenvolver planos de ação conjunta com os parceiros para melhorar a qualidade.
* Reconhecer e fortalecer parcerias com os fornecedores de melhor desempenho.

---
