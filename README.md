# eSuggestion-System-Spring-boot-backend-CRUD-operation


# 📚 Campus Navigation & Suggestion Backend

This is a Spring Boot backend project for managing campus suggestions. It includes a RESTful API for handling suggestions, employees, and suggestion types with full CRUD functionality.

---

## 🚀 Features

- ✅ **Suggestion Management**
  - CRUD operations for suggestions
  - Each suggestion is linked to an employee
  - Filter by suggestion type

- ✅ **Employee Management**
  - Manage employee records
  - Suggestions are created by employees

- ✅ **Suggestion Type Support**
  - Categorize suggestions by type (e.g., infrastructure, academics, etc.)

- 🗂️ **Database Integration**
  - MySQL database using Spring Data JPA
  - Entity relationships (Employee ↔ Suggestion ↔ SuggestionType)

- 🧪 **Error Handling**
  - Handles common HTTP exceptions gracefully
  - JSON serialization safeguards (e.g., max nesting depth)

---

## 📦 Tech Stack

- **Backend**: Java 17, Spring Boot
- **Database**: MySQL + Spring Data JPA (Hibernate)
- **Build Tool**: Maven



