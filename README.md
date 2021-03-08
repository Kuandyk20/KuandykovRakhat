# KuandykovRakhat
ElectricityBillingSystem
Welcome to my project!
Here I used 3 classes which are mostly extends eachother.
First and simple one is ConnectDB class which connects to DataBase and thats all.
AccMenu class extends ConnectDB so we can use variables from postgresql tables.Also it is defined as menu for user who is registred in this program. It count bill for user after he types quantity of units he used. Also there are options to see price list and your account information.
MainMenu class is main menu of three options: Log in, Sign up, Exit.This class extends from Accmenu because we need to use AccMenu methods of calculating payment for electricity.
So when you log in correctly you just go to Accmenu method.
