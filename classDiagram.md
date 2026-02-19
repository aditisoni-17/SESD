# Class Diagram: Major Classes and Relationships

## Core Classes

### Order
- orderId
- userId
- items
- status

### Payment
- paymentId
- orderId
- amount
- paymentStatus

### Product
- productId
- name
- price
- stock

### EventBus (Singleton)
- publish(event)
- subscribe(eventType, handler)

---

## Interfaces

### IEvent
- eventType
- payload

### IEventHandler
- handle(event)

### PaymentStrategy
- pay(amount)

---

## Class Diagram (Text Representation)

