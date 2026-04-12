
Controllers

Models - Database structure

DTOs (data transfer objects) - API contract

Data - AppDbContext - connects app to database and also defines tables

Repositories - handles db operation / data handler

Services - business logic

Middleware - pipeline controller

Program.cs - root startup file (register services, configure db, setup middleware, enable authentication) - also known as wiring system