# Electricity Consumption & Churn Analysis

A comprehensive data analysis project investigating electricity consumption patterns and customer churn trends from 2000-2008.

## 📋 Project Overview

This project aims to analyze historical electricity consumption data and understand factors contributing to customer churn. The analysis pipeline includes data cleaning, exploratory data analysis (EDA), churn definition logic, and key performance indicators (KPIs).

## 📁 Project Structure

```
├── README.md                          # Project documentation
├── requirements.txt                   # Python dependencies
├── data/
│   ├── raw/
│   │   └── ELECTRICITY_SOLD_TO_ULTIMATE_CONSUMERS.xls
│   └── processed/
│       └── datafile.csv
└── notebooks/
    ├── 01_problem_understanding.ipynb              # Data loading & initial exploration
    ├── 02_data_cleaning_preprocessing.ipynb        # Data cleaning pipeline
    ├── 03_churn_definition_logic.ipynb             # Churn definition & categorization
    ├── 04_exploratory_data_analysis.ipynb          # EDA & visualizations
    ├── 05_insights_and_kpis.ipynb                  # KPIs & business insights
    └── data/processed/
        └── electricity_consumption_2000_2008.csv   # Processed data for analysis
```

## 📊 Data Sources

- **Raw Data**: `ELECTRICITY_SOLD_TO_ULTIMATE_CONSUMERS.xls`
  - Time period: 2000-2008 (8 years)
  - Source: Electricity consumption records
  - Format: Excel (.xls)

- **Processed Data**: Cleaned and transformed CSV files ready for analysis

## 🔍 Notebooks

### 1. **Problem Understanding** (`01_problem_understanding.ipynb`)
- Load Excel data into pandas DataFrame
- Explore data structure and sheets
- Extract relevant columns (Year, Total Electricity Consumption)
- Initial data validation
- Export cleaned data to CSV

### 2. **Data Cleaning & Preprocessing** (`02_data_cleaning_preprocessing.ipynb`)
- Handle missing values
- Data type conversions
- Outlier detection and treatment
- Feature engineering

### 3. **Churn Definition Logic** (`03_churn_definition_logic.ipynb`)
- Define churn metrics
- Categorize customers based on consumption patterns
- Create churn indicators

### 4. **Exploratory Data Analysis** (`04_exploratory_data_analysis.ipynb`)
- Statistical summaries
- Visualizations of consumption trends
- Distribution analysis
- Correlation analysis

### 5. **Insights & KPIs** (`05_insights_and_kpis.ipynb`)
- Key performance indicators
- Business insights
- Recommendations
- Summary dashboards

## 🚀 Getting Started

### Prerequisites
- Python 3.12+
- pip

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sojwal27/Electricity_consumption_churn_analysis.git
   cd Electricity_consumption_churn_analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Run notebooks in order**
   - Start with `01_problem_understanding.ipynb`
   - Follow the sequence through `05_insights_and_kpis.ipynb`

## 📦 Dependencies

All required packages are listed in `requirements.txt`:
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `plotly` - Interactive visualizations
- `xlrd` - Excel file support
- `jupyter` - Notebook environment

Install all dependencies:
```bash
pip install -r requirements.txt
```

## 📈 Key Findings

*To be updated after analysis completion*


## 📈 PowerBi Dashboard

<img width="649" height="369" alt="Screenshot 2026-01-07 163128" src="https://github.com/user-attachments/assets/ea2696a7-0c64-4d2c-9a57-8b5cd42a2b62" />


## 🔄 Workflow

1. **Load & Validate**: Extract data from Excel files
2. **Clean & Process**: Handle missing values and transformations
3. **Define Churn**: Create churn metrics and categories
4. **Explore & Visualize**: Generate insights through EDA
5. **Report KPIs**: Document findings and recommendations

## 📝 Notes

- All data processing is documented in individual notebooks
- Each notebook is self-contained and can be executed independently
- Processed data is cached in CSV format for faster analysis
- All visualizations are interactive (Plotly)

## 👤 Author

Sojwal27

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📧 Contact & Support

For questions or issues, please open a GitHub issue or contact the project maintainer.
