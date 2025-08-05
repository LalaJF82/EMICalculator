
📊 EMI Calculator - Java
This is a simple EMI (Equated Monthly Installment) Calculator written in Java. It takes user input for loan amount, interest rate, and tenure to calculate the monthly EMI using standard financial formulas.

🧮 What is EMI?
EMI stands for Equated Monthly Installment. It is the fixed monthly payment made by a borrower to repay a loan over a specified time period.

The EMI formula used in the program:

ini
Copy
Edit
EMI = P × r × (1 + r)^n / ((1 + r)^n – 1)
Where:

P = Principal loan amount

r = Monthly interest rate (Annual rate divided by 12 × 100)

n = Total number of monthly payments (Years × 12)

🚀 How to Run
Compile the code:

bash
Copy
Edit
javac EMICalculator.java
Run the program:

bash
Copy
Edit
java day4.EMICalculator
Note: Make sure the file is located in a folder named day4 to match the package declaration.

📝 Example Input/Output
text
Copy
Edit
Enter loan amount in USD
10000
Enter annual interest rate (in %)
7.5
Enter loan tenure in years
5
Your monthly EMI is: 200.38
📂 File Structure
Copy
Edit
day4/
└── EMICalculator.java
✅ Features
Takes user input interactively via console

Calculates EMI using the compound interest formula

Works for any currency and interest rate input

🛠 Requirements
Java JDK 8 or later

Terminal/Command Prompt access

📌 License
This project is free to use and modify for educational or personal purposes.

Let me know if you want to add enhancements like input validation or a GUI version.









