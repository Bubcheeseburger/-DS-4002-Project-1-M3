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
│ ├── top_ingredients.png # Output chart for Frequency.ipynb that shows how frequent certain ingredients are
│ ├── confusion_matrix_counts.png  # Output chart from MI3_Methodology.ipynb
│ └── confusion_matrix_normalized.png # Output chart from MI3_Methodology.ipynb
│
├── SCRIPTS/ # Jupyter notebooks for analysis
│ ├── Preprocessing.ipynb # Cleans and merges raw CSVs, outputs processed data
│ ├── Frequency.ipynb # Script used to get surface level analysis of data, providing frequency of certain ingredient list lengths
│ ├── IngredientPrevalence.ipynb # Script used to get surface level analysis of data, providing frequency of certain ingredients and creating a figure in output
│ └── MI3_Methodology.ipynb # This is the main script that scores products, labels them as healthy, unhealthy, or intermediate, and then teaches a model to recognize the patterns in ingredients to score things itself
│
├── README.md # Project overview and instructions
└── LICENSE # License file
```


## Section 3: How To Reproduce

### 1. Set Up the Project Structure
Clone this repository and ensure your local folder structure matches the layout shown in **Section 2** of this README:

### 2.  Run Preprocessing
Open and run the notebook:
This notebook will:
- Load and clean the raw USDA data (`food.csv` and `branded_food.csv`).
- Merge and standardize ingredient information.
- Output a new, processed dataset:  
  **`DATA/processed/branded_food_clean.csv`**

### 3. Train & Evaluate the Classification Model
Next, open and run:
This notebook will:
- Apply labeling functions to classify foods as **healthy**, **intermediate**, or **unhealthy** based solely on their ingredient lists.
- Train a machine learning model to predict these labels automatically.
- Output final evaluation metrics, including accuracy, F1-score, and confusion matrices.

