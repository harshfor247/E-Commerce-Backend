# E-Commerce-Backend
An E-Commerce Backend using Java Spring Boot with 4 different microservices that includes open-api, User, Order, Transaction using Kafka, PostgreSQL.
The links for the 4 microservices are:-
open-api:- https://github.com/harshfor247/open-api.git
User:- https://github.com/harshfor247/User.git
Order:- https://github.com/harshfor247/Order.git
Transaction:- https://github.com/harshfor247/Transaction.git

Description:- The E-Commerce Backend Project contains 4 different microservices where the open-api can directly connect with the frontend that means open-api can be act as BFF(Backend for Frontend). All the services here are connected with the use of Feign Clients. The function of User service is to create, read, update, deactivate the users and store it in the SQL database where i am using PostgreSQL. Whereas the function of Order Service includes create, read, update, deactivate Products and Orders and similarly saving it to PostgreSQL DB. The last service that is Transaction is only dealing with payment part for the orders that is the final step of purchasing any product. I used Apache kafka in this project to send events in between the services.
