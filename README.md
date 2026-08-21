Hi, I'm Dor 👋

I'm a backend developer with a background in Management Information Systems, focused on C#/.NET. I build backend systems and reusable .NET libraries around ASP.NET Core, REST APIs, SQL Server, external integrations, and validation heavy business logic. I care about code that stays clear and testable long after the first release: thin APIs, strong domain logic, clean architecture boundaries, and tests that protect real behavior instead of just passing.

🚀 What I'm building

RosterPilot (public repo: Aether.TaskProcessor) is a production scheduling system I designed and built end to end for a real operations manager at the Courts Administration of Israel. It replaced a manual scheduling process that used to take up to five working days with a run that now takes about an hour.

It's a WPF hosted Blazor desktop app built on Clean Architecture, with a custom genetic optimization engine that turns Excel based worker availability and constraints into a full biweekly schedule. The system tracks its own run lifecycle and keeps approval locked while critical violations are unresolved, so it never reports success for work that didn't actually finish. It's backed by 395 automated tests, and I use AI coding tools like Claude and Copilot daily as part of the build, though every line ships only after I've reviewed it myself.

What I work on
- Backend development with C#/.NET and ASP.NET Core
- REST API design, validation, authentication, and error handling
- SQL Server persistence and clean data access
- External API integrations with structured request and response handling
- Clean Architecture, OOP, SOLID, and dependency injection
- xUnit testing across Domain, Application, Infrastructure, and API layers
- Azure integrations such as Document Intelligence and Blob Storage
- Swagger/OpenAPI documentation for developer friendly APIs

Selected projects

InvoiceFlow
A .NET invoice processing API that turns uploaded invoice documents into structured, validated results. Built with ASP.NET Core, SQL Server, Clean Architecture, Azure Document Intelligence, Azure Blob Storage, API key protection, rate limiting, and xUnit coverage.

TravelPricingGateway
An ASP.NET Core hotel pricing API that validates hotels through SQL Server, calls multiple pricing providers in parallel, and returns the cheapest successful result across both JSON and legacy XML provider formats.

BusinessJournal
An end to end customer and appointment management system built with ASP.NET Core, Blazor, and SQL Server. Scheduling conflicts can't happen because the rule lives in one place, backed by JWT authentication and 91 automated tests.

FluentRestClient
A small C# library for clean, fluent REST API calls, covering request configuration, headers, Basic Auth, and both sync and async response handling.

Currently
Looking for a C#/.NET backend developer role where I can work on real systems with a strong engineering team and keep growing through practical, production minded development.
