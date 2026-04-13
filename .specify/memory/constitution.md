<!--
Sync Impact Report
Version change: none → 1.0.0
List of modified principles: All principles added (Security-First, User-Centric Design, Data Integrity and Performance, Testability and Quality, Simplicity and Training Focus)
Added sections: Core Principles, Additional Constraints, Development Workflow, Governance
Removed sections: None
Templates requiring updates: None (no constitution references found in plan-template.md, spec-template.md, tasks-template.md, or commands)
Follow-up TODOs: None
-->

# ContosoDashboard Constitution
<!-- Example: Spec Constitution, TaskFlow Constitution, etc. -->

## Core Principles

### I. Security-First
Authentication and authorization are paramount; implement defense in depth with role-based access control, IDOR protection, secure coding practices, and proper input validation. Use mock authentication for training but follow production-ready patterns with claims-based identity and hierarchical permissions.

### II. User-Centric Design
All features prioritize user experience and accessibility; dashboard, profiles, notifications, and UI components tailored to user roles and needs. Ensure responsive design, clear navigation, and intuitive workflows.

### III. Data Integrity and Performance
Use Entity Framework Core with proper relationships, indexes, and migrations for data consistency and referential integrity. Optimize database queries, implement caching where appropriate, and ensure scalable performance for concurrent users.

### IV. Testability and Quality
Enable nullable references, async/await patterns, and clean architecture for maintainable, testable code. Follow separation of concerns with service layers, dependency injection, and comprehensive error handling.

### V. Simplicity and Training Focus
Maintain offline-first design with no external dependencies for training purposes. Use abstractions and interfaces to enable seamless migration to cloud services (Azure SQL, Blob Storage, Entra ID) while keeping the codebase simple and educational.

## Additional Constraints

Technology Stack: .NET 10 with Blazor Server, SQL Server (LocalDB for training), Bootstrap 5, ASP.NET Core Identity patterns.  
Compliance: Training application only - not for production use. Known limitations include mock authentication and simplified security.  
Performance: Target <2s page load times, support 100+ concurrent users in training scenarios.  
Deployment: Local development only; production would require Azure App Service, SQL Database, and proper authentication.

## Development Workflow

Feature development follows Spec-Driven Development using GitHub Spec Kit: create specs, plans, tasks, and checklists. Use EF Core migrations for database schema changes. Implement code reviews, testing, and validation before merging. Commit after each task completion.

## Governance
Constitution supersedes all other practices; all decisions must align with core principles. Amendments require documentation, team consensus, and migration plan. Complexity must be justified with simpler alternatives considered. Use this constitution for runtime development guidance.

**Version**: 1.0.0 | **Ratified**: 2026-04-13 | **Last Amended**: 2026-04-13

## Core Principles

### I. Security-First
Authentication and authorization are paramount; implement defense in depth with role-based access control, IDOR protection, secure coding practices, and proper input validation. Use mock authentication for training but follow production-ready patterns with claims-based identity and hierarchical permissions.

### II. User-Centric Design
All features prioritize user experience and accessibility; dashboard, profiles, notifications, and UI components tailored to user roles and needs. Ensure responsive design, clear navigation, and intuitive workflows.

### III. Data Integrity and Performance
Use Entity Framework Core with proper relationships, indexes, and migrations for data consistency and referential integrity. Optimize database queries, implement caching where appropriate, and ensure scalable performance for concurrent users.

### IV. Testability and Quality
Enable nullable references, async/await patterns, and clean architecture for maintainable, testable code. Follow separation of concerns with service layers, dependency injection, and comprehensive error handling.

### V. Simplicity and Training Focus
Maintain offline-first design with no external dependencies for training purposes. Use abstractions and interfaces to enable seamless migration to cloud services (Azure SQL, Blob Storage, Entra ID) while keeping the codebase simple and educational.

## Additional Constraints

Technology Stack: .NET 10 with Blazor Server, SQL Server (LocalDB for training), Bootstrap 5, ASP.NET Core Identity patterns.  
Compliance: Training application only - not for production use. Known limitations include mock authentication and simplified security.  
Performance: Target <2s page load times, support 100+ concurrent users in training scenarios.  
Deployment: Local development only; production would require Azure App Service, SQL Database, and proper authentication.

## Development Workflow

Feature development follows Spec-Driven Development using GitHub Spec Kit: create specs, plans, tasks, and checklists. Use EF Core migrations for database schema changes. Implement code reviews, testing, and validation before merging. Commit after each task completion.

## Governance
Constitution supersedes all other practices; all decisions must align with core principles. Amendments require documentation, team consensus, and migration plan. Complexity must be justified with simpler alternatives considered. Use this constitution for runtime development guidance.

**Version**: 1.0.0 | **Ratified**: 2026-04-13 | **Last Amended**: 2026-04-13
