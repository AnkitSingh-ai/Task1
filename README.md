# Task 1: Database Setup and Schema Design

## Objective
The goal of this task was to design a relational database schema for an **E-commerce system**.

## Deliverables
1. **SQL Script** (`schema.sql`)  
   - Contains table creation commands with primary/foreign keys.
2. **ER Diagram** (`ER_Diagram.png`)  
   - Shows relationships between Users, Orders, Products, Categories, Payments, etc.

## Tools Used
- MySQL Workbench (can also be done with pgAdmin or SQLiteStudio)  
- GitHub for submission

## Entities
- Users
- Categories
- Products
- Orders
- Order_Items
- Payments

## Relationships
- One User → Many Orders  
- One Order → Many Products (via Order_Items)  
- One Product → One Category  
- One Order → One Payment  

## Outcome
A well-structured schema that ensures data integrity, normalization, and clear entity relationships.
