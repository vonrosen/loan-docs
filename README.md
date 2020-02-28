# Mortage Calculator App

[http://www.loanval.com](http://www.loanval.com)

An application that calculates the maximum loan amount for a given payment and interest rates and saves user queries.

## Microservices

### [Loan UI](https://github.com/vonrosen/loan-ui)
React front-end.
### [Loan Service](https://github.com/vonrosen/loan-service)
Spring-boot loan calculation API.
### [User Service](https://github.com/vonrosen/user-service)
Spring-boot user persistence and retrieval API.
### [User Request Log Service](https://github.com/vonrosen/user-request-log-service)
Spring-boot user input logging service that publishes to RabbitMQ.
### [User Request Log Eventing Service](https://github.com/vonrosen/user-request-log-eventing-service)
Spring-boot user input logging service that consumes from RabbitMQ, persists user requests, and provides and API to read user requests from the persistence store.

![Mortage App Diagram](http://www.loanval.com/mortgate-app-diagram.png "Mortgate App Diagram")
