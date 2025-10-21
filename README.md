# Hertzsprung-Russell Star Classification

Machine learning models are used to classify star types using basic features (temperature, luminosity, radius) from an astronomy dataset.  
Data is checked for physical accuracy using the Stefan-Boltzmann law.  
Random Forest and Logistic Regression are compared.  
Random Forest achieves perfect accuracy; LR underfits on non-linear regions.  
All code, steps, and model outputs are reproducible.  

- Final notebook: `/notebooks/Hertzsprung-Russell-Diagram.ipynb`
- Sample data: `/data/stars.csv`
- See `/figures/` for main visualizations.

## How to Run

1. Clone this repo:
   git clone [your-repo-url]

2. Open `/notebooks/Hertzsprung-Russell-Diagram.ipynb` in Jupyter, Colab, or VS Code.

3. Make sure `/data/stars.csv` is present.

4. Run cells top to bottom.  
   All dependencies: pandas, numpy, matplotlib, seaborn, scikit-learn.

No setup script, no CLI, no hidden requirements. Notebook uses standard packages, no custom code.

