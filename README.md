# SmartFab — Production Scheduling Optimization

Projeto académico da unidade curricular **Investigação Operacional**  
Universidade do Minho — 2025/2026

Este trabalho consiste na formulação e resolução de um **problema de escalonamento da produção** para uma linha de montagem da SmartFab, com múltiplos módulos IoT, custos de setup, stock e capacidade limitada.

Modelação matemática em **Programação Inteira** e resolução com **LPSolve**.

---

## Objetivo

Determinar o plano ótimo de produção que:
- satisfaça a procura em todos os períodos
- minimize o custo total de:
  - produção
  - armazenamento (stock)
  - reconfiguração da linha

---

## Conteúdo técnico

- Conjuntos, parâmetros e variáveis de decisão
- Formulação matemática completa do modelo:
  - Função objetivo
  - Restrições de stock
  - Restrições de capacidade
  - Restrições de reconfiguração
- Duas variantes do problema analisadas:
  - **Modelo Base** (sem limite de stock)
  - **Modelo com Limites Máximos de Armazenagem**

**Resultados:**
- Custo ótimo (modelo base): **561,21 €**
- Custo ótimo com limite de stock: **575,33 €**
- Trade-off entre eficiência produtiva e restrições logísticas
- Redução do número de setups vs. antecipação de produção ✔️

Fonte: Relatório académico completo :contentReference[oaicite:0]{index=0}

---

## Tecnologias & Ferramentas

- Modelação Matemática → Programação Inteira
- Solver → **LPSolve**
- Linguagem → **Algebraic modeling**
- Análise crítica quantitativa

---

## 📂 Documentos incluídos

