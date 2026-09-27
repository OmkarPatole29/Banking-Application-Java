
# Banking Application

A console-based banking application developed using Java to practice Core Java, Object-Oriented Programming, Collection interfaces, exception handling and layered application architecture.

## Features

- Open bank accounts
- Deposit money
- Withdraw money
- Transfer money between accounts
- View account statements
- List bank accounts
- Search accounts by customer name
- Handle invalid operations using custom exceptions

## Technologies Used

- Java
- IntelliJ IDEA
- Git
- GitHub

## OOP Concepts Practiced

- **Encapsulation** – Keeping account and customer data private and controlled through methods.
- **Abstraction** – Defining essential banking operations through interfaces.
- **Inheritance** – Reusing common functionality where applicable.
- **Polymorphism** – Implementing interface methods and using different implementations.
- **Exception Handling** – Handling errors using custom exceptions.

## Project Structure

src/
├── app/
├── domain/
├── exceptions/
├── repository/
├── service/
│   └── impl/
└── util/


## Architecture

The application follows a layered structure:

- **App:** Contains the main entry point and console interaction.
- **Domain:** Contains account, customer, and transaction-related classes.
- **Repository:** Manages the storage and retrieval of application data.
- **Service:** Contains the banking operations and business logic.
- **Exceptions:** Contains custom exceptions for banking errors.
- **Util:** Contains reusable validation functionality.

## Learning Note

This project was developed as a hands-on learning project to strengthen my understanding of Core Java,Collection interfaces, exception handling and Object-Oriented Programming.

While building the application, I practiced organizing code into packages, implementing banking operations, handling exceptions, and separating responsibilities across different layers. This helped me understand how Java concepts are applied in a practical banking application.

I also used this project to practice Git and GitHub version control, including repository initialization, commits, and project management.