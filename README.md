# Pokedex App 🐾

A Flutter-based Pokedex application powered by [PokeAPI](https://pokeapi.co). This app is currently a **Work in Progress**.

---

## Features
- Fetch and display Pokémon data from PokeAPI.
- Clean and structured codebase following **Clean Architecture** principles.
- Robust testing with:
  - **Unit Tests**
  - **Integration Tests**
  - **Widget Tests**
  - **Golden Tests**
- Implements **Dependency Injection** for scalable and maintainable code.
- Uses **BLoC** for state management.

---

## Software Architecture
The app follows **Clean Architecture** to ensure modularity and separation of concerns. It consists of three main layers:

1. **Data Layer**:
   - Responsible for interacting with the PokeAPI and mapping responses.
   - Includes repositories and data sources.

2. **Domain Layer**:
   - Defines core business logic and entities.
   - Contains use cases for Pokémon-related operations.

3. **Presentation Layer**:
   - Manages UI and user interactions.
   - Uses **BLoC** for reactive state management.

---

## State Management
This app uses the **BLoC** (Business Logic Component) library to handle state management, ensuring a predictable state flow and testability.

---

## Testing
The app employs a **Test-Driven Development (TDD)** approach, leveraging tools such as:
- **Mocktail**: For mocking dependencies.
- **flutter_bloc_test**: For testing BLoC logic.
- Comprehensive testing coverage, including:
  - Unit tests for business logic.
  - Integration tests for API and data layer validation.
  - Widget tests for UI behavior.
  - Golden tests for UI snapshots.

### **Screen-Record**

https://github.com/user-attachments/assets/5a6008b1-4a82-4390-8adf-b3071a884b48


---
## Contact

For any inquiries or feedback, please reach out to **[gabbernardo20@gmail.com]**.
