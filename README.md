👥 Human Resource System – WCF (SOAP & REST) Application

An enterprise-level Human Resource Management System (HRMS) developed using C# and Windows Communication Foundation (WCF).
This project showcases a service-oriented architecture (SOA) that exposes both SOAP and RESTful endpoints for seamless integration with multiple clients (web, mobile, or desktop).

--------------------------

🏗️ Overview

The Human Resource System WCF Application is designed to provide secure and efficient HR-related operations over service interfaces.
It supports both SOAP-based services for legacy integrations and REST-based services for modern applications — all within a single unified WCF solution.

This project demonstrates how to build, host, and consume WCF services that manage employees, departments, attendance, and payroll data using a clean, extensible design.

---------------------------

🚀 Key Features
🧩 Service Architecture

Dual endpoints: SOAP (XML-based) and REST (JSON-based)

Service contracts, data contracts, and operation contracts implemented using C# interfaces

Configurable bindings and endpoints via App.config / Web.config

👩‍💼 Employee & Department Management

Add, update, delete, and retrieve employee records

Manage departments, designations, and employee assignments

🕒 Attendance & Leave Tracking

Record attendance and leaves for employees

Retrieve summaries via REST or SOAP calls

💰 Payroll Processing

Calculate and manage employee salaries

Generate payroll data through service operations

🔒 Security & Extensibility

Basic HTTP authentication support

Configurable endpoints for multiple clients (desktop, web, mobile)

Layered structure for scalability and maintainability

--------------------------------

🧱 Technologies Used
| Category                   | Technology                                           |
| -------------------------- | ---------------------------------------------------- |
| **Language**               | C#                                                   |
| **Framework**              | .NET Framework 4.8 / .NET 8 (with WCF Compatibility) |
| **Service Framework**      | Windows Communication Foundation (WCF)               |
| **Protocols Supported**    | SOAP (XML), REST (JSON)                              |
| **Data Access (Optional)** | Entity Framework / ADO.NET / Mock Repository         |
| **Architecture**           | N-Tier, Service-Oriented Architecture (SOA)          |

-----------------------------

▶️ How to Run
🖥️ Option 1: Host on IIS

Open the solution in Visual Studio

Right-click the HRSystem.Host project → Set as Startup Project

Update base addresses in Web.config

Run the project — WCF services will start and be accessible via browser or Postman

💻 Option 2: Self-Host in Console

Open HRSystem.Host/Program.cs

Run the console application

Services will be hosted locally (e.g., http://localhost:8080/EmployeeService)

---------------------------------

🔮 Future Enhancements

Integrate JWT or OAuth 2.0 authentication

Add Swagger/OpenAPI documentation for REST endpoints

Implement database persistence with EF Core

Add unit tests and integration tests

Containerize with Docker for microservice deployment
