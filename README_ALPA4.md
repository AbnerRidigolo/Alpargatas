
# 📈 Projeto: Estratégia Anti-Crise com ALPA4 usando Médias Móveis

Este projeto testa uma **estratégia de investimento baseada em Análise Técnica**, utilizando o **cruzamento de médias móveis** no ativo **ALPA4 (Alpargatas S.A)**. O objetivo é avaliar se essa estratégia teria superado o desempenho da ação e do índice Ibovespa entre 2021 e 2025.

---

## 🧠 Desafio

Desenvolver e validar um modelo quantitativo simples que:

- Compra o ativo quando a média móvel curta cruza a longa para cima.
- Vende ou permanece fora do ativo quando ocorre o cruzamento inverso.

> Resultado destacado: +300% contra -90% do ativo, em determinados parâmetros.

---

## 🚀 Tecnologias Utilizadas

- Python 3.x
- [yfinance](https://pypi.org/project/yfinance/) — para extração dos dados históricos da bolsa
- pandas, numpy — para manipulação de dados
- matplotlib, mplcyberpunk — para visualizações
- Jupyter Notebook

---

## ⚙️ Etapas do Projeto

1. **Importação de bibliotecas**
2. **Coleta dos dados históricos do ativo ALPA4 (Yahoo Finance)**
3. **Cálculo das Médias Móveis (curta e longa)**
4. **Geração de sinais de compra e venda**
5. **Cálculo dos retornos diários da ação**
6. **Simulação da estratégia de investimento**
7. **Comparação com desempenho do ativo e do Ibovespa**
8. **Visualização do desempenho acumulado**
9. **Otimização das janelas de médias móveis para melhores resultados**

---

## 💡 Estratégia de Médias Móveis

- **Média Rápida**: 7 dias  
- **Média Lenta**: 40 dias

> A estratégia compra quando a Média Rápida cruza a Média Lenta para cima e vende no cruzamento para baixo.

---

## 📊 Resultados

- A estratégia gerou retornos superiores ao **buy and hold** da própria ALPA4.
- Houve momentos em que **proteger o capital** foi mais vantajoso que manter a ação comprada.
- Testes com otimização de parâmetros sugerem que há **pontos de ajuste finos** que melhoram ainda mais a performance.

---

## 📦 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/SeuUsuario/SeuRepositorio.git
cd SeuRepositorio
```

2. Instale os pacotes necessários:

```bash
pip install -r requirements.txt
```

3. Execute o notebook:

```bash
jupyter notebook aula_1_alpa4_mm.ipynb
```

---

## ✅ Requisitos

Você pode criar um `requirements.txt` com:

```
yfinance==0.2.58
mplcyberpunk
pandas
numpy
matplotlib
```

---

