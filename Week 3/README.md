# 1. Week challenges (Monday) 💻

## 1.1. Simple calculator

The calculator must ask the user for two numbers, after asking for the two numbers, you must ask for the operation to be performed, keep in mind that you must show the user the options available (+, -, *, /). The first thing that must be done is to validate that the operation that the user entered is valid, if it is not a valid option, the user must be shown an error message, for example: ⚠️ La operación no es valida and terminate the program. If the operation is valid, show the message: Procesando: <OPERACIÓN A REALIZAR> For, example: if the user has entered the numbers 10 and 15 as well as the operation *, the message should read: Procesando: 10 * 15. After this message the result of the operation must be displayed, following the previous example, the result of operating 10 * 15 is 150, so the program should return: Resultado: 150. Remember to use conditionals to identify which operations you should execute.

![Cálculadora Simple Si entonces](https://user-images.githubusercontent.com/118086376/236605795-d57e32eb-1000-413e-9846-63aa70356ade.png)

## 1.2. Special number

You must create the code that follows the following logic, if the given number is 100, take this number as special and show the following message: "This is a special number!", but if the number is less than 1000, multiple of 10 and different from 100, you must show the following message: "This number is almost special". if none of the given conditions are met show the following message: "Just a regular number". Another developer was trying to program the logic, but apparently couldn't, you need to fix the code to work properly

![Special Number](https://user-images.githubusercontent.com/118086376/236602975-64dd797b-e1a0-4a18-b9f9-fa41213103fc.png)

# 2. Week challenges (Tuesday) 💻

## 2.1. Simple calculator with Switch

For this challenge you will be performing a simple calculator, this calculator can perform the following operations:

Sum (+)
Subtract (-)
Multiplication (*)
Division (/)
The calculator must ask the user for two numbers, after asking for the two numbers, you must ask for the operation to be performed, keep in mind that you must show the user the options available (+, -, *, /). The first thing that must be done is to validate that the operation that the user entered is valid, if it is not a valid option, the user must be shown an error message, for example: ⚠️ La operación no es valida and terminate the program. If the operation is valid, show the message: Procesando: <OPERACIÓN A REALIZAR> For, example: if the user has entered the numbers 10 and 15 as well as the operation *, the message should read: Procesando: 10 * 15. After this message the result of the operation must be displayed, following the previous example, the result of operating 10 * 15 is 150, so the program should return: Resultado: 150. Remember to use conditionals to identify which operations you should execute.

![Cálculadora Simple](https://user-images.githubusercontent.com/118086376/236600636-989e1fde-fe29-4eab-9efc-0530a5631f24.png)

## 2.2. Multi Option Program

For this challenge you will create a program with multiple options using Switch (Segun), the options available are the following:

  1. Sum two numbers
  2. Print the day of the week given the day number
  3. Print the length of a given text

This program must have a start menu where the user must select one of the previously described options. When the user selects each of the options, the program will perform the following:

  1. Sum. The user enters two numbers and the result of the sum of both is printed
  2. Print day of the week. The user enters a day of the week using numbers and the name of the day must be printed. For example, if the number 1 is entered, the program prints the text Lunes.
  3. Calculate text length. The user enters a text and the length of the text should be printed. I was able to use the Pseint Longitud function to get the length.
  
  ![Multi_opcion](https://user-images.githubusercontent.com/118086376/236650113-484f6626-f537-4b8e-b859-54922ca77cbf.png)

# 3. Week challenges (Wednesday) 💻

## 3.1. Multiplication Tables

For this challenge you will create a program to calculate the multiplication tables for a given number using While (Mientras). The user must enter a number and then the multiplication table for the number must be printed.

![tablas](https://user-images.githubusercontent.com/118086376/236651763-fdbb74ce-3b7e-403b-adf6-e3653e0ab606.png)

## 3.2. Simple Calculator with Do While

For this challenge we are going to use the simple calculator that we made in the challenge 02 but now adding the functionality to perform a calculation again without finishing the program. The program should ask us if we want to use another operation and if the user answers yes then we can perform a new operation. To solve this challenge remember to use Do while (Repetir Hasta Que).

![Calculadora_Simple_Hastaque](https://user-images.githubusercontent.com/118086376/236652364-a6fb0bb1-aa38-4319-aca2-92ea9465dda7.png)

# 4. Week challenges (Thursday) 💻

## 4.1. Multiplication Tables with For

For this challenge you will create a program to calculate the multiplication tables for a given number using the For(Para) loop. The user must enter a number and then the multiplication table for the number must be printed.

![Tablas_For](https://user-images.githubusercontent.com/118086376/236741102-91c3eef7-2262-4c24-9164-4b914f2c0784.png)

## 4.2. Ascending and Descending Numbers

For this challenge we are going to print numbers in ascending or descending order. The user must enter a number, then he must enter if he wants to print the numbers in ascending or descending order. If the user chooses ascending, the numbers will be printed from the number 0 to the number entered, otherwise the numbers will be printed descending from the number entered to the number 0.To solve this challenge remember to use the For(Para) loop.

![Ascendente](https://user-images.githubusercontent.com/118086376/236745367-6c0b70c3-f44c-4b45-a6bb-5534e9e81c12.png)

## 4.3. Greetings

For this challenge, you need to create a program that prints a greeting based on an hour entered. The program should do the following:

  * Print Buenos dias! if the hour is from 0 to 12
  * Print Buenas tardes! if the hour is from 13 to 18
  * Print Buenas noches! if the hour is from 19 to 23
  * Ask the user if he wants to perform another greeting. If the answer is Si, the program must start again.
  * At the end of the program, print out the number of times the program has greeted.
