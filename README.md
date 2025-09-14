# ShoppingCartSystem
This Java program simulates a shopping cart system where users can, add multiple products to a cart. apply different types of discounts (Festive, Bulk)  Pay the final amount using an OnlinePayment method. It demonstrates object-oriented programming concepts such as abstraction, inheritance, polymorphism, and interface implementation

#🧾 Features
-Add an arbitrary number of products to a shopping cart.
-Calculate total price for each product and overall cart value.
>Apply:
 -Festive Discount (10% off total)
 -Bulk Discount (20% off if any product quantity > 5)
-Use an online payment method to "pay" the final bill.
-Gracefully handle unknown discount types (no discount applied).
>
# 📂 File Structure
ShoppingCartSystem.java
README.md

# How to Run
. Clone the repository
git clone https://github.com/saicharan-git01/ShoppingCartSystem.git
cd ShoppingCartSystem
javac ShoppingCartSystem.java
java ShoppingCartSystem

  #input
    3
    apple 50 2
    banana 20 6
    milk 30 1
    bulk

 >>🧠 OOP Concepts Used

-Encapsulation: Product details are private with getters.
-Abstraction: Discount class provides a blueprint for discount strategies.
-Inheritance: FestiveDiscount and BulkDiscount extend Discount.
-Polymorphism: applyDiscount() behaves differently based on discount type.
-Interfaces: Payment is an interface implemented by OnlinePayment.

# Author 
Developed by Saicharan
Email: bondlavarusaicharan@gmail.com
