# school-management-system
Console-based School Management System demonstrating OOP and SOLID principles

# 🏫 School Management System

[![Java](https://img.shields.io/badge/Java-17-blue.svg)](https://www.oracle.com/java/)
[![Maven](https://img.shields.io/badge/Maven-3.8+-red.svg)](https://maven.apache.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Console-based School Management System demonstrating **Object-Oriented Programming (OOP)** and **SOLID** design principles.

---

## 📖 Project Overview

This project is an educational application designed to showcase:
- ✅ **OOP Pillars**: Encapsulation, Inheritance, Polymorphism, Abstraction
- ✅ **SOLID Principles**: Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion
- ✅ **Design Patterns**: Factory, Strategy, Dependency Injection
- ✅ **3-Tier Architecture**: UI → Service → Entity layers
- ✅ **Test-Driven Development (TDD)**: 90%+ code coverage

---

## 🚀 Features

- **Student Management**: Add, view, update, remove students
- **Teacher Management**: Manage faculty records
- **Course Management**: Create courses, assign teachers
- **Enrollment System**: Enroll students in courses with capacity management
- **Reporting**: Generate various system reports
- **Role-Based Access**: Admin, Teacher, Student dashboards

---

## 🛠️ Tech Stack

- **Language**: Java 17
- **Build Tool**: Maven 3.8+
- **Testing**: JUnit 5, Mockito
- **Code Coverage**: JaCoCo
- **IDE**: IntelliJ IDEA

---

## 📋 Prerequisites

- Java JDK 17 or higher
- Maven 3.8 or higher
- IntelliJ IDEA (recommended) or any Java IDE

---

## 🔧 Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/school-management-system.git
cd school-management-system
```

### 2. Build Project
```bash
mvn clean compile
```

### 3. Run Tests
```bash
mvn test
```

### 4. Generate Coverage Report
```bash
mvn jacoco:report
```

Open `target/site/jacoco/index.html` in browser.

### 5. Run Application
```bash
mvn exec:java -Dexec.mainClass="com.school.Main"
```

Or build JAR and run:
```bash
mvn clean package
java -jar target/school-management-system-1.0.0.jar
```

---

## 📁 Project Structure
```
src/
├── main/java/com/school/
│   ├── entities/      # Domain models (Person, Student, Teacher, Course)
│   ├── services/      # Business logic layer
│   ├── ui/            # Console interface
│   ├── exceptions/    # Custom exception hierarchy
│   ├── utils/         # Helper classes
│   ├── patterns/      # Design pattern implementations
│   └── Main.java      # Application entry point
└── test/java/com/school/
    ├── entities/      # Entity unit tests
    ├── services/      # Service integration tests
    └── utils/         # Utility tests
```

---

## 📚 Documentation

- [Product Requirements Document (PRD)](docs/requirements/PRD.md)
- [Software Requirements Specification (SRS)](docs/requirements/SRS.md)
- [User Stories](docs/requirements/UserStories.md)
- [Software Design Document (SDD)](docs/design/SDD.md)

---

## 🧪 Testing

### Run All Tests
```bash
mvn test
```

### Run Specific Test Class
```bash
mvn test -Dtest=StudentServiceTest
```

### Check Code Coverage
```bash
mvn jacoco:report
```

**Coverage Targets:**
- Entity Layer: 90%+
- Service Layer: 95%+
- Overall: 85%+

---

## 🎯 Development Workflow

This project follows **Test-Driven Development (TDD)**:

1. ❌ **RED**: Write failing test
2. ✅ **GREEN**: Write minimal code to pass
3. 🔄 **REFACTOR**: Improve code quality

See [Development Guide](docs/development-guide.md) for details.

---

## 🏗️ Architecture

**3-Tier Layered Architecture:**
```
┌─────────────────┐
│   UI Layer      │ ← Console menus, user interaction
├─────────────────┤
│ Service Layer   │ ← Business logic, validation
├─────────────────┤
│  Entity Layer   │ ← Domain models, data
└─────────────────┘
```

**SOLID Compliance:**
- Each service has single responsibility (SRP)
- New features added via extension (OCP)
- Dependency injection throughout (DIP)

---

## 📊 Current Status

🚧 **In Development** - Sprint 1 (Entity Layer)

**Completed:**
- ✅ Project setup
- ✅ Documentation (PRD, SRS, User Stories, SDD)
- ✅ Architecture design

**In Progress:**
- 🔄 Entity layer implementation
- 🔄 Unit tests

**Upcoming:**
- ⏳ Service layer
- ⏳ UI layer
- ⏳ Integration tests

---

## 🤝 Contributing

This is an educational project. Contributions welcome!

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

---

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file.

---

## 👤 Author

**Arshad Ali**
- GitHub: [@yourusername](https://github.com/ArshadAli01/)
- LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)

---

## 🙏 Acknowledgments

- Inspired by real-world school management systems
- Built as a learning project to demonstrate OOP and SOLID principles
- Documentation follows industry best practices (IEEE standards)

---

**⭐ If you find this project helpful, please give it a star!**
