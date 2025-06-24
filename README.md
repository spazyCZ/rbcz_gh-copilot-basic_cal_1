# Demo app for the github copilot training course
This is a simple demo app to showcase the capabilities of GitHub Copilot.
Web application built with Python Flask

Application is **CALCULATOR** that can perform basic arithmetic operations.

## Features
REST API with the following endpoints:
- `GET /add`: Adds two numbers
- `GET /subtract`: Subtracts two numbers
- `GET /multiply`: Multiplies two numbers
- `GET /divide`: Divides two numbers

```mermaid
graph TD
    A[app.py<br/>Flask App] --> B1[/calculator/add<br/>POST/]
    A --> B2[/calculator/subtract<br/>POST/]
    A --> B3[/calculator/multiply<br/>POST/]
    A --> B4[/calculator/divide<br/>POST/]
    A --> C1[/greet<br/>GET/]
    A --> C2[/hello<br/>GET/]
    A --> D[Logging & Performance<br/>Middleware]
    A --> E[Swagger Docs]
    A --> F[test_app.py<br/>Tests]
    F --> G1[Mock Tests]
    F --> G2[Integration Tests]
```
