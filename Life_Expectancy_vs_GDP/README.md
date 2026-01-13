## Project Overview
This project analyzes the relationship between Gross Domestic Product (GDP) and Life Expectancy across six countries using data from WHO and World Bank sources.

## Dataset
The analysis uses `data/all_data.csv` containing:
- **Country**: Name of the country
- **Year**: Year of observation
- **GDP**: Gross Domestic Product in US dollars
- **Life expectancy at birth (years)**: Average lifespan at birth

## Countries Analyzed
- Chile
- China
- Germany
- Mexico
- United States
- Zimbabwe

## Time Period
2000-2015

## Project Structure
Life_Expectancy_vs_GDP/

├── data/

│ └── all_data.csv # Source data
├── notebooks/
│ └── life_expectancy_gdp.ipynb # Main analysis notebook
├── src/ # Source code (optional)
├── reports/ # Generated reports (optional)
├── requirements.txt # Python dependencies
├── .gitignore # Git ignore rules
└── README.md # This file


## Analysis Components
1. **Data Exploration**: Understanding dataset structure
2. **Data Cleaning**: Handling missing/invalid values
3. **Correlation Analysis**: GDP vs Life Expectancy relationship
4. **Visualization**: Scatter plots, time series, comparisons
5. **Statistical Analysis**: Rankings, growth rates, insights

## Key Questions
- Is there a correlation between GDP and Life Expectancy?
- How has this relationship changed over time?
- Which countries show the strongest/weakest correlation?
- What are the growth patterns for each country?

## How to Run
```bash
# Clone the repository
git clone https://github.com/carlesalce/portfolio_projects.git
cd portfolio_projects/Life_Expectancy_vs_GDP

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter notebook
jupyter notebook notebooks/life_expectancy_gdp.ipynb
