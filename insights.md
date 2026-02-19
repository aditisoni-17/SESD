✅ Project Insights (My Understanding)

Insights Gained While Designing This System

While working on the idea of an Event-Driven Order Management System, I realized that building real-world backend systems is not just about writing APIs, but more about designing how different components communicate and scale.

1. Microservices Improve Maintainability

Instead of keeping everything in one large monolithic backend, splitting the system into services like:

Order Service

Payment Service

Inventory Service

Notification Service

makes the application easier to manage, extend, and debug. Each service has a single responsibility.

2. Event-Driven Architecture Reduces Tight Coupling

In traditional systems, services directly call each other, which creates dependency issues.

Using Kafka-style events such as:

OrderPlaced

PaymentCompleted

StockUpdated

helps services stay independent. They only react to events rather than knowing internal details of other services.

3. Asynchronous Communication is Industry Standard

Real platforms like Amazon or Swiggy cannot process everything synchronously because that would slow down the user experience.

Event-driven flow ensures:

Faster response time

Better scalability

Smooth handling of high traffic

4. OOP Makes System Design Cleaner

Implementing the system with proper OOP concepts gave a better structure:

Encapsulation helped keep service logic separate

Abstraction through interfaces made components reusable

Polymorphism allowed multiple payment strategies

Inheritance supported common event structures

This made the codebase more modular and professional.

5. Design Patterns Naturally Fit Backend Systems

Instead of forcing patterns, I noticed they naturally appear:

Observer Pattern → Event subscription

Strategy Pattern → Different payment modes

Singleton Pattern → One EventBus instance

Factory Pattern → Event object creation

This improved flexibility and readability.

6. System Design is More Than Coding

This milestone helped me understand that software engineering starts with:

Use case planning

Sequence flow design

Class relationships

Database modeling

Implementation becomes much easier once the architecture is clear.

Conclusion

Overall, designing this project gave me a strong understanding of how distributed systems work in real companies. It also improved my confidence in backend system design, OOP structuring, and event-driven thinking.

If you want, I can also write a short “Reflection.md” or a README Insights section that looks super authentic for submission 💯

the insight needs to look like i made it for myself and my understanging of thr porjct

Got it 🫂
You want it to sound really personal, like you actually sat and thought about the project yourself, not like a polished article.

Here’s a more natural, student-style version — like your own notes and understanding:

✅ My Insights / What I Understood From This Project

While finalizing my SESD project idea, I understood that building an Order Management System is not just about creating APIs, but more about designing how the whole backend behaves like a real industry system.

1. Why I Chose Event-Driven Architecture

Initially I thought services can directly call each other, but then I realized that in real applications, this creates too much dependency.

Using an event-driven approach (Kafka style) makes more sense because services don’t need to know each other internally.
They only communicate through events like:

OrderPlaced

PaymentCompleted

StockUpdated

This feels much closer to how Amazon/Swiggy type systems actually work.

2. Services Should Be Independent

By separating Order, Payment, Inventory, and Notification into different services, I understood that each service has its own responsibility.

For example:

Order service should not handle payment logic

Inventory service should only focus on stock updates

This makes the system cleaner and scalable.

3. Importance of Async Processing

One major learning for me was that real systems cannot process everything synchronously.

If payment takes time, the order service should not be blocked.
That’s why events and asynchronous flow are important.

This improves performance when many users place orders at the same time.

4. OOP Fits Naturally in System Design

Since the project is in TypeScript, I saw how OOP concepts directly help in structuring the backend:

Classes like Order, Payment, Product make the design clear

Interfaces help in abstraction

Polymorphism helps in supporting multiple payment methods

Overall, OOP makes the architecture more professional.

5. Design Patterns Are Actually Useful

I always thought design patterns are theoretical, but while designing this system I noticed they come naturally:

Observer Pattern → event subscribers

Strategy Pattern → different payment modes

Singleton → one EventBus

Factory → event creation

So patterns are not forced, they solve real problems.

6. System Design Comes Before Implementation

This milestone made me realize that software engineering is not only coding.

Before writing actual code, it is important to think about:

Use cases

Main sequence flow

Class relationships

Database structure

Once diagrams are clear, implementation becomes much easier.

Final Understanding

Through this project idea, I gained a better understanding of how distributed backend systems work in real companies, and how event-driven microservices are used for scalable applications.