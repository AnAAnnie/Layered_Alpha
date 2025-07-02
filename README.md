# Layered Alpha: A Two-Stage Machine Learning Framework for Robust Stock Selection

**Layered Alpha** is a cutting-edge machine learning framework that integrates **macroeconomic factors** with **traditional financial metrics** for stock selection. Unlike conventional models that only rely on historical stock data, **Layered Alpha** incorporates economic signals such as **GDP growth**, **CPI**, and **unemployment rate** to predict U.S. equity returns more robustly. This framework aims to bridge the gap between macroeconomic insights and micro-level stock prediction, improving model accuracy and performance.

## Key Features & Innovation

- **Two-Stage Machine Learning Approach**: The framework consists of two key stages. The first stage integrates **macroeconomic factors** into a model that generates predictive signals. The second stage uses **financial data** (like momentum, P/E ratio) to further refine stock selection.
  
- **Machine Learning Models**: The project uses **XGBoost**, **Random Forest**, and **Linear Regression** for predicting stock returns. The framework combines **time-series forecasting** for macroeconomic indicators and traditional technical indicators to enhance stock prediction.

- **Macro-Financial Integration**: This is the first implementation to seamlessly integrate **macroeconomic indicators** with traditional **financial factors** in the stock prediction model, offering a comprehensive, holistic approach to equity selection.

- **Backtesting & Evaluation**: The framework includes a comprehensive backtesting module that evaluates model performance through a **long-short portfolio strategy** and measures key performance metrics such as **information ratio (IR)** and **return on investment (ROI)**.

## Project Overview

- **Stage 1: Macro Factor Integration** – Integrates key **macroeconomic factors** (e.g., GDP, CPI, Interest rates) to predict potential movements in U.S. equities.
- **Stage 2: Financial Factor Refinement** – Applies **financial metrics** (P/E, momentum) to further enhance predictions, using machine learning algorithms like **XGBoost** and **Random Forest**.
  
This dual-layer methodology allows the model to factor in external economic conditions, making predictions more resilient to market changes.

## Project Structure
```
LayeredAlpha/
├── data/ # Raw data and processed datasets (macroeconomic & financial data)
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
- Macroeconomic Data from FRED
