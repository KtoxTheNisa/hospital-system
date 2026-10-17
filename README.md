# JavaFX & SQLite Hospital Appointment System

A modern desktop application designed to streamline the appointment process between doctors and patients. This project focuses on Object-Oriented Programming (OOP) principles and relational database management.

##  Key Features
- **Role-Based Access Control:** Separate, dynamic dashboards for Doctors and Patients.
- **Appointment Management:** Real-time scheduling, cancellation, and automated slot management.
- **Secure Authentication:** User login and registration with detailed input validation.
- **Polished UI:** A user-friendly interface styled with custom CSS for a modern look.

##  Tech Stack & Architecture
- **Language:** Java (JDK 21)
- **Framework:** JavaFX (FXML & CSS)
- **Database:** SQLite for relational data persistence.
- **Build Tool:** Maven for dependency and lifecycle management.
- **Design Pattern:** Implements **Factory Design Pattern** for flexible user creation.

##  Project Structure
- `models/`: Entity classes for Users, Doctors, Patients, and Appointments.
- `database/`: Data Access Objects (DAO) for SQLite CRUD operations.
- `ui/`: Controller classes managing JavaFX view logic.

##  Execution
1. Clone the repository.
2. Ensure the SQLite JDBC dependency is resolved via Maven.
3. Launch the application using Maven:
   ```bash
   mvn javafx:run
