# Sequence Diagram: Main Order Flow (End-to-End)

## Scenario: User Places an Order Successfully

---

## Sequence Flow Steps

1. User places an order through API
2. Order Service publishes `OrderPlaced` event
3. Payment Service consumes event and processes payment
4. Payment Service publishes `PaymentCompleted` event
5. Inventory Service updates stock
6. Notification Service sends confirmation to user

---

## Sequence Diagram (Text Representation)

