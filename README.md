Multi-Factor Stock Return Modeling – SBI Analysis



This project presents a practical, real-world application of quantitative finance using Python. It focuses on analyzing and predicting stock returns by combining financial concepts with data-driven modeling techniques. Using State Bank of India (SBI) as a case study, the project explores how market movements and technical factors influence individual stock performance.

Instead of relying on a single prediction approach, the project compares multiple models — including a baseline Naive model, a Market regression model, and a Multi-factor regression model. This structured comparison highlights how adding meaningful financial variables improves predictive power and provides deeper insights into stock behavior.

The goal of this project is not just prediction accuracy, but understanding how real-world financial data behaves, how models perform under market uncertainty, and how quantitative methods can support better investment analysis. It is designed as a portfolio-ready case study for aspiring financial analysts and data-driven finance roles.




🎯 Project Objective


Analyze SBI stock performance using historical market data

Compare simple vs advanced prediction models

Understand the impact of market and technical factors

Evaluate model accuracy using statistical metrics




⚙️ Tools & Technologies


Python (Google Colab)

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

Statsmodels





Project Workflow


1️⃣ Data Collection & Preparation

Extracted historical stock and index data programmatically

Calculated daily returns

Created lag-based features

Cleaned and aligned datasets for modeling



2️⃣ Exploratory Data Analysis

Price trend comparison

Return distribution analysis

Volatility insights

Correlation study between stock and indices



3️⃣ Models Implemented


🔹 Naive Model

Predicts next-day return using previous-day return

Used as a baseline benchmark


🔹 Market Model (Single-Factor Regression)

Linear regression using market returns

Measures overall market dependency (beta concept)


🔹 Multiple Regression Model

Multi-factor approach using:

Lagged returns

Trading volume

Market index returns

Designed to improve explanatory power and prediction accuracy




📊 Model Evaluation


All models were compared using standard statistical metrics:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² (Explanatory Power)





📈 Key Insights


The Naive model showed very weak predictive power.

The Market model confirmed that overall market movement influences stock returns.

The Multiple Regression model delivered the best performance.

Multi-factor modeling significantly improved prediction accuracy.

Financial time-series remain noisy, limiting perfect prediction.




💡 Key Learnings


Handling financial time-series data in Python

Feature engineering for stock prediction

Regression modeling and interpretation

Importance of multi-factor approaches in finance

Translating financial theory into practical analytics




🚀 Future Enhancements


Add macroeconomic variables (inflation, interest rates)

Apply ML models (Random Forest, XGBoost)

Explore deep learning models (LSTM)

Build an interactive dashboard

Extend to multi-stock portfolio analysis





🤖 Development Note

This project was built in Google Colab using Python.
GenAI tools were used to accelerate coding and experimentation, while the modeling logic, financial interpretation, and evaluation were done manually.





🙋‍♀️ About Me

I am an aspiring Financial Analyst with a strong interest in finance, analytics, and AI-driven financial modeling.
This project is part of my journey to build practical, real-world finance projects.
