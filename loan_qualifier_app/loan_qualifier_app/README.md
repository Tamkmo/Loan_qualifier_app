# Loan Qualifier Application

This project is about providing a tool to help identify loans that qualify based on parameters such as income, debt, credit score and current home value. The app provide unique ability to output a list of qualified loans saved as a .csv file with an integrated user input. The user input is simple and intuitive to follow. The goal of this project was to remove the complexities involved for the user to identify best suited loans, and help our users in their decision making process.

---

## Technologies

The project has been built using Python and its libraries. The critical dependencies are installation of the Fire and Questionary libraries, which need to be installed before running the program. The program works with both Windows and MacOS systems. 

---

## Installation Guide

The file package contains 3 key folders, the main program and README.md files. The 3 folders in the package are data, qualifier and utils. To run the main program 'app.py' successfully, 3 folders mentioned above need to be installed under the same folder structure. Python libraries such as Fire and Questionary need to be installed using following command at the terminal: pip install Fire, pip install Quesitonary before running 'app.py'.

---

## Usage

To run the loan qualifier application, run the command 'python app.py' at the ternimal. The program will ask for file path to load the data from, followed by user input for credit score, monthly debt, monthly income, desired loan amount and home value. Based on the filtering calculations if loans matching your criteris are identified, they will be listed on the terminal. Program will prompt the user to save the list of qualifying loans to a csv file for better data retention.

? Enter a file path to a rate-sheet (.csv): ./data/daily_rate_sheet.csv
? What's your credit score? 750
? What's your current amount of monthly debt? 3000
? What's your total monthly income? 10000
? What's your desired loan amount? 100000
? What's your home value? 300000
The monthly debt to income ratio is 0.30
The loan to value ratio is 0.33.
Found 15 qualifying loans

? File needs to be saved as a csv. Please confirm? y
? Enter a file path to save your qualifying loan list (.csv): ./data/qualified_loans.csv

---

## Contributors

Thanks to these wonderful instructors and TAs from FinTech class. Special mention goes to Celeste Tretto, our instructor for being a consistent support as we venture in this new area of study. I look forward to future collaboration ideas on this project or suggestions to advance this project. Please reach out to me at Tasnim.Morbiwala@gmail.com.

---

## License

The source code is available under public license to help with future collaboration.
