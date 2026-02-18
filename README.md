# Portfolio — Egor Podverbnii

A small collection of university and personal projects focused on practical software engineering: Java application development (JavaFX, client–server, MVC), database work with Oracle SQL/PLSQL, automated testing, and basic embedded programming.

## Core Technologies
- **Java** (OOP, Streams, clean architecture)
- **JavaFX** (UI, event handling)
- **Client–Server** architecture
- **JDBC** (database access)
- **Testing:** JUnit, Mockito (unit / integration / system tests)
- **Databases:** Oracle **SQL/PLSQL** (materialized views, query optimization, data warehouse basics)
- **Tools:** Git (GitHub/GitLab), CI/CD (GitHub Actions, GitLab CI), Docker (basics)
- **Linux & Shell scripting**
- **C / C++:** RAII, ownership concepts (C++); embedded C on STM Nucleo

---

## Projects

### [Study Card App](https://github.com/cathees/studycards) (Java / JavaFX, Client–Server, JDBC, MVC)
A study/flashcard application built with Java and JavaFX. The project uses a **client–server** setup and an **MVC architecture** to keep UI, business logic, and data access cleanly separated. Persistence is implemented via **JDBC**.

**Highlights**
- JavaFX UI with MVC structure
- Client–server communication (separation of client and server responsibilities)
- Database persistence via JDBC (CRUD workflows)
- Focus on maintainable structure and testability

**Tech**
Java, JavaFX, JDBC, MVC, Git, CI/CD

---

### Test Suite for Study Card App (JUnit / Mockito)
An extensive automated test suite created to increase reliability and refactoring confidence. Covers multiple test levels and uses mocks where appropriate.

**Highlights**
- **Unit tests** for isolated logic
- **Integration tests** for combined components (e.g., DB/service boundaries)
- **System tests** for end-to-end flows
- Mocking with Mockito to control dependencies

**Tech**
JUnit, Mockito

---

### [Oracle SQL/PLSQL](res/UE12_13_Podverbnii.pdf) - Advanced Database Work
A collection of advanced SQL/PLSQL tasks and database concepts, with a focus on performance and analytics-oriented modeling.

**Highlights**
- Complex SQL queries and performance tuning
- **Materialized views**
- Query optimization and indexing concepts
- **Data warehouse basics** (e.g., star-schema ideas, reporting-friendly modeling)

**Tech**
Oracle SQL, PL/SQL

---

### Embedded C on STM Nucleo (Hardware Programming)
Small embedded programming exercises on an STM Nucleo board, focusing on low-level development and direct hardware interaction.

**Highlights**
- Peripheral-level programming and validation on hardware
- Structured C code for embedded environments

**Tech**
C, STM Nucleo, Linux tooling (where applicable)

---

### [C++ Fundamentals](https://github.com/cathees/cppchess) (RAII / Rule of 0/5)
Exercises and implementations focusing on safe resource management and modern C++ fundamentals.

**Highlights**
- Ownership and lifetime management
- RAII patterns
- Rule of 0 / Rule of 5 usage in class design

**Tech**
C++

---

## Contact
- GitHub: https://github.com/cathees
- Email: egorpod.ep@gmail.com

