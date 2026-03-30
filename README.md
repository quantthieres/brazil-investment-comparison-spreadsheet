# Comparador de Investimentos — Renda Fixa vs IBOV11

Este projeto consiste em um modelo em Excel para simulação e comparação de investimentos em renda fixa e renda variável (IBOV11), considerando impostos, custos e diferentes premissas de mercado.

---

## Objetivo

Comparar diferentes alternativas de investimento de forma realista, considerando:

- aporte inicial e prazo
- taxas de juros (CDI, Selic e IPCA)
- tributação (IR regressivo e isenções)
- custos (custódia B3 e TER do ETF)

A ideia é avaliar o retorno líquido e comparável entre diferentes ativos.

---

## ⚙️ O que a planilha faz

- simula o crescimento do investimento ao longo do tempo
- calcula valor bruto e valor líquido
- aplica regras reais de tributação no Brasil
- considera custos como custódia e taxa de ETF
- permite alterar premissas facilmente por meio de células editáveis
- gera ranking entre os investimentos

---

## Ativos analisados

- Tesouro Selic
- Tesouro IPCA+
- Tesouro Prefixado
- CDB (% do CDI)
- LCI / LCA (isentos de IR)
- Poupança
- IBOV11 (ETF de renda variável)

---

## 📈 Exemplo

![Comparação de investimentos](./images/Compara%C3%A7%C3%A3o%20de%20Retornos.png)

---

## Interpretação dos resultados

### 1. Impacto da tributação

- O IR reduz significativamente o retorno de produtos tributados, como CDB e Tesouro.
- LCI e LCA, por serem isentas, conseguem competir mesmo com taxas menores.

**Insight:** nem sempre o maior rendimento bruto é o melhor no final.

---

### 2. Importância do cenário de juros

- Com taxas de juros elevadas (CDI alto), a renda fixa tende a performar muito bem.
- Em cenários assim, ela pode competir diretamente com a renda variável.

**Insight:** isso é típico do Brasil em períodos de juros altos.

---

### 3. IBOV11 depende de premissas

- O retorno da renda variável é baseado em uma estimativa, não em uma garantia.
- Pequenas mudanças nessa premissa alteram bastante o resultado final.

**Insight:** diferente da renda fixa, a renda variável não oferece previsibilidade de retorno.

---

### 4. Comparação líquida é essencial

- Comparar investimentos apenas pelo retorno bruto pode levar a conclusões erradas.
- O modelo mostra o impacto real de impostos e custos sobre o resultado final.

**Insight:** a análise correta deve ser feita em termos líquidos.

---

### 5. Tempo e juros compostos

- Quanto maior o prazo, maior o impacto dos juros compostos.
- Pequenas diferenças de taxa se tornam relevantes no longo prazo.

---

## ⚠️ Limitações

- O retorno do IBOV11 é uma estimativa, não uma previsão.
- O modelo não considera volatilidade nem risco de mercado.
- Não incorpora cenários dinâmicos; as taxas são tratadas como constantes.
- Não substitui uma análise completa de investimentos.

---

## Conclusão

O modelo mostra que:

- a renda fixa pode ser altamente competitiva em cenários de juros elevados
- impostos e custos têm impacto relevante no retorno final
- comparações devem ser feitas com base em retorno líquido
- a renda variável depende fortemente das premissas adotadas

---

## ⚠️ Aviso

Esta planilha tem caráter educacional e não constitui recomendação de investimento.
