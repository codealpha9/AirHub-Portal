
Flight Management Client-Server

It is a flight management and dispatching system implemented as a distributed application using Go for the server-side and Python for the client-side. The system is designed to handle various operations related to managing flights, such as creating, updating, retrieving, and deleting flight records. It employs a client-server architecture, where the server handles the core logic and database interactions, and the client communicates with the server through API calls to perform operations on flights. The system is built with a focus on scalability, fault tolerance, and performance, making it suitable for managing flight operations in a distributed environment.
## Running

### Server


1. Make sure that Go v1.11+ is installed
2. Download deps `$ go mod download`
3. Build `$ go build ./cmd/server`
4. Run `$ ./server`

Arguments can be viewed with `$ ./server -h`

### Client

1. Make sure that Python 3.5+ is installed
2. Run `$ python main.py`

Arguments can be viewed with `$ python main.py -h`

new 1201 Banglore Delhi 8:00 20 10000

find_destinations Manglore

get 1201
get 101

find_flights Banglore Delhi
reserve 1201 15
monitoring_seats 1201 1
