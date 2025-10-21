# Hertzsprung-Russell Star Classification

Machine learning models are used to classify star types using basic features (temperature, luminosity, radius) from an astronomy dataset.  
Data is checked for physical accuracy using the Stefan-Boltzmann law.  
Random Forest and Logistic Regression are compared.  
Random Forest achieves perfect accuracy; LR underfits on non-linear regions.  
All code, steps, and model outputs are reproducible.  

- Final notebook: `/notebooks/Hertzsprung-Russell-Diagram.ipynb`
- Sample data: `/data/stars.csv`
- See `/figures/` for main visualizations.

## Data Source

The dataset used for this project comes from:
https://www.kaggle.com/datasets/deepu1109/star-dataset/data

## How to Run

1. Clone this repo:
   git clone [your-repo-url]

2. Open `/notebooks/Hertzsprung-Russell-Diagram.ipynb` in Jupyter, Colab, or VS Code.

3. Make sure `/data/stars.csv` is present.

4. Run cells top to bottom.  
   All dependencies: pandas, numpy, matplotlib, seaborn, scikit-learn.

No setup script, no CLI, no hidden requirements. Notebook uses standard packages, no custom code.

--------------------------------------------------------------------
- `hr_true.png`  
  Shows the actual star types on the Hertzsprung-Russell diagram. This is the real class distribution in the dataset.

- `hr_rf.png`  
  Random Forest predictions shown on the HR diagram. Nonlinear boundary, fewer mistakes, classes are split correctly.

- `hr_lr.png`  
  Logistic Regression predictions on the same diagram. Only linear boundaries; some classes get mixed up.

- `hr_compare.png`  
  Side-by-side comparison: Random Forest vs Logistic Regression. Direct view of how each model classifies stars in feature space.

