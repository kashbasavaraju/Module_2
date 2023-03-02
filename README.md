# Loan Qualifier App

This application allows users to see whether they qualify for loans from an existing data set provided by a 'daily rate sheet' by entering their credit score, monthly debt, monthly income, desired loan amount, and their home value. From these inputs, Debt to Income Ratio, and loan to home value is calculated. The loans from the daily rate sheet are then filtered based on if the ratios fit the criteria for the existing loans.

Using this application will allow users to quickly identify and access loans they qualify for as opposed to having to filter loans out manually that is usually done by a third party.

---

## Technologies

This project leverages Python 3.7 with the following packages:

    fire - for the command interface

    questionary - for the interactive user prompts and dialogs

---

## Installation Guide

Install Questionary and Fire from Python Library using the following command in python:

```python
'install pip fire'
```
```python
'install pip questionary'
```
## Usage

To use the Loan Qualifier Application, clone the repository and run the **app.py** application in the terminal.

When prompted, enter the output path for the rate sheet for the loans which is located in the "data" folder. 

```python
'./data/daily_rate_sheet.csv'
```
When prompted, enter credit score, monthly debt, monthly income, desired loan amount, and home value.

![User prompts 1](https://github.com/kashbasavaraju/Module_2/blob/main/User%20Prompts%20Part%201.png)

The program will then filter and identify the number of qualified loans.

![User prompts 2](https://github.com/kashbasavaraju/Module_2/blob/main/User%20Prompts%20Part%202.png)

When prompted, enter whether or not you would like to save the file. 

![User prompts 3](https://github.com/kashbasavaraju/Module_2/blob/main/User%20Prompts%20Part%203.png)

If there are no qualifying loans, it will let you know there are 0 qualifying loans and will exit the program. 

![User prompts 4](https://github.com/kashbasavaraju/Module_2/blob/main/User%20Prompts%20Part%204.png)

If there are qualifying loans, it will prompt you whether or not you want to save the file. If you would like to save the file, enter the output path (using .csv format) and the file will save as a csv file. 

![User prompts 5](https://github.com/kashbasavaraju/Module_2/blob/main/User%20Prompts%20Part%205.png)

If you would not like to save the file, the program will be suspended.

![User prompts 6](https://github.com/kashbasavaraju/Module_2/blob/main/User%20Prompts%20Part%206.png)

If you do not enter either a Yes or a No, you will receive an error message and will be asked to enter a Yes or a No.

![User prompts 7](https://github.com/kashbasavaraju/Module_2/blob/main/User%20Prompts%20Part%207.png)

## Contributors

Kaushik Basavaraju
Email: kash.basavaraju@gmail.com

---

## License

MIT
