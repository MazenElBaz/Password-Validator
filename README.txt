----------------------
Name: Mazen ElBaz
Date: Sept. 2018
----------------------

Exercise 1: Password Validator 

Included Files:
    * validator.py
    * README

Running Instructions:
    1. In the directory containing validator.py use the command: python3 validator.py

    2. Under if __name__ == "__main__", the first prompt is for task 1. Type any password that you would like to be validated and press ENTER. The program prints "Secure", "Insecure" or "Invalid". Then, there is another prompt and that is for task 2. Type the number n and press ENTER. The program prints a random password with n characters. To make sure that my generate function was returning secure random passwords, I passed the randomly generated password to my validate function. The next line after the random password is printed, the program prints "Secure".

Notes and Assumptions:
    1. In the generate function, the code doesn't test if the number n is greater than or equal to 8 since I am assuming you will always be entering n>=8.

    2. To increase the randomness of the password, after the 4 types of characters are assigned to RandomPassword, random.sample is used to shuffle them around so they are not in a particular order. Also, the remaining characters, which will be added to the variable RandomPassword, will be added randomly with random types. 