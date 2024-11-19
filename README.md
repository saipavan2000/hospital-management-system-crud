# Hospital Management System

The Hospital Management System is a comprehensive solution designed to streamline hospital operations. Developed using **Java Spring Boot**, the system allows for efficient management of patient records, doctor schedules, and appointments. The platform supports seamless **CRUD (Create, Read, Update, Delete)** operations for managing hospital data.

## Key Features

- **Patient Management**:
  - Manage patient records efficiently with the ability to create, update, and view patient details.

- **Appointment Scheduling**:
  - Patients can book, update, and cancel appointments easily.

- **CRUD Operations**:
  - Implemented for patient records, doctor schedules, and appointments for smooth hospital workflow.

- **Backend**: 
  - Built using **Spring Boot** for robust and scalable server-side functionality.

- **Frontend**: 
  - Developed with **Angular** to provide an intuitive user interface for both admins and users.

- **Database**: 
  - Integrated **MySQL** for reliable data storage and efficient query processing.

## Tech Stack

- **Backend**: Spring Boot
- **Frontend**: Angular
- **Database**: MySQL

## Installation

### Prerequisites

Ensure you have the following installed:

- [Java 8+](https://adoptopenjdk.net/)
- [Node.js and npm](https://nodejs.org/)
- [MySQL](https://dev.mysql.com/downloads/installer/)

### Setup Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/hospital-management-system.git
   cd hospital-management-system
   ```

2. **Backend (Spring Boot)**:
   - Navigate to the backend folder and run the Spring Boot application:
   
     ```bash
     cd Backend_SpringBoot
     mvn spring-boot:run
     ```

   - Ensure that your MySQL database is running and configure the `application.properties` file with your MySQL credentials.

3. **Frontend (Angular)**:
   - Navigate to the frontend folder and install the necessary dependencies:
   
     ```bash
     cd Fronted_Angular/projectfrontend
     npm install
     ```

   - After installation, start the Angular development server:
   
     ```bash
     ng serve
     ```

   - The application will be available at `http://localhost:4200`.
