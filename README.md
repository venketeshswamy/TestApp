# Friendly CSV Quiz
An interactive web-based quiz application that dynamically loads, parses, and renders quizzes from structured CSV files. Designed for exam preparation, supporting multiple-choice questions, mappings, and supplementary PDF references.
## 🔗 Live Demo
Access the live application here: **[https://venketeshswamy.github.io/TestApp/](https://venketeshswamy.github.io/TestApp/)**
---
## 📁 Repository Structure
*   **`index.html`** & **`assets/`**: The compiled frontend application (built using Vite, React, TypeScript, and Tailwind CSS).
*   **`QUIZZES/`**: Contains the quiz datasets grouped by subject folders:
    *   `ADVITT` (Advanced Information Technology Test)
    *   `AFM` (Advanced Financial Management)
    *   `AUDIT` / `AUDITM26EXTRAS` (Auditing)
    *   `FR` (Financial Reporting)
    *   `IDT` (Indirect Tax Laws)
    *   `SPOMSETA` / `SPOMSETB` (Self-Paced Online Modules Set A & B)
### Quiz Subject Folder Contents:
Each subject folder inside `QUIZZES/` contains:
*   `Questions.csv`: The primary database of questions, multiple-choice options, and correct answers.
*   `Mapping.csv`: Mappings relating questions to specific chapters, modules, or reference materials.
*   `Questions_Only.pdf`: PDF versions of the questions for offline viewing.
---
## 🛠️ Built With
*   **Vite** - Build Tool & Development Server
*   **React** - UI Component Library
*   **TypeScript** - Type Safety
*   **Tailwind CSS** - Modern Utility-First Styling
