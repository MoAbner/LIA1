**English** | [Português](README.pt-BR.md)

# World Risk Index · Exploratory data analysis

An exploratory analysis of natural-disaster risk indicators, developed as part of the LIA1 coursework. The study uses Python and interactive visualizations to investigate exposure, vulnerability and response capacity across countries.

## Questions explored

- How do risk and exposure relate?
- How does response capacity compare across selected countries?
- How do susceptibility distributions vary between regions?
- Which indicators are correlated, and where do outliers appear?

## Approach

Data cleaning and type conversion, missing-value treatment using medians, descriptive statistics, correlation analysis and Plotly visualizations. Correlations describe patterns in the dataset; they do not establish causation.

**Tools:** Python · pandas · NumPy · Plotly · Jupyter Notebook.

## Open the analysis

See [Abner's submitted notebook](Entregas%20-%20Abner%20Gabriel/Natural_disaster.ipynb). The repository also contains other coursework notebooks and a root-level `Natural_disaster.ipynb`.

```bash
git clone https://github.com/MoAbner/LIA1.git
cd LIA1
python -m pip install jupyter pandas numpy plotly
python -m notebook
```

Open the desired notebook, check its data-loading cell and provide the World Risk Index CSV at the path it expects before running cells in order. The original documentation refers to `world_risk_index.csv`; this README does not bundle or create that dataset.

## Author

Abner Gabriel Monteiro Tavares · Computer Engineering, UFG.
