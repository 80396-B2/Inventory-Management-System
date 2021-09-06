# Inventory-Management-System
This a Inventory Management system  created using python 3.9 and its various modules & libraries.
This system can be preferably used in a pharmaceutical store or a website of a pharmaceutical company(like medplus).
# Getting Started
You need to have a python platform on your system.
* Download all the files in your pc but make sure to keep all of them in the exact same folder else the code will not execute.
* Later, hit run and the code will start executing.
# Modules/Libraries used
The python libraries I used are:-
* json
* datetime
* time
* random
# Features
* It can check the availability of the ordered drug and will reply as per the stock.
* It has a prescription checker to check if the drug can be sold over the counter or not for legal restrictions.
* It comes with a bill at the end which is quite detailed,compact and eye-catching
* You can also check the after sales record in the sales.json file.
# Special facts
* All the bill number are completely random and unique.
* On the bill you can find your name, exact time of check-out and the present date!!
* A time delayer for giving a real feel while it checks for the stocks.
# Data set
I myself created the data set using dictionary in python then converted it in Json.
It has 30 products and each product has 7 attributes/properties:-
* Drug name
* Expiry date
* Price
* Country of origin
* Over the counter permission
* Bar code no
* Quantity available
* mg(power)
* Unique item code
All the names of drug are real and legit though their attributes are all made-up by me..
# Description/Working
First things first reading the data with file handling.Then it asks for your name.Once you hit enter a complete list of all the drugs and their corresponding item code is displayed along with its mg.You need to enter the item code of the medicine you need and the quantity.
The program checks for the required drug and its availability with a time delayer (*you can see the stars looking like a loading bar*)
  * now if the item is available with sufficient quantity and over the counter permissions then it wil be added to cart and ask to add more items or proceed to check-out options.
  * if the quantity is less then stated then it will ask to proceed with whatever available then according to user choice it will either add it to cart or ask to add more items or proceed to check-out options.
  * if the item is not sold without prescription then it will reject your request and will ask for new item or checkout subsequently.
You can add as many products as you want in accordancewith the availabilty and then you can proceed to check-out.
here you will get a bill with all you purchased drug name,it's price,Quantity_Purhased,barcode and expiry.There are some dynamic features in the bill too like:
  * unique bill no for future reference.
  * Your name is printed on the bill.
  * the exact date & time is also present on the bill.
 At the very end you can find a grand total of your purchase.
 You can also check for the same in the sales.json file.



# Links
* Gmail- kartikgparashar786@gmail.com
* kaggle - https://www.kaggle.com/kartikparashar 
* linkedin - www.linkedin.com/in/kartik-parashar-90bb1a1a4
* This Repo- https://github.com/kartikparashar786/Inventory-Management-System

  
  
