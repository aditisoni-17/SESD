# ER Diagram: Database Entities and Relationships

Although this milestone focuses on system design, the backend will eventually require persistence.

---

## Entities

### Users Table
- user_id (PK)
- name
- email

### Orders Table
- order_id (PK)
- user_id (FK)
- status
- created_at

### Payments Table
- payment_id (PK)
- order_id (FK)
- amount
- payment_status

### Products Table
- product_id (PK)
- name
- price
- stock

### OrderItems Table
- order_item_id (PK)
- order_id (FK)
- product_id (FK)
- quantity

---

## ER Diagram (Text Representation)

