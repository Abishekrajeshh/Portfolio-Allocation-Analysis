# Portfolio Allocation Analysis

## **Overview**
This project analyzes portfolio allocation strategies by integrating risk datasets, historical stock data, and applying Modern Portfolio Theory (MPT). The analysis optimizes trading strategies and compares results with the S&P 500 index.

---

## **Features**
- **Data Retrieval**: Scrapes stock data from historical sources.
- **Portfolio Optimization**: Applies Modern Portfolio Theory for strategy refinement.
- **Sector Analysis**: Filters and analyzes specific stock sectors.
- **Visualization**: Includes sector distributions, moving averages, and trend insights.
- **Profitability Insights**: Demonstrates a Buy/Sell approach that achieved a 24% profit compared to the S&P 500.

---

## **Project Structure**
```
project-folder/
├── data/              # Raw and processed data files
├── src/               # Python scripts and functions
├── notebooks/         # Jupyter notebooks
├── README.md          # Project overview
├── requirements.txt   # Python dependencies
├── LICENSE            # (Optional) License information
└── portfolio_analysis.md     # Markdown analysis document
```

---

## **Setup and Installation**

### Prerequisites
- Python 3.7+
- Pip (Python package manager)

### Install Required Libraries
```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, manually install:
```bash
pip install pyomo pandas requests yahoo_fin matplotlib seaborn
```

---

## **Usage Instructions**

### Run the Jupyter Notebook
1. Open the notebook:
   ```bash
   jupyter notebook notebooks/Portfolio_Analysis.ipynb
   ```
2. Execute each cell sequentially.

### Key Scripts
- **`fetch_stock_data`**: Retrieves and processes historical stock data.
- **Portfolio Optimization**: Implements Modern Portfolio Theory (MPT) to identify the best allocation.
- **Visualization**: Generates plots for moving averages, risk analysis, and portfolio trends.

---

## **Example Outputs**
- **Profitability Comparison**:
  Achieved a **24% profit** using a Buy/Sell strategy compared to the S&P 500.
- **Visualization**:
  ![Sector Distribution Plot](path/to/sector_distribution.png)

---

## **Contributing**
Contributions are welcome! Please fork this repository and create a pull request with your proposed changes.

---

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## **Acknowledgements**
- Stock data retrieved using historical APIs.
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `pyomo`.
