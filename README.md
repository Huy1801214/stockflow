# StockFlow – Inventory & Order Management System

> A Microservices-based Inventory & Order Management System built with Java Spring Boot and Apache Kafka.

## 1. Overview

**StockFlow** is a backend-focused project designed to manage inventory, orders, warehouses, procurement, and related business operations.

The system aims to provide a centralized solution for retail businesses to manage products, track inventory across multiple warehouses, process customer orders, and coordinate purchasing activities.

This project is also an opportunity to explore and apply software engineering principles, Microservices Architecture, Clean Architecture, and Distributed Systems concepts through a practical business scenario.

## 2. Project Goals

The main goals of this project are:

- Build a practical backend system based on real-world business requirements.
- Apply Java and Spring Boot to develop scalable backend services.
- Explore Microservices Architecture and service-to-service communication.
- Apply Clean Architecture to organize business logic and infrastructure.
- Learn Event-Driven Architecture using Apache Kafka.
- Understand distributed systems challenges such as data consistency, concurrency, fault tolerance, and reliable message processing.
- Practice software engineering workflows, testing, containerization, and deployment.

## 3. Key Features

<img width="1236" height="562" alt="image" src="https://github.com/user-attachments/assets/6ae72fa6-2320-465d-aa22-7e7dc908fb45" />

## 4. System Architecture

### Target Architecture

StockFlow is planned to follow a Microservices Architecture, where each service is responsible for a specific business capability.

The initial service decomposition is:

| Service | Responsibility | Status |
|---|---|---|
| Product Service | Product and category management | Planned |
| Inventory Service | Inventory tracking and stock reservation | Planned |
| Order Service | Order creation and lifecycle management | Planned |
| Procurement Service | Supplier and purchasing management | Planned |
| Payment Service | Payment processing and transaction management | Planned |
| Shipping Service | Shipment and delivery management | Planned |
| Notification Service | Notification delivery | Planned |

### Architectural Principles

The following architectural approaches are planned:

- **Microservices Architecture:** Organize the system into independently responsible services.
- **Clean Architecture:** Separate domain logic, application use cases, and infrastructure concerns.
- **Domain-Driven Design (DDD):** Model business domains and define clear service boundaries.
- **Event-Driven Architecture:** Use asynchronous events for communication between services.

*System architecture and service boundaries: Planned.*

## 5. Technology Stack

The following technologies are selected as the initial target stack. Their actual implementation is planned.

| Category | Technology | Status |
|---|---|---|
| Programming Language | Java | Planned |
| Backend Framework | Spring Boot | Planned |
| API Gateway | Spring Cloud Gateway | Planned |
| Messaging | Apache Kafka | Planned |
| Database | PostgreSQL | Planned |
| Caching | Redis | Planned |
| ORM | Spring Data JPA / Hibernate | Planned |
| Containerization | Docker & Docker Compose | Planned |
| Monitoring | Prometheus & Grafana | Planned |
| Testing | JUnit 5, Mockito, Testcontainers | Planned |

## 6. Core Business Workflows

The system is planned to support the following end-to-end workflows.

### 6.1 Procurement & Goods Receiving

1. Create a purchase order.
2. Select a supplier and add products.
3. Track the purchase order status.
4. Receive goods at a warehouse.
5. Update inventory quantities.

**Status:** Planned

### 6.2 Order Creation & Inventory Reservation

1. Customer places an order.
2. Order Service creates the order.
3. Inventory Service checks product availability.
4. Inventory Service reserves the required stock.
5. Order proceeds to payment processing.

**Status:** Planned

### 6.3 Payment & Order Fulfillment

1. Process the customer's payment.
2. Handle payment success or failure.
3. Confirm or cancel the order.
4. Commit or release the inventory reservation.
5. Prepare the shipment.

**Status:** Planned

### 6.4 Shipping & Notification

1. Create a delivery request.
2. Track shipment status.
3. Update order delivery information.
4. Notify customers about important order updates.

**Status:** Planned

## 7. Project Structure

The repository will initially contain project documentation. Source code and service implementations will be added as development progresses.

```text
stockflow/
├── README.md
├── docs/
│   ├── business-requirements/
│   ├── architecture/
│   ├── database/
│   ├── workflows/
│   └── diagrams/
└── services/
    └── (planned)
```
