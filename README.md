E-Commerce Backend API (.NET 8 – Clean Architecture)

-A scalable and maintainable E-Commerce backend system built using ASP.NET Core 8 following Clean Architecture principles.
-- Features
Product & Catalog Management
Product CRUD operations
Category management
Product filtering & pagination
Stock handling
-- Shopping System
Shopping cart management
Add / remove items
Cart persistence per user
Order creation flow
--Order Processing
Order creation & tracking
Order status lifecycle (Pending → Paid → Shipped → Delivered)
Order history per user
--Authentication & Authorization
JWT Authentication
Refresh Token mechanism
Role-based authorization (Admin / User)
Secure endpoints
--Payment Integration
Stripe payment gateway integration
Secure checkout flow
Payment confirmation handling
--Mapping & Architecture
AutoMapper integration
DTO-based communication
Separation of Concerns (Entities vs DTOs)
Clean Architecture (Domain / Application / Infrastructure / API)
--Architecture Highlights
Clean Architecture structure
Repository & Unit of Work pattern
Middleware (Error handling, Logging)
Validation using FluentValidation (if used)
Scalable and maintainable project structure
