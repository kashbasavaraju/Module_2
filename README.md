# Loan Qualifier App

This application allows users to see whether they qualify for loans from an existing data set provided by a 'daily rate sheet' by entering their credit score, monthly debt, monthly income, desired loan amount, and their home value. From these inputs, Debt to Income Ratio, and loan to home value is calculated. The loans from the daily rate sheet are then filtered based on if the ratios fit the criteria for the existing loans.

Using this application will allow users to quickly identify and access loans they qualify for as opposed to having to filter loans out manually that is usually done by a third party.

---

## Technologies

The programming language used to make this program is Python.

---

## Installation Guide

Install Questionary and Fire from Python Library using the following command in python:

```python
'install pip fire'
```
```python
'install pip questionary'
```
Then activate the program using

```python
'python app.py'
```
## Usage

When prompted, enter the output path for the rate sheet for the loans which is located in the "data" folder. 

```python
'./data/daily_rate_sheet.csv'
```
When prompted, enter credit score, monthly debt, monthly income, desired loan amount, and home value.

![User prompts](https://github.com/kashbasavaraju/Module_2/blob/main/User%20Prompts%20Part%201.png)

The program will filter and identify the number of qualified loans.

When prompted, enter whether or not you would like to save the file. If there are no qualifying loans, it will let you know there are 0 qualifying loans and will exit the program. If there are qualifying loans, it will prompt you whether or not you want to save the file. If you would like to save the file, enter the output path and the file will save as a csv file. If you would not like to save the file, the program will be suspended.

## Contributors

Kaushik Basavaraju
Email: kash.basavaraju@gmail.com

---

## License

MIT
