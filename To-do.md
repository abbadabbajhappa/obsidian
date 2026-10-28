Should be done by 15 days, target 15th Nov

Core C#

Must know clearly:

OOP
abstraction
encapsulation
inheritance
polymorphism
C# concepts
class vs struct
value vs reference type
stack vs heap
string immutability
boxing/unboxing
ref/out/in

delegates/events
delegate is a type safe function pointer i.e. it holds reference(pointer) to a function
multicast delegate -> holds the reference of more than one function
anonymous delegate -> delegates pointing methods without name

What is RequestDelegate?
RequestDelegate is a delegate representing the next component in the ASP.NET Core request pipeline.
It accepts an HttpContext and returns a Task. Middleware invokes it to pass the request to the next component.

What is _next, and why do we call _next(context)?
_next is a RequestDelegate representing the next component in the ASP.NET Core request pipeline. 
We call _next(context) to pass the current HttpContext to that next component so it can continue processing the request.

lambda expressions
LINQ
generics
IEnumerable vs IQueryable
async/await
Task vs Thread
IDisposable
garbage collection

ASP.NET Core

Must know:

middleware pipeline
dependency injection
appsettings
configuration
logging
authentication vs authorization
JWT
filters
REST API principles
exception handling
caching basics

Entity Framework / DB

Must know:

LINQ translation
tracking vs no-tracking
eager/lazy loading
migrations
indexing
joins
stored procedures
transactions
normalization basics

SQL (VERY IMPORTANT)

Many .NET devs fail here.

Practice:

joins
group by
ranking
indexing
execution basics
optimization basics