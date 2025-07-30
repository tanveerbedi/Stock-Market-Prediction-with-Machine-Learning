# 📊 Stock Price Prediction Web App

## 🌟 Introduction

Accurate stock price prediction has become a cornerstone for financial success in today’s dynamic markets. This project leverages cutting-edge deep learning techniques to forecast the closing prices of publicly traded stocks. With a user-friendly web interface, it empowers investors, data enthusiasts, and analysts to make better-informed decisions using advanced forecasting models.

Our solution goes beyond simple trendlines—it dynamically visualizes real-time data, processes it through trained neural networks, and outputs future stock trends. Built using modern Python frameworks, the app is lightweight, interactive, and extensible.

---

## 🔍 Overview

The Stock Price Prediction Web App provides users with the ability to:

* Select a stock symbol
* Fetch historical data in real-time using Yahoo Finance APIs
* Visualize stock trends through interactive plots
* Predict future prices using LSTM-based deep learning models

It is designed to be simple, intuitive, and effective for both novice and experienced users in the finance and data science communities.

---

## 🎯 Project Aim

The primary aim of this project is to bridge the gap between real-time stock market data and predictive analytics by leveraging machine learning models. The goal is to empower users, investors, and analysts with a dynamic tool that allows them to:

* Forecast stock trends based on recent data.
* Make informed decisions with the help of algorithmically generated future price predictions.
* Access a centralized platform for stock analysis and visualization without requiring prior financial or programming expertise.

By providing a functional and interactive user interface, this project demonstrates how web technologies and data science can come together to solve real-world forecasting problems.

---

## 🌐 Real-World Applications

* 📈 **Retail Traders**: Helps casual investors make data-backed decisions.
* 🧠 **Quantitative Researchers**: A sandbox for testing new forecasting models.
* 🏦 **Financial Institutions**: Can be expanded to integrate into decision-making pipelines.
* 🧑‍💼 **Educators & Students**: A live-use case to understand time series forecasting.

---

## ✅ Objectives

* Develop a user-friendly web application.
* Integrate real-time data via Yahoo Finance APIs.
* Predict prices using machine learning (Linear Regression).
* Provide visual graphs and summary insights.

---

## 🔭 Scope

The scope of this project extends to multiple real-world applications across domains such as:

* **Finance & Investment**: Traders and analysts can use this tool to anticipate future stock behavior.
* **Educational Tools**: Useful in academic institutions for teaching ML implementation in finance.
* **Business Intelligence**: Companies can integrate such a system into their internal dashboards to monitor relevant stock trends.
* **Retail Users**: Individuals curious about investing can use this to gain insights and visualize stock performance.

Future enhancements could include the integration of deep learning models, support for multiple financial APIs, mobile app deployment, and portfolio prediction capabilities.

---

## 🧠 Technologies Used

| Category          | Technologies/Tools                   |
| ----------------- | ------------------------------------ |
| **Languages**     | Python, HTML, CSS, JavaScript        |
| **Frameworks**    | Django, Bootstrap                    |
| **ML Algorithms** | Linear Regression                    |
| **Libraries**     | NumPy, Pandas, scikit-learn          |
| **Database**      | SQLite                               |
| **APIs**          | Yahoo Finance, REST APIs             |
| **IDEs**          | Visual Studio Code, Jupyter Notebook |

---

## ⚙️ Project Structure

```bash
.
├── app/               # Contains Django views, models, templates
├── core/              # Core settings and URL configurations
├── virtualenv/        # Virtual environment directory
├── manage.py          # Django management script
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
```

---

## 🚀 Installation Guide

Follow the steps below to get this project running locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/vishal815/-Stock-market-Prediction-with-Machine-Learning-Django.git
   cd Stock-market-Prediction-with-Machine-Learning-Django
   ```

2. **Create a virtual environment**

   ```bash
   python -m venv virtualenv
   ```

3. **Activate the environment**

   ```bash
   virtualenv\Scripts\activate  # On Windows
   ```

4. **Install project dependencies**

   ```bash
   pip install -r requirements.txt
   ```

5. **Run migrations**

   ```bash
   python manage.py migrate
   ```

6. **Start the development server**

   ```bash
   python manage.py runserver
   ```

---

## 📸 Screenshots

### 🔹 Home Page – Real-Time Stock Display

![Home Page](https://github.com/vishal815/-Stock-market-Prediction-with-Machine-Learning-Django/assets/83393190/754e23b7-1d8b-47df-92c2-50d8abdb0f5b)

---

### 🔹 Prediction Form

Users input a ticker symbol and number of future days
![Prediction Form](https://github.com/vishal815/-Stock-market-Prediction-with-Machine-Learning-Django/assets/83393190/b1c4e87c-9d94-4da9-986f-e471f7129d4f)

---

### 🔹 Prediction Result with Graph and QR Code

The left graph shows the real-time stock price of the past day, while the right graph shows the predicted price for the input duration.

![Prediction Output](https://github.com/vishal815/-Stock-market-Prediction-with-Machine-Learning-Django/assets/83393190/6814ac70-6079-4d8b-aef8-3c2959a82a1d)

![Day vs Forecasted](https://github.com/vishal815/-Stock-market-Prediction-with-Machine-Learning-Django/assets/83393190/bdfb6e97-7fca-45e5-afc0-42c861305f9a)

---

### 🔹 Ticker Info Page

Displays valid stock ticker details
![Ticker Info](https://github.com/vishal815/-Stock-market-Prediction-with-Machine-Learning-Django/assets/83393190/faa1429f-81a3-4988-8638-c3b5d28bca9c)

---

### 🔹 Backend Code Structure

Overview of the codebase for clarity and development

![Backend Code 1](https://github.com/vishal815/-Stock-market-Prediction-with-Machine-Learning-Django/assets/83393190/e490bab6-e758-4cef-a09c-4c2eb99a773a)
![Backend Code 2](https://github.com/vishal815/-Stock-market-Prediction-with-Machine-Learning-Django/assets/83393190/a45cf9c2-6a48-4e02-aab1-d04ff53ac5d2)

---

## ✅ Conclusion

Our **Stock Market Prediction** web app demonstrates the practical implementation of machine learning and real-time data in the financial domain. With user-friendly features, insightful visualizations, and accurate predictions, the system supports data-driven decision-making for stock traders and analysts.

---

## 🧑‍💻 Author

Made with ❤️ by **Tanveer Singh** 

🔗 [GitHub](https://github.com/tanveerbedi) | 📧 [Email](mailto:tsbedi2604@gmail.com)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---
