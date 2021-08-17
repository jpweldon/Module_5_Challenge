# Module_5_Challenge

# Financial Health Evaluation

---

## Introduction:

The premise of this project is the scenario that I have decided to start a fintech consulting firm that focuses on projects to benefit local communities. I have won my first contract with a large credit union. The project entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. The chief technology officer (CTO) of the credit union wants me to develop a prototype application to present at its next assembly.


I will create two financial analysis tools.  The first of these is a financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund. The second tool is a financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

I will use the information from the Monte Carlo simulation to answer questions about the portfolio in my Jupyter notebook.

---

## Technologies

This project leverages python 3.7 with the following modules:

* [os](https://docs.python.org/3/library/os.html) - For providing a portable way of using operating system dependent functionality.

* [datetime](https://docs.python.org/3/library/datetime.html) - For supplying classes for manipulating dates and times.

* [json](https://docs.python.org/3/library/json.html) - For data interchange.

* [requests](https://docs.python-requests.org/en/master/index.html) - For sending HTTP/1.1 requests.

* [pandas](https://github.com/pandas-dev/pandas) - For reading data into a DataFrame and analyzing data via statistics and plots.

* [dotenv](https://pypi.org/project/python-dotenv/) - For reading key-value pairs from a .env file and setting them as environment variables.

* [alpaca_trade_api](https://alpaca.markets/docs/api-documentation/) - For collecting the necessary data.

* [pytz](https://pypi.org/project/pytz/) - For accurate timezone calculations.

* [matplotlib](https://matplotlib.org/stable/users/index.html) - For embedding plots in the application.

---

## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install pandas
  pip install python-dotenv
  pip install alpaca-trade-api
  pip install mkdocs
```

---

## Usage

To use the financial health evaluation application:

Clone the Module_5_Challenge repository from GitHub:

'git clone https://github.com/jpweldon/Module_5_Challenge.git'

Run the financial_planning_tools.ipynb program.

Examine the statistics, charts, and analysis contained within the file. I have included analysis outlining the significance.

---

## Contributors

John P Weldon

Email: johnpweldon01@gmail.com

[LinkedIn:] (www.linkedin.com/in/john-weldon-333b0695)

---

## License

MIT

---