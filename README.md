--- |

Cross Country Salary Management System

Overview:

The Cross Country Salary Management System is a Java-based application that helps organizations manage and compare employee salaries from various countries. It stores each employee's name, country, and salary in their local currency, then converts all salaries to USD using fixed exchange rates. This provides a standardized view, making salary comparison and total cost analysis across different regions easy and efficient.


---

Features:

Stores employee data: name, country, and local salary.

Converts salaries from local currencies to USD.

Displays both local and USD salary values.

Calculates total salary expenditure in USD.



---

Supported Countries & Exchange Rates:

Country	Currency	Exchange Rate (to USD)

USA	USD	1.00
India	INR	0.012
UK	GBP	1.25
Germany	EUR	1.10
Japan	JPY	0.007


Note: Exchange rates are fixed and manually defined within the code.


---

Sample Output:

=== Cross Country Salary Report ===
Alice - USD 7000.00 (USD 7000.00)
Rahul - INR 100000.00 (USD 1200.00)
John - GBP 4000.00 (USD 5000.00)
Anna - EUR 3500.00 (USD 3850.00)
Sato - JPY 500000.00 (USD 3500.00)

Total Salary in USD: 20550.00


---

How It Works:

1. The program defines an Employee class to represent individual employees.


2. A CurrencyConverter class contains methods for currency conversion and retrieving currency symbols.


3. The CrossCountrySalaryManagement main class:

Initializes a list of employees.

Prints each employee’s salary in local currency and USD.

Calculates and prints the total salary cost in USD.





---

Use Cases:

HR management for multinational teams.

Financial planning and international payroll analysis.

Consolidated salary reporting for global companies.



---

Requirements:

Java Development Kit (JDK) 8 or later.

IDE or text editor (e.g., IntelliJ IDEA, Eclipse, VS Code).



---

How to Run:

1. Save the code in a file named CrossCountrySalaryManagement.java.


2. Open a terminal/command prompt.


3. Compile the code:

javac CrossCountrySalaryManagement.java


4. Run the compiled program:

java CrossCountrySalaryManagement




---

License:

This project was developed by Team Null&Void for educational use. Feel free to use, modify, and expand upon it as needed.
