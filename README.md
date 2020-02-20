# Mortage Calculator App

An application to calculate the maximum loan amount for a given payment and interest rates and save user queries.

## Microservices

### [Loan UI](https://github.com/vonrosen/loan-ui)
React front-end.
### [Loan Service](https://github.com/vonrosen/loan-service)
Spring-boot loan caluctation API.
### [User Service](https://github.com/vonrosen/user-service)
Spring-boot user persistence and retrieval API.
### [User Request Log Service](https://github.com/vonrosen/user-request-log-service)
Spring-boot user input logging service that publishes to RabbitMQ.
### [User Request Log Eventing Service](https://github.com/vonrosen/user-request-log-eventing-service)
Spring-boot user input logging service that consumes from RabbitMQ, persists user requests, and provides and API to read user requests from the persistence store.

![Mortage App Diagram](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
