# 📈 Multi-Agent AI Trading Crew Web App

This project is a web application that simulates a team of specialized AI agents analyzing a stock to identify potential trading opportunities.

## 🚀 Features

*   **Interactive UI:** Enter any stock ticker to begin the analysis.
*   **Multi-Agent System:** Simulates four distinct agents with specific roles:
    *   **Market_Analyst_Agent:** Gathers and processes market data and calculates technical indicators.
    *   **Strategy_Agent:** Analyzes the data to find trade signals based on pre-defined logic.
    *   **Risk_Manager_Agent:** Assesses the signal's risk, calculates position size, and has the power to veto unsafe trades.
    *   **Execution_Agent:** Simulates the final placement of an approved trade order.
*   **Detailed Logging:** See the step-by-step "thinking" process of each agent.

## 🛠️ Technologies Used

*   **Python:** The core programming language.
*   **Streamlit:** For building the interactive web application.
*   **Pandas:** For data manipulation and analysis.
*   **yfinance:** To fetch stock market data from Yahoo Finance.
*   **pandas-ta:** For calculating technical analysis indicators.

## 🏃 How to Run Locally

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/AI-Trading-WebApp.git
    ```
2.  Navigate into the project directory:
    ```bash
    cd AI-Trading-WebApp
    ```
3.  Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
4.  Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```
