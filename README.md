## Typescript Project for start2impact University

Hello, this is my project about Typescript on start2impact.

This project aims to develop a typescript system that models the operating structure of a brand called Sunnee
of recycled plastic beachwear, focusing on the interactions between customers, beachwear products and sustainable production processes.

By defining interfaces and classes that represent the various components of the system, the project demonstrates how technology can support sustainable innovation for the fashion industry.

You can try my project <a href="https://codepen.io/RiccardoAD/pen/KKONVxE?editors=1111">HERE</a> on CodPen.

Key Components

Interfaces:

IProdotto (IProduct): represents products with properties such as type (swimsuit, pareo, hat), ID, size, color, status (available, out of stock), and a method to assign them to a customer.

ICliente (ICustomer): represents customers with properties such as first name, last name, email, preferred payment method, and a method to order a product.

IProcessoProduzione (IProductionProcess): represents a production process with a name, description, list of products in production, and a method to add products.

Implemented Classes:

Product: implements IProdotto, manages product information and assignment to a customer.

Customer: implements ICliente, manages customer data and allows them to order a product.

ProductionProcess: implements IProcessoProduzione, manages production processes and adding new products.

Operational Logic:

Customers can order available products.
Products can be assigned to a specific customer, changing their status to "assigned."
Production processes manage products currently in production.
Testing and Implementation:

Various products and customers were instantiated.
A sustainable production process was created to add and manage products.
The logic for ordering and production was successfully tested.

# About the code

I used only typescript.

I created interfaces and then classes that implemented the interfaces previously created.

Then I created instances to test and use the code.
