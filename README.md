# Assignment-4-CS-260
Restaurant links and arrays, with focus on arrays


# Restaurant Queue Simulation

## Overview
This C++ program simulates a queue system in a restaurant setting, managing customers' orders and serving them in the order they arrive. It demonstrates the use of two fundamental data structures: dynamic arrays (via `std::vector`) and linked lists (via `std::queue`).

## Data Structures

### Dynamic Array (`std::vector`)
- **Purpose**: Used to store a list of items in each customer's order. It allows adding items dynamically, accommodating orders of any size.
- **Use Case**: Each `Order` contains a `std::vector<std::string>` to hold the names of the food items ordered. This flexibility is crucial for handling varying order sizes and complexities.

### Linked List (`std::queue`)
- **Purpose**: Implements a First-In, First-Out (FIFO) queue to manage the order in which customers are served. This simulates a real-world queue where the first customer to arrive is the first to be served.
- **Use Case**: The program uses `std::queue<Customer>` to enqueue customers as they arrive and dequeue them as they are served. This ensures fairness and orderliness in the service process.

## Interaction Between Data Structures
The interaction between these data structures is central to the simulation's functionality. Orders are dynamically managed using vectors, allowing for detailed and flexible order tracking. The queue, acting as a linked list, ensures that the service order is maintained according to arrival time, demonstrating how different data structures can work together to solve complex problems in software development.

## Conclusion
This simulation provides a practical example of how arrays and lists can be used together to manage data efficiently in a real-world application. Understanding these data structures and their applications is crucial for developing efficient and effective software solutions.
