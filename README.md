# Library Management System - Database Design

This repository contains the design of a database for a **Library Management System**. The project involves creating four models using **Draw.io**:
1. **ER Diagram**: Represents entities, relationships.
2. **Conceptual Model**: A high-level overview of the database structure represents entities, relationships, and attributes.
3. **Logical Model**: Defines tables, columns, primary keys, and foreign keys.
4. **Physical Model**: Represents the actual database schema, including data types and constraints.

All four models are included in a **single Draw.io file** with separate worksheets for each model.

---

## **Project Overview**

### **Objective**
The goal of this project is to design a database for a library system that supports the following functionalities:
1. **Track Books**: Store information about books, including title, author, ISBN, publisher, publication year, and genre.
2. **Manage Members**: Store information about members, including name, address, phone number, and email.
3. **Track Loans**: Track which books are borrowed by which members, along with the loan date and due date.
4. **Manage Publishers**: Store information about publishers, including name, address, and contact information.
5. **Generate Reports**: The system should be able to generate reports on overdue books, popular genres, and member activity.

---

## **Tasks Performed**

### **1. ER Diagram**
- Focuses on the main entities and their relationships.
- **ER Diagram**: Created an Entity-Relationship (ER) diagram using **Draw.io** to visually represent the entities and their relationships.

### **2. Conceptual Model**
- **Overview**:
  - A high-level representation of the database structure.
- **Entities Identified**:
  - **Books**: Title, Author, ISBN, PublisherID, PublicationYear, Genre.
  - **Members**: Name, Address, Phone, Email.
  - **Loans**: LoanID, MemberID, BookID, LoanDate, DueDate.
  - **Publishers**: Name, Address, ContactInfo.
- **Conceptual Diagram**: Created a conceptual model diagram using **Draw.io** to provide a clear understanding of the system's structure.

### **3. Logical Model**
- **Tables**:
  - **Books**: `BookID` (Primary Key), `Title`, `Author`, `ISBN`, `PublisherID` (Foreign Key), `PublicationYear`, `Genre`.
  - **Members**: `MemberID` (Primary Key), `Name`, `Address`, `Phone`, `Email`.
  - **Loans**: `LoanID` (Primary Key), `MemberID` (Foreign Key), `BookID` (Foreign Key), `LoanDate`, `DueDate`.
  - **Publishers**: `PublisherID` (Primary Key), `Name`, `Address`, `ContactInfo`.
- **Normalization**: The design is normalized to **Third Normal Form (3NF)**.
- **Logical Diagram**: Created a logical model diagram using **Draw.io** showing tables, columns, primary keys, and foreign keys.

### **4. Physical Model**
- **Database Schema**:
  - Defined data types for each column (e.g., `VARCHAR`, `INT`, `DATE`).
  - Added constraints (e.g., `NOT NULL`, `UNIQUE`).
  - Included indexes for performance optimization.
- **Physical Diagram**: Created a physical model diagram using **Draw.io** to represent the actual database schema.

---

## **Files in the Repository**
1. **Draw.io File**:
   - **File**: `LMS Database Design.drawio` 
   - **Description**: A single Draw.io file containing four worksheets:
     - **ER Diagram**: Represents entities, relationships.
     - **Conceptual Model**: A high-level overview of the database structure represents entities, relationships, and attributes.
     - **Logical Model**: Defines tables, columns, primary keys, and foreign keys.
     - **Physical Model**: Represents the actual database schema, including data types and constraints.
   - **How to Use**:
     - Open the file in [Draw.io](https://app.diagrams.net/).
     - Switch between worksheets to view the ER Diagram, Conceptual Model, Logical Model, and Physical Model.
2. **Database Design Task.pdf**:
   - **File**: `Database Design Task.pdf`.
   - **Description**: The original task document outlining the requirements, including sample data for the Books, Members, Loans, and Publishers tables.

---

## **How to Use This Repository**
1. **View the Diagrams**:
   - Download the `LMS Database Design.drawio` file and open it in Draw.io.
   - Use the worksheets to navigate between the **ER Diagram**, **Conceptual Model**, **Logical Model**, and **Physical Model**.
2. **Review the Sample Data**:
   - Open the **Database Design Task.pdf** file to explore the sample data provided for the Books, Members, Loans, and Publishers tables.
3. **Understand the Design**:
   - Use the ER Diagram, Conceptual Model, Logical Model, and Physical Model to understand the database structure and relationships.

---

## **Key Features of the Database Design**
1. **Entities and Relationships**:
   - The ER Diagram clearly defines the relationships between books, members, loans, and publishers.
2. **Normalization**:
   - The database design is normalized to **Third Normal Form (3NF)**, ensuring data integrity and reducing redundancy.
3. **Scalability**:
   - The design allows for easy expansion, such as adding new entities (e.g., librarians, genres) or attributes (e.g., book ratings, member status).

---

## **Tools Used**
- **Diagramming Tool**: [Draw.io](https://www.draw.io) for creating the ER Diagram, Conceptual Model, Logical Model, and Physical Model.
- **Sample Data**: Provided in the **Database Design Task.pdf** file.

---

## **Author**
Rama Hammad  
rama.hammad64@gmail.com
