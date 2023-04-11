# Car_Sales_Company
This is a database project for a Car Sales Company. The company offers various cars for sale from different categories, each with a specific model and set of features. The customers can buy cars with different types of selling methods, such as cash and loan.
# Project Description
The project contains several entities and relationships that are crucial for the car sales company. The system contains information about the cars for sale that are in the inventory and records information about the cars that are sold. The customer can buy many cars, and each car may be sold to zero or one customer.

If the customer buys the car by loan, the system records the repayment start date, repayment end date, and monthly payment. The system also contains information about the vehicles, such as mini-bus, small car, and the manufactures. The manufacturer may produce different car models for the same type of vehicle with different features.

# Entities
- Vehicle: stores the information about the vehicle such as the make, model, and year.
- Car Model: stores the information about the car model, including the model id, model name, and production date.
- Manufacturer: stores the information about the car's manufacturer, including the name and location.
- Car for Sale: stores the cars that are currently available for sale, including the vehicle, model, and price.
- Car Feature: stores the features of the car, such as air conditioning, power windows, and so on.
- Customer: stores the customer's information such as name, address, and contact details.
- Car Sold: stores the information about the cars that are sold, including the selling method (cash or loan) and the customer's information.
- Customer Payment: stores the information about the customer's payment for a car bought on a loan, including the repayment start date, end date, and monthly payment.

# Relationships

- One customer can buy many cars, and each car may be sold to zero or one customer.
- Each car has a specific model and set of features, and each model belongs to one manufacturer.
- The manufacturer may produce different car models for the same type of vehicle with different features.
- The system records the repayment start date, repayment end date, and monthly payment for cars bought by loan.
- The Inventory entity contains the cars that are currently available for sale.

# Conclusion
This database project is designed to help the car sales company manage its business operations more efficiently. By storing and organizing the data related to the cars, customers, and manufacturers, the company can easily track its sales, inventory, and customers' payments.
