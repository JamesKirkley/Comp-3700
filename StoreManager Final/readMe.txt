This project aims to build a working prototype, client-server for the "Store Management System".

1. It is a multi-user, client-server software application.
 That means, there might be several users interacting with the system at the same time, from two user classes: managers and customers.
 Each user interacts with the system via a client component, while a server component (might be running in a different machine) provides the data services.

The "manager" user has the following user stories:

• As a store manager, I want to add information of a new product

• As a store manager, I want to change information of an existing product

The "customer" user has the following user stories:

As a customer, I want to register as a new user into the system
As a customer, I want to change my customer information (e.g. address, payment method, phone number, email)
As a customer, I want to change my login information (e.g., password)
As a customer, I want to log in the system
As a customer, I want to make a new order
As a customer, I want to change an existing order (e.g., change quantity, add items or remove existing ones)
As a customer, I want to cancel an order
As a customer, I want to search for product information
As a customer, I want to see my order history


2. This system is designed with 3 architectural patterns:

a. Three-tier layers: Data Access; Business Logic, and User Interface. The Data Access layer is separated into client side and server side.

b. Model-View-Controller

c. Client-Server

3. This system is designed with the following object-oriented design patterns: Singleton; Adapter;

4. This system needs to be secure: 

i) information exchanged over the network needs to be encrypted;

ii) the system will only allow valid operation of each user. 
For example, a customer user could not change product information; or could not see/cancel/change orders not made by his/her.

Youtube link of system running.
https://youtu.be/VdaFgobM0jw
