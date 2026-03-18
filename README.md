# Análise de Vulnerabilidade Global: World Risk Index

Este repositório contém o desenvolvimento de uma análise exploratória de dados (EDA) baseada no dataset **World Risk Index**. O estudo foi realizado como parte das atividades da disciplina de **Laboratório de Inovação e Automação 1 (LIA 1)**, com foco em identificar padrões globais de risco e vulnerabilidade a desastres naturais.

## Objetivos do Estudo

O projeto visa aplicar técnicas de Ciência de Dados para investigar os componentes internos do índice de risco global, buscando responder às seguintes questões de pesquisa:

1. **Relação Risco vs. Exposição:** Verificar se países com alta exposição a eventos naturais apresentam, necessariamente, o maior índice de risco final.
2. **Capacidade de Resposta:** Identificar as 10 nações com maior déficit de resposta e o impacto direto dessa métrica no ranking global.
3. **Análise Regional de Suscetibilidade:** Identificar médias regionais de vulnerabilidade e detecção de *outliers* geográficos.
4. **Correlação de Fatores:** Determinar qual variável interna (Suscetibilidade, Falta de Capacidade de Resposta ou Falta de Adaptação) possui a correlação estatística mais forte com o Índice de Risco.

## Tecnologias Utilizadas

* **Linguagem:** Python 3.14
* **Manipulação de Dados:** Pandas e NumPy
* **Visualização de Dados:** Plotly (escolhida pela capacidade de exploração interativa e identificação precisa de amostras via *hover*)
* **Ambiente de Desenvolvimento:** Jupyter Notebook

## Estrutura do Projeto

* `Natural_disaster.ipynb`: Notebook contendo o ciclo completo de dados (limpeza, tratamento de valores ausentes, análise estatística e visualização).
* `world_risk_index.csv`: Base de dados utilizada para as análises.
* `README.md`: Documentação técnica do projeto.

## Metodologia Aplicada

1. **Tratamento de Dados:** Limpeza de ruídos e normalização de tipos de dados para garantir a integridade da análise.
2. **Imputação de Valores:** Utilização de medianas para o preenchimento de dados ausentes, preservando a distribuição estatística das variáveis.
3. **Análise Estatística:** Cálculo de matrizes de correlação e identificação de *outliers* globais.
4. **Visualização Interativa:** Implementação de gráficos dinâmicos para facilitar a análise granular por país e região, permitindo a inspeção direta de valores específicos.

---

### Autor
**Abner Gabriel Monteiro Tavares** Estudante de Engenharia de Computação - Universidade Federal de Goiás (UFG)
