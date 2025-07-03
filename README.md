# Layered Alpha: A Two-Stage Machine Learning Framework for Robust Stock Selection

**Layered Alpha** is a machine learning framework for robust U.S. stock selection, integrating financial metrics and machine learning models. It aims to enhance stock prediction accuracy by combining **financial data** with **machine learning techniques** like **XGBoost**, **Random Forest**, and **Linear Regression**.

## Key Features & Innovation

- **Two-Stage Machine Learning Approach**: Integrates **financial data** (momentum, P/E ratios) in the first stage and refines predictions using machine learning models in the second stage.
  
- **Machine Learning Models**: Utilizes **XGBoost**, **Random Forest**, and **Linear Regression** to predict stock returns and improve model accuracy.

- **Financial Factor Integration**: Combines **financial indicators** and **machine learning** for a comprehensive stock selection approach.

- **Backtesting & Evaluation**: Includes a backtesting module that evaluates model performance through **long-short portfolio strategies** and key metrics like **information ratio (IR)** and **return on investment (ROI)**.

## Project Overview

- **Stage 1: Financial Data Integration** – Integrates key **financial metrics** (e.g., P/E ratio, momentum) to predict stock returns.
- **Stage 2: Model Refinement** – Applies machine learning algorithms like **XGBoost** and **Random Forest** to enhance predictions.

## Project Structure

```
LayeredAlpha/
├── data/ # Raw data and processed financial datasets
├── features/ # Feature engineering scripts to extract relevant factors
├── model/ # Machine learning models and algorithms for stock prediction
├── backtest/ # Scripts for backtesting and performance evaluation
├── notebooks/ # Jupyter notebooks for exploratory analysis and experiments
├── utils/ # Utility functions (data loaders, metrics, helpers)
├── LICENSE
└── README.md
```

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AnAAnnie/LayeredAlpha.git
   cd LayeredAlpha
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. If you prefer, create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   pip install -r requirements.txt

   ```
   
## Citation
If you use this framework in your research, please cite it as follows:

```bibtex
@misc{LayeredAlpha2025,
  title={Layered Alpha: A Two-Stage Machine Learning Framework for Robust Stock Selection},
  author={Qing(Sunny) Luo, Zekun(Johnson) Song},
  year={2025},
  url={https://github.com/AnAAnnie/LayeredAlpha}
}
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Special thanks to the following projects that helped shape Layered Alpha:
- XGBoost
- Random Forest
- Financial Data from FRED
