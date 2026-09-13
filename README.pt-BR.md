[English](README.md) | **Português**

# World Risk Index · Exploratory data analysis

Uma análise exploratória de indicadores de risco de desastres naturais, desenvolvida nas atividades de LIA1. O estudo usa Python e visualizações interativas para investigar exposição, vulnerabilidade e capacidade de resposta entre países.

## Perguntas exploradas

- Como risco e exposição se relacionam?
- Como a capacidade de resposta se compara entre países selecionados?
- Como as distribuições de suscetibilidade variam entre regiões?
- Quais indicadores são correlacionados e onde aparecem valores discrepantes?

## Abordagem

Limpeza e conversão de tipos, tratamento de valores ausentes por medianas, estatística descritiva, análise de correlação e visualizações com Plotly. As correlações descrevem padrões no dataset; não estabelecem causalidade.

**Ferramentas:** Python · pandas · NumPy · Plotly · Jupyter Notebook.

## Abrir a análise

Consulte o [notebook entregue por Abner](Entregas%20-%20Abner%20Gabriel/Natural_disaster.ipynb). O repositório também contém outros notebooks das atividades e um `Natural_disaster.ipynb` na raiz.

```bash
git clone https://github.com/MoAbner/LIA1.git
cd LIA1
python -m pip install jupyter pandas numpy plotly
python -m notebook
```

Abra o notebook desejado, confira a célula de carregamento de dados e disponibilize o CSV do World Risk Index no caminho esperado antes de executar as células em ordem. A documentação original menciona `world_risk_index.csv`; este README não inclui nem gera esse dataset.

## Autor

Abner Gabriel Monteiro Tavares · Engenharia de Computação, UFG.
