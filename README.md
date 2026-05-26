# Daily Expense Tracker

# Description
Welcome to the Daily Expense Tracker! Managing personal finances is a crucial step toward achieving financial stability, and it starts with understanding your daily spending habits. This project provides a lightweight, interactive, and user-friendly Python application designed to help you seamlessly log and analyze your day-to-day expenditures. 

Built entirely within a Jupyter Notebook, this tool serves as an excellent practical example of utilizing fundamental Python programming concepts alongside powerful external libraries. By leveraging the NumPy library, the application efficiently computes vital financial metrics, offering immediate insights into your spending patterns without the overhead of complex financial software.

#Key Features
* **Interactive Data Entry:** The application features a continuous, intuitive loop that prompts the user to input daily expenses. It remains active until the user safely signals completion by typing 'done', making it highly flexible for any timeline.
* **Robust Input Validation:** To ensure seamless operation and strict data integrity, the script includes built-in error handling. It actively prevents application crashes by catching non-numeric text inputs and explicitly rejects negative values.
* **Advanced Statistical Analysis:** Instead of relying on basic loops, the calculation engine uses NumPy arrays. This enables highly efficient computation of your total expenses, the average daily cost, the maximum expense incurred, and the exact day that peak expense took place.

# Technologies & Libraries
* **Python 3:** The core programming language powering the application's underlying logic.
* **Jupyter Notebook:** Provides an interactive coding environment to run the script and view outputs seamlessly.
* **NumPy:** Utilized for its highly optimized mathematical operations, specifically calculating arrays, sums, averages, and maximum values.

# How to Run
1. Clone this repository to your local machine.
2. Ensure Python and Jupyter are installed. Install dependencies via your terminal: `pip install notebook numpy`.
3. Launch Jupyter Notebook and open the `May_Minor_Project.ipynb` file.
4. Run the code cell. An input prompt will appear below, allowing you to log expenses.

# Author & Context
**Divyanshu-2476084** Developed as part of practical coursework and projects at the KIIT School of Management. This tracker was built with a strong focus on data analytics and modeling, demonstrating how simple user inputs can be efficiently transformed into structured datasets and meaningful summaries.

# Future Scope
Upcoming enhancements could include utilizing Pandas to export logged data into CSV files for long-term storage, and integrating Matplotlib or Power BI to generate dashboards that visualize spending trends and patterns over time.
