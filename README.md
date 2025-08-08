[README.txt](https://github.com/user-attachments/files/21665023/README.txt)
FXchange – Currency Converter 🇪🇺 (Version 1.0.0)

FXchange is a simple Python-based currency converter. It allows users to convert a given amount in Euro (EUR) into three other currencies: US Dollar (USD), Swedish Krona (SEK), or Swiss Franc (CHF). The program uses live exchange rate data provided by the public Frankfurter API (https://www.frankfurter.app/). It runs directly in the terminal/console and is intended as a lightweight and beginner-friendly tool.

====================
How It Works
====================
The user is first asked how much Euro they want to convert. Then they choose the target currency by entering a number:
1 = Dollar
2 = Kronen
3 = Franken

Based on the input, the program makes a request to the Frankfurter API, retrieves the latest exchange rate for the selected currency, and calculates the converted amount. The result, along with the date of the exchange rate, is then printed to the screen.

====================
Features
====================
– Convert Euro (EUR) to:
   • US Dollar (USD)
   • Swedish Krona (SEK)
   • Swiss Franc (CHF)
– Uses live exchange rate data
– Fully functional with a stable internet connection
– Simple code structure – easy to read and modify
– Variable names in German for learning purposes

====================
Planned Features
====================
– More currencies
– Reverse conversion (e.g. USD to EUR)
– Error handling (e.g. invalid input, API offline)
– GUI version with Tkinter or Kivy (future)
– Language selection (German/English)

====================
Requirements
====================
• Python 3.x
• Internet connection (to access the API)
• requests library (install with: pip install requests)

====================
Note
====================
This project is designed for learning purposes and is ideal for beginners who want to explore Python, APIs, and practical small tools. The variable names are intentionally kept in German to support language learning and familiarity.

Created by: master_commander_98
