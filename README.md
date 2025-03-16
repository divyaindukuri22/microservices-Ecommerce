# microservices-Ecommerce

## Features
- **Product Service:** Manage product details with CRUD operations.
- **Customer Service:** Manage customer data.
- **Order Service:** Handle orders and order items.
- **Payment Service:** Manage payment transactions.
- API documentation using **Swagger UI**.

## Technologies Used
- **Java 17**
- **Spring Boot**
- **Spring Web**, **JPA**, **Actuator**
- **H2 Database** (In-memory)
- **Swagger** (API Documentation)

## Installation and Setup
1. **Clone the Repository**
```bash
git clone https://github.com/your-username/online-shopping-app.git
cd online-shopping-app
```

2. **Build the Project**
```bash
./mvnw clean install
```

3. **Run Each Service**
- **Product Service:**
```bash
cd product-service
./mvnw spring-boot:run
```
- **Customer Service:**
```bash
cd customer-service
./mvnw spring-boot:run
```

## API Endpoints
### **Product Service** (Port: `8081`)
- **POST** `/api/products` → Add a new product
- **GET** `/api/products` → Get all products
- **GET** `/api/products/{id}` → Get product by ID
- **PUT** `/api/products/{id}` → Update product
- **DELETE** `/api/products/{id}` → Delete product

### **Customer Service** (Port: `8082`)
- **POST** `/api/customers` → Add a new customer
- **GET** `/api/customers` → Get all customers
- **GET** `/api/customers/{id}` → Get customer by ID
- **PUT** `/api/customers/{id}` → Update customer
- **DELETE** `/api/customers/{id}` → Delete customer
