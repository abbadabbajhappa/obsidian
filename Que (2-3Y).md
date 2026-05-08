# Core C# Questions

1. What is the difference between `class` and `struct`?
		A class is a reference type with reference semantics and heap allocation behavior, while a struct is a value type copied by value and typically stored inline. Structs are best for small immutable data; classes are better for complex shared objects.

2. Difference between:
    - `abstract class`
    - `interface`
3. What is dependency injection in .NET?
4. Explain:
    - `async`
    - `await`
    - Task-based programming
5. Difference between:
    - `Task`
    - `Thread`
    - `async/await`
6. What is `IEnumerable` vs `IQueryable`?
7. What are delegates and events?
8. What is LINQ? Difference between deferred and immediate execution?
9. Explain boxing and unboxing.
10. Difference between:
    - `ref`
    - `out`
    - `in`
11. What are extension methods?
12. What is garbage collection?
13. Difference between value type and reference type.
14. What are nullable reference types?
15. Explain SOLID principles with examples.

---

# ASP.NET Core Questions

1. Explain the request pipeline in ASP.NET Core.
2. What is middleware?
3. Difference between:
    - MVC
    - Web API
    - Minimal API
4. What is dependency injection lifecycle?
    - Singleton
    - Scoped
    - Transient
5. What is model binding?
6. What is routing?
7. Attribute routing vs conventional routing?
8. What is JWT authentication?
9. Difference between authentication and authorization?
10. How do you secure APIs?
11. What is Swagger/OpenAPI?
12. What are filters in ASP.NET Core?
13. Explain configuration management:

- `appsettings.json`
- environment variables
- secrets

14. What is logging in .NET?
15. What causes performance issues in APIs?

---

# Entity Framework Core Questions

1. What is Entity Framework Core?
2. Difference between:
    - `First()`
    - `FirstOrDefault()`
    - `Single()`
    - `SingleOrDefault()`
3. What is lazy loading vs eager loading?
4. Explain migrations.
5. What is change tracking?
6. Difference between:
    - `AsNoTracking()`
    - tracked entities
7. How do transactions work in EF Core?
8. What is the N+1 query problem?
9. Code First vs Database First?
10. How does LINQ get converted into SQL?

---

# SQL Questions Every .NET Dev Should Know

1. Difference between:
    - `DELETE`
    - `TRUNCATE`
    - `DROP`
2. What are joins?
    - INNER
    - LEFT
    - RIGHT
    - FULL
3. What is indexing?
4. Clustered vs non-clustered index?
5. What is normalization?
6. Explain primary key and foreign key.
7. What are stored procedures?
8. Difference between `WHERE` and `HAVING`.
9. What causes slow queries?
10. How do you optimize database performance?

---

# API & System Design Basics

1. What is REST?
2. What are HTTP methods?
    - GET
    - POST
    - PUT
    - PATCH
    - DELETE
3. Difference between PUT and PATCH?
4. What are status codes?
    - 200
    - 201
    - 400
    - 401
    - 403
    - 404
    - 500
5. What is caching?
6. What is rate limiting?
7. What is pagination?
8. How do microservices communicate?
9. What is API versioning?
10. How do you handle exceptions globally?

---

# Practical/Scenario-Based Questions

1. Your API is suddenly slow. How will you debug it?
2. A database query takes 15 seconds. What steps will you take?
3. Users report random `500` errors in production. What will you check first?
4. How would you design a login system?
5. How do you handle sensitive configuration values?
6. How would you improve application performance?
7. Explain a challenging bug you fixed recently.
8. What happens internally when an API request hits your server?
9. How would you implement file upload functionality?
10. How do you ensure backward compatibility in APIs?

---

# Multithreading & Performance

1. What is deadlock?
2. What is thread safety?
3. What is `lock` in C#?
4. What are concurrent collections?
5. Difference between synchronous and asynchronous programming?
6. When should you NOT use async?
7. What is connection pooling?

---

# Testing Questions

1. What is unit testing?
2. Difference between unit testing and integration testing?
3. Which frameworks have you used?
    - xUnit.net
    - NUnit
4. What is mocking?
5. What is dependency inversion in testing?

---

# DevOps / Real-World Questions

1. What is CI/CD?
2. Have you worked with:
    - Docker
    - Azure DevOps
    - GitHub Actions
3. Explain your Git workflow.
4. What is branching strategy?
5. How do you handle production deployments?

---

# Questions That Separate Average vs Strong Developers

1. Why should services be scoped carefully?
2. Why is `async void` dangerous?
3. Why can `IQueryable` be risky?
4. Why avoid business logic in controllers?
5. What are memory leaks in .NET?
6. What happens if DbContext is registered as Singleton?
7. Why should HttpClient not be created repeatedly?
8. Explain middleware order importance.
9. What is idempotency in APIs?
10. What is eventual consistency?

---

# Topics You SHOULD Know Well at 2–3 Years

A solid developer at this level is usually expected to know:

- C# fundamentals deeply
- ASP.NET Core APIs
- Entity Framework Core
- SQL basics + optimization
- Authentication/JWT
- Async programming
- Dependency Injection
- Git workflow
- API debugging
- Logging & exception handling
- Basic cloud/devops understanding
- Clean architecture basics