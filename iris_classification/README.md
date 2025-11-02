# Iris Flower Classification - Bioinformatic Analysis

##  Project Overview
A comprehensive bioinformatic analysis of the classic Iris dataset, combining exploratory data analysis with machine learning to classify flower species based on morphological measurements. This project demonstrates the application of data science techniques to biological classification problems.

##  Objectives
- Perform exploratory data analysis on morphological measurements
- Conduct statistical hypothesis testing between species  
- Implement and compare multiple machine learning classifiers
- Identify key morphological features for species discrimination
- Provide biological interpretation of analytical results

##  Dataset
**Source**: UCI Machine Learning Repository (Fisher's Iris Data)  
**Samples**: 150 flowers (3 species × 50 samples each)  
**Features**: 
- Sepal length (cm)
- Sepal width (cm) 
- Petal length (cm)
- Petal width (cm)
- Species (Iris setosa, Iris versicolor, Iris virginica)

##  Project Structure
iris-classification/
├── data/
│ ├── raw/ # Original dataset
├── notebooks/
│ ├── 01_eda_iris.ipynb # Exploratory data analysis
│ └── 02_ml_modeling.ipynb # Machine learning analysis
├── src/ # Reusable Python scripts
├── reports/
│ ├── figures/ # Generated visualizations
│ └── bioinformatic_analysis_report.md
├── requirements.txt # Python dependencies
└── README.md


##  Key Findings from EDA

### Data Quality & Distribution
- Perfect dataset with no missing values or duplicates
- Balanced distribution (50 samples per species)
- Clean data types and reasonable value ranges

### Morphological Patterns  
- **Iris setosa**: Clearly distinct morphology with smaller petals
- **Iris versicolor & virginica**: Some morphological overlap, particularly in sepal measurements
- **Petal measurements**: Show better species discrimination than sepal measurements

### Statistical Significance
- All morphological features show highly significant differences between species (p < 0.001)
- Strong correlation between petal length and width (r = 0.96)
- Petal measurements exhibit the largest effect sizes (F > 1000)

### Visualization Insights
- Box plots reveal clear separation of setosa from other species
- Correlation heatmap shows petal measurements are highly correlated
- Pair plot demonstrates multivariate separation patterns

### Machine Learning Results
- **Best Model**: Support Vector Machine
- **Test Accuracy**: 97% (29/30 test samples correctly classified)
- **Cross-validation Score**: 97.5% ± 2.0% (consistent performance)
- **Top Performing Models**:
  1. Support Vector Machine : 97% accuracy
  2. Gaussian Naive Bayes 97% accuracy
  3. Logistic Regression 93.3% accuracy
  4. K-Nearest Neighbors 93.3% accuracy

### Feature Importance
**Random Forest Feature Importance:**
1. PetalWidthCm: 0.44 
2. PetalLengthCm: 0.43 
3. SepalLengthCm: 0.11 
4. SepalWidthCm: 0.02 

### 📊 Species-Specific Performance
- **Iris-setosa**: 100% accuracy (perfect classification)
- **Iris-versicolor**: 90% accuracy (1 misclassification as virginica)
- **Iris-virginica**: 100% accuracy (perfect classification)


##  Technologies Used
- **Python 3.8+**
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Statistics**: SciPy
- **Notebooks**: Jupyter

## Skills Demonstrated
- Data Analysis: EDA, statistical testing, data visualization

- Machine Learning: Model selection, evaluation, feature importance

- Bioinformatics: Biological data interpretation, taxonomic applications

- Reproducible Research: Complete documentation, version control

## Future Work
- Integration with genetic data for comprehensive analysis

- Expansion to more Iris species and morphological traits

- Development of interactive classification tool

- Application methodology to other plant taxonomic groups
