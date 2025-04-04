#🐾 PetStoreApp

PetStoreApp is a Java-based backend application that manages pet store locations, employees, and customers. Built with Spring Boot and Spring Data JPA, this project allows users to perform full CRUD operations on pet stores, as well as create and retrieve employee and customer records.

---

##📌 Features

###CRUD operations on PetStore
   - Create a new pet store
   - Retrieve all pet stores or a specific one by ID
   - Update pet store details
   - Delete a pet store  
   
###Employee management
   - Create a new employee
   - Find an existing employee by ID
   
###Customer management
   - Create a new customer
   - Find an existing customer by ID
    
---    
    
##🧱 Entities

###🏪 PetStore
   - Represents a pet store location.
   - Includes relevant details such as name, address, etc.
   
###👤 Employee
   - Represents a staff member working at a pet store.
   - Each employee can be associated with a specific store.
   
###🐶 Customer
   - Represents a customer who interacts with the pet store.
   - Customer data includes identifying details like name and contact information.
    
---    
    
##⚙️ Technologies Used

   - Java
   - Spring Boot
   - Spring Data JPA
   - Maven
    
---    
    
##▶️ Getting Started

1. Clone the repository  

     - git clone https://github.com/sflugum/PetStoreApp.git
     - cd PetStoreApp

2. Build and run the app

     - ./mvnw spring-boot:run  

3. Access the API

    - PetStore endpoints: http://localhost:8080/petstores
    - Employee endpoints: http://localhost:8080/employees
    - Customer endpoints: http://localhost:8080/customers
    
---    
    
##📬 API Endpoints Overview

###Here are some example endpoints:

  - GET /petstores – List all pet stores
  - POST /petstores – Create a new pet store
  - PUT /petstores/{id} – Update an existing pet store
  - DELETE /petstores/{id} – Delete a pet store
  - GET /employees/{id} – Find an employee
  - POST /employees – Create a new employee
  - GET /customers/{id} – Find a customer
  - POST /customers – Create a new customer
  
---  

##🚀 Future Enhancements

###Here are some planned or potential improvements for future versions of PetStoreApp:

  - Advanced Queries
      - Search for customers by name or contact info.
      - Filter pet stores by city, state, or services offered.
  - Data Validation & Error Handling
      - Implement detailed validation rules for incoming data.
      - Provide user-friendly error responses with helpful messages.
  
---

Developed by Silas Flugum ⚜️    
Contact: https://github.com/sflugum  

