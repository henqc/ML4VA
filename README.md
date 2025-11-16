# ML4VA: Community Policing Data Analysis

A machine learning analysis of Virginia's community policing data. The project includes comprehensive data preprocessing, model training, weight analysis, and visualizations to understand patterns in police stop data. The analysis explores various machine learning models including logistic regression, random forests, gradient boosting, and neural networks to predict outcomes and identify important features in the dataset.

**Dataset Source:** [Virginia Community Policing Data](https://data.virginia.gov/dataset/community-policing-data)

## Repository Structure

```
ML4VA/
├── ml4va.ipynb                    # Main notebook with complete analysis pipeline
├── archive/                        # Intermediate development work
│   ├── data_exploration.ipynb     # Initial data exploration and preprocessing
│   └── model_development.ipynb    # Model training and experimentation
└── README.md                       # This file
```

## Important Notes

### Getting Started

1. **Download the Dataset**: The dataset must be downloaded from the [Virginia Open Data Portal](https://data.virginia.gov/dataset/community-policing-data) and placed in the project directory.

2. **Update File Path**: In `ml4va.ipynb`, update the `pd.read_csv()` line to point to the correct location of your downloaded dataset file.

3. **Main Notebook**: All final work including data preprocessing, model training, weight analysis, and visualizations is contained in `ml4va.ipynb`. This is the primary reference for the complete analysis.

4. **Archive Folder**: The `archive/` folder contains intermediate development work and exploratory notebooks. These are provided for reference but should not be used as the primary source of the analysis.

### Dataset Information

- **Size**: ~3.37 million records with 21 features
- **Features Include**: Stop date, agency name, location, jurisdiction, reason for stop, demographics (race, ethnicity, age, gender), actions taken, violations, searches conducted, use of force, and more
- **Target Variables**: Various outcomes including action taken, use of force, and other policing decisions

### Dependencies

Uses standard data science and machine learning libraries:

- pandas, numpy
- scikit-learn
- matplotlib
- scipy
- tensorflow/keras
