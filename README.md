# Boston House Price Prediction

A comprehensive data science project analyzing and predicting housing prices in Boston suburbs using machine learning techniques.

## Project Overview

This project aims to analyze and predict housing prices in Boston suburbs using a dataset from the U.S. Census Service. The analysis explores relationships between housing prices and various demographic, economic, and environmental factors.

## Project Structure

```
PROJECT/
├── README.md
├── .gitignore
└── Data/
    ├── Boston.csv                              # Dataset
    ├── Final_Project_Report.docx               # Detailed project report
    ├── Malav_Gajera_Final_Project.ipynb       # Main analysis notebook
    └── requirements.txt                        # Python dependencies
```

## Dataset

The dataset includes 14 attributes:
- **CRIM**: Per capita crime rate by town
- **ZN**: Proportion of residential land zoned for large lots
- **INDUS**: Proportion of non-retail business acreage
- **CHAS**: Charles River dummy variable
- **NOX**: Nitric oxide concentration
- **RM**: Average number of rooms per dwelling
- **AGE**: Proportion of owner-occupied units built before 1940
- **DIS**: Weighted distances to employment centers
- **RAD**: Index of accessibility to radial highways
- **TAX**: Property tax rate per $10,000
- **PTRATIO**: Pupil-teacher ratio by town
- **B**: Proportion of blacks by town
- **LSTAT**: % lower status of the population
- **MEDV**: Median value of owner-occupied homes (target variable)

## Key Findings

- **RM (Average rooms)**: Strongest positive correlation with housing prices (~0.7)
- **LSTAT (Lower status %)**: Strong negative correlation with housing prices (~-0.74)
- **Random Forest model** achieved the best performance with R² = 0.90 after tuning

## Models Implemented

1. **Linear Regression**: R² = 0.76 (baseline)
2. **Decision Tree**: R² = 0.74
3. **Random Forest**: R² = 0.87 (0.90 after tuning)
4. **K-Neighbors**: R² = 0.68

## Installation & Setup

# Clone the repository
git clone https://github.com/yourusername/boston-house-price-prediction.git

# Navigate to project directory
cd MALAV_GAJERA_FINAL_PROJECT

# Install dependencies
pip install -r Data/requirements.txt

# Launch Jupyter Notebook
jupyter notebook Data/Malav_Gajera_Final_Project.ipynb


## Usage

1. **Open the Jupyter Notebook**: `Data/Malav_Gajera_Final_Project.ipynb`
2. **Run all cells** to reproduce the analysis
3. **View the detailed report**: `Data/Final_Project_Report.docx`

## Results

The Random Forest model achieved excellent performance:
- **Training Accuracy**: 98%
- **Testing Accuracy**: 90%
- **R² Score**: 0.90

## Files Description

- **`Data/Boston.csv`**: The Boston housing dataset
- **`Data/Malav_Gajera_Final_Project.ipynb`**: Complete analysis notebook with:
  - Data preprocessing and cleaning
  - Exploratory Data Analysis (EDA)
  - Feature correlation analysis
  - Multiple regression models
  - Model evaluation and comparison
  - Visualization of results
- **`Data/Final_Project_Report.docx`**: Comprehensive project report
- **`Data/requirements.txt`**: Python package dependencies

## Video Demonstration

Watch the project walkthrough: [YouTube Link](https://youtu.be/9LxZ36CVPTM)

## Technologies Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Contact

For questions about this project, please contact me at [malavgajera250@gmail.com]

## License

This project is licensed under the MIT License - see the LICENSE file for details.
