# Hi there, I'm Dawid 👋

## I'm a student at Polish - Japanese Academy of Information Technology 🇵🇱 🇯🇵

- ☕ I’m currently learning about fundamental aspects of OOP in Java and ERP software
- 💫 2022 Goals: Learn more about SAP ERP software, discover Java frameworks and reach intermediate level in SQL


##  📈 GitHub stats:

[![Anurag’s github stats](https://github-readme-stats.vercel.app/api?username=dawidsado)](https://github.com/dawidsado)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dawidsado&layout=compact)](https://github.com/dawidsado)

<br></br>

# 📁 My main projects with specififc description:

# 1.MiniBankingApplication 🏦
https://github.com/dawidsado/MiniBankingApp

<!-- Based on excercise from programming classes in second semester -->

![MiniBankingAppChart](https://user-images.githubusercontent.com/77989461/177208582-0e667eb9-f895-4f19-858c-8cc022940d70.png)

<br></br>

Class BankAccount implements the AccountOperations interface, which enables to: check balances, make transfers and deposits. 
BankAccount has information about the balance (default it is 0) and the transaction list assigned to the account.
In case of incorrect data given to transfer I created the AccountOperationException.

![Obraz 08 07 2022, godz  11 53 (1)](https://user-images.githubusercontent.com/77989461/177967188-64ac0476-2a19-4f6f-97e9-c5d5e49f8fdb.jpg)
![Obraz 08 07 2022, godz  11 53](https://user-images.githubusercontent.com/77989461/177967198-f729a137-e9de-4089-bef1-f4fd1b3c8d4d.jpg)
![Obraz 08 07 2022, godz  12 04](https://user-images.githubusercontent.com/77989461/177969849-0c023b27-9904-42ed-89b3-314d1ef1807f.jpg)

<br></br>

Class Transaction represent bank transactions. There is information about the sum of transaction, receiver and sender accounts. The class also enables us to simulate the transaction process (amount of money is deleted and added to given accounts). 

![Obraz 08 07 2022, godz  11 55](https://user-images.githubusercontent.com/77989461/177967645-4eadf490-4cdf-4be9-b355-90f475deb7f7.jpg)

<br></br>

The user class has first name and last name attributes and a constructor.
There are three types of users (3 classes).

![Obraz 08 07 2022, godz  11 56](https://user-images.githubusercontent.com/77989461/177967652-8be457af-9df8-4c34-a76d-63bc5597b0ac.jpg)

<br></br>

1.	Client - has assigned account (in general-id of users is generated automatically), is able to use operations from the account. (super constructor and implementation of interface).

![Obraz 08 07 2022, godz  11 59](https://user-images.githubusercontent.com/77989461/177968129-faa432ed-f54a-4448-8261-74b7ebeec851.jpg)

<br></br>

2.	 Employee - is able to add new clients and open a new account.

![Obraz 08 07 2022, godz  11 59 (1)](https://user-images.githubusercontent.com/77989461/177968144-4ddd69c7-09f6-4fbf-bd82-643d6f11d8d6.jpg)

<br></br>

3.	 Admin – also can add new clients, additionally can add and remove employees.

![Obraz 08 07 2022, godz  12 01](https://user-images.githubusercontent.com/77989461/177968777-80a2608c-def1-4712-8682-10e8529e10e6.jpg)

<br></br>

In addition, I created CreditCardForm class, which is responsible for the process of credit card registration and extends Client. Class store number of the card, CVC code and expiration year, which is randomly picked from static list where available years are located (20 next years from current). The list should be initialized with the use of a static initialization block. To get current year I use the Date class. 

![Obraz 08 07 2022, godz  12 01 (1)](https://user-images.githubusercontent.com/77989461/177968855-360222eb-5bfd-44f6-8355-42951ce321ec.jpg)

<br></br>

I also created an interface that enables every user to generate password. I based algorithm on  first letters of first and last name,  ID, underscore char and hash code value.

![Obraz 08 07 2022, godz  12 06](https://user-images.githubusercontent.com/77989461/177970865-1a1bcb82-a491-4fec-bfe7-32c4890f5214.jpg)

<br></br>

## Test

https://user-images.githubusercontent.com/77989461/177971379-c4f72c18-7e3c-41d8-9924-ed8657628f1f.mp4

<br></br>

## What had I learned during that task? 🤔

•	Working with interfaces, subclass constructors, abstract and inheritance classes

•	For loop and initialization block

•	More practical use of lists

•	Creating and throwing custom exceptions

•	Use of Date class

•	Methods like hashCode and valueOf

<br></br>

# 2. MiniShoppingApp 🛒

<!-- Also based on excercise from programming classes in second semester -->

Simple app to simulate the process of online shopping. 

A user account can be created in two ways, by adding all parameters in the constructor (standard account) or with only e-mail (guest account). There is also a possibility to create a standard account from the guest state. New products can be also created in two different ways. Products has the function of setting new prices and their amount.

In Category  class one of the attributes is ArrayList which stores Product objects. There are methods to add or subtract products from the list and to set new categories.

Cart class also has a method to add products (to cart in that case) but in an extended version. The process of adding new products is extending the list in cart and there should not be a possibility to add more products than the real amount of them in stock. The payment method is using a for-each loop which iterates through the list and returns the price of all products in the cart.

## What had I learned during that task? 🤔

•	Loops, especially for - each loop which is better in working at collections

•	Constructors overloading

•	Implementation and use of lists in classes




##  🤝 Connect with me:

[![alt text][1.1]][1]
[![alt text][2.1]][2]

[1.1]: https://user-images.githubusercontent.com/77989461/175812672-192d6cac-f990-4d13-bcf0-4f319a531350.png (linkedin icon)
[1]: https://www.linkedin.com/in/dawid-sadownik-429468236/
[2.1]: https://cdn-icons-png.flaticon.com/512/1409/1409946.png (instagram icon)
[2]: https://www.instagram.com/dawidsado_/
