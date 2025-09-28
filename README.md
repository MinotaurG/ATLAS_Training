# ATLAS_Training

_Work done while training for the SDE Track._

This repository contains day-wise training notes and artifacts. Topics span Object-Oriented Analysis & Design (OOAD), SOLID principles, design patterns, Java/JUnit testing, UML/PlantUML, and AWS (with a focus on DynamoDB, CLI/SDK usage, and DAX).

---

## ✨ What’s inside

- **OOAD & SOLID**: Principles, refactoring, code smells, three-tier architecture, UML.
- **Design Patterns**: Creational (Factory, Abstract Factory, Builder, Prototype, Singleton), Structural (Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Proxy), Behavioral (Command, Observer/Pub-Sub, Strategy, MVC context).
- **Java & Testing**: JUnit 4/5 basics, assertions, fixtures, test suites, TDD/BDD notes, Generics & wildcards.
- **AWS & DynamoDB**: Console/CLI/SDK CRUD, capacity/on-demand, partitions & hot keys, LSIs/GSIs, queries/scans, DAX clusters, DynamoDBMapper basics, NoSQL Workbench.
- **Architecture**: CAP theorem, ACID vs BASE, 3-tier patterns, persistence concepts.

> **Note:** Files are organized **day-by-day** (e.g., `Day 31 -Aditya - 113312696 DynamoDB.docx`) to reflect the training cadence.

---

## 🗂️ Repository structure

ATLAS_Training/
├─ Day 1- ... .docx
├─ Day 2- ... .docx
├─ ...
└─ Day NN ... .docx

markdown
Copy code

- Each `Day *.docx` captures notes, tasks, example code snippets, and links used that day.
- Some days emphasize **DynamoDB & AWS workflows** (console, CLI, SDK).
- Later days include **DAX** setup and client usage notes.

---

## 🔧 Getting started

### Prerequisites

 If you want to try code mentioned in notes:
  - Java 11+ (or the version referenced in your environment)
  - Maven/Gradle (as applicable)
  - AWS CLI (for DynamoDB CLI exercises)
  - Local **DynamoDB Local** / **NoSQL Workbench** (for local testing)

### Clone
```bash
git clone https://github.com/MinotaurG/ATLAS_Training.git
cd ATLAS_Training