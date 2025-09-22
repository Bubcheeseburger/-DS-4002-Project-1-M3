# -DS-4002-Project-1-M3
This is the repository for analysis for Project 1 in DS 4002

## Section 1: Software and Platform

### Platform: Google Colab + Jupyter Notebook
### Language: Python 3
### Key Packages:
  - Pandas (data manipulation)
  - Numpy (numerical operation)
  - Scikit-learn (machine learning)
  - Matplotlib, Seaborn (visualization)

### This project was deveopled on MacOS and Windows

## Section 2: File Structure
```
├DS-4002-Project-1-M3/
│
├── DATA/ # Raw and processed data files
│ ├── food.csv # USDA FoodData Central food reference data
│ ├── branded_food.csv # USDA FoodData Central branded foods dataset
│ └── branded_food_clean.csv # Data obtained after running Preprocessing.ipynb, reading to be analyzed
│
├── OUTPUT/ # Generated charts and figures for reporting
│ ├── freq_ingredients.png # Output chart for IngredientPrevalance.ipynb that shows how frequent certain ingredient list lengths ar
│ └── top_ingredients.png # Output chart for Frequency.ipynb that shows how frequent certain ingredients are
│
├── SCRIPTS/ # Jupyter notebooks for analysis
│ ├── Preprocessing.ipynb # Cleans and merges raw CSVs, outputs processed data
│ ├── Frequency.ipynb # Script used to get surface level analysis of data, providing frequency of certain ingredient list lengths
│ └── IngredientPrevalence.ipynb # Script used to get surface level analysis of data, providing frequency of certain ingredients and creating a figure in output
│
├── README.md # Project overview and instructions
└── LICENSE # License file (if applicable)
```


## Section 3: How To Reproduce
