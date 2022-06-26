# Hi there, I'm Dawid 👋 
  
## I'm a student at Polish - Japanese Academy of Information Technology 🇵🇱 🇯🇵

- ☕ I’m currently learning about fundamental aspects of OOP in Java and ERP software, especially SAP
- 💫 2022 Goals: Learn more about SAP ERP software, reach intermediate level of SQL
- 🏃‍♂️ I train long - distance running

##  📈 GitHub stats:

[![Anurag’s github stats](https://github-readme-stats.vercel.app/api?username=dawidsado)](https://github.com/dawidsado)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dawidsado&layout=compact)](https://github.com/dawidsado)

##  🤝 Connect with me:

[![alt text][1.1]][1]
[![alt text][2.1]][2]

[1.1]: https://user-images.githubusercontent.com/77989461/175812672-192d6cac-f990-4d13-bcf0-4f319a531350.png (linkedin icon)
[1]: https://www.linkedin.com/in/dawid-sadownik-429468236/
[2.1]: https://cdn-icons-png.flaticon.com/512/1409/1409946.png (instagram icon)
[2]: https://www.instagram.com/dawidsado_/

## 📁 My main - basic projects with specififc description:

### 1.MiniBankingApplication 🏦 

<!-- Based on excercise from programming classes in second semester -->

The main task is to create a mini - banking system.

Class BankAccount implements the AccountOperations interface, which enables to: check balances, make transfers and deposits. 
BankAccount has information about the balance (default it is 0) and the transaction list assigned to the account.
In case of incorrect data given to transfer I created the AccountOperationException.

Class Transaction represent bank transactions. There is information about the sum of transaction, receiver and sender accounts. The class also enables us to get all information.

User object cannot be created inside the system, class has a first name and last name attributes.
There are three types of users (3 classes).
1.	Client - has assigned account (in general-id of users is generated automatically), is able to use operations from the account.
2.	Employee - is able to add new clients and open a new account. Also, can accept deposits from the client (on private or someone else account).
3.	Admin - the same abilities as Employee, can add and remove employees.

In addition, I created CreditCardForm class, which is responsible for the process of credit card registration and extends User. Class store number of the card, CVC code and expiration year, which is randomly picked from static ArrayList where available years are located (20 next years from current). The list should be initialized with the use of a static initialization block. To get current year I use the LocalDate class.

#### What had I learned during that task? 🤔

•	Working with interfaces, abstract and inheritance classes

•	More practical use of lists

•	Creating and throwing custom exceptions

•	Use of LocalDate class 

•	Implementation of iteration loops


### 2. MiniShoppingApp 🛒

<!-- Also based on excercise from programming classes in second semester -->

Simple app to simulate the process of online shopping. 

A user account can be created in two ways, by adding all parameters in the constructor (standard account) or with only e-mail (guest account). There is also a possibility to create a standard account from the guest state. New products can be also created in two different ways. Products has the function of setting new prices and their amount.

In Category  class one of the attributes is ArrayList which stores Product objects. There are methods to add or subtract products from the list and to set new categories.

Cart class also has a method to add products (to cart in that case) but in an extended version. The process of adding new products is extending the list in cart and there should not be a possibility to add more products than the real amount of them in stock. The payment method is using a for-each loop which iterates through the list and returns the price of all products in the cart.

#### What had I learned during that task? 🤔

•	Loops, especially for - each loop which is better in working at collections

•	Constructors overloading

•	Implementation and use of lists in classes
