# 📄 Project Proposal: AutoTest-LLM

## 🧠 Project Name
**AutoTest-LLM** – Automated Test Case Generation using Large Language Models

---

## 🎯 Objective
The goal of this project is to develop a software tool that leverages Large Language Models (LLMs) to automatically generate a comprehensive set of software test cases from a provided codebase and a plain text specification file. This tool will simplify and accelerate the software testing process while maintaining high-quality coverage.

---

## 📦 Scope

### 📥 Input
- **1. Source Code Folder**: A complete project written in a single programming language (Python)
- **2. Specification File**: A `.txt` file containing detailed descriptions of each function’s expected behavior

### 📤 Output
- A `Test Folder` containing the following:
  - **White-box Test Cases**:
    - Statement Coverage
    - Block Coverage
    - Condition Coverage
    - Path Coverage
  - **Black-box Test Cases**:
    - Derived from the textual specification
  - **Boundary Value Analysis (BVA)** Test Cases
  - **Equivalence Class Partitioning (ECP)** Test Cases
  - **Automation Script**:
    - A GitHub Actions YAML workflow to automatically run the generated test suite

---

## 🧪 Language Supported
- **Python**

---

## 📌 Assumptions
- The input codebase is syntactically correct and functional
- The `.txt` specification file is complete, unambiguous, and maps to the functions in the codebase
- No dynamic code generation or obscure metaprogramming used in the source code

---

## 🧰 Technologies Used
- **Python**: Core logic, parsing, and test generation
- **LLM API (OpenAI)**: To generate test cases using structured prompts
- **AST module (Python)**: For static code analysis and function extraction
- **GitHub Actions**: To automate the execution of generated test suites
- **Markdown & YAML**: For documentation and workflow configuration

---

## 👥 Team Roles & Responsibilities
| Name              | Role                     | Responsibility                                     |
|-------------------|--------------------------|----------------------------------------------------|
| [Member 1]        | Project Manager           | Organize tasks, track deadlines, and communication |
| [Member 2]        | LLM Integration Engineer  | LLM prompt engineering and response handling       |
| [Member 3]        | Test Suite Developer      | Organize and format test cases                     |
| [Member 4]        | Automation & Deployment   | Setup GitHub Actions and automation workflows      |

---

## 📌 Deliverables
- `Specifications.md`: Detailed explanation of tool functionality
- `Proposal.md`: This file
- GitHub repository with:
  - Initial file structure
  - Example inputs/outputs
  - Generated test cases
  - CI/CD automation script
  - README file with usage instructions

---

## ✅ Timeline for Part 1
| Milestone                     | Deadline         |
|------------------------------|------------------|
| Group Formation               | [Insert Date]    |
| Project Proposal Finalized    | [Insert Date]    |
| GitHub Repository Created     | [Insert Date]    |
| Specifications & README Ready | [Insert Date]    |

---

## 🔮 Future Extensions (Optional)
- Support for additional languages (e.g., JavaScript, Java)
- Interactive Web Interface for uploading projects and viewing test reports
- Integration with Docker for isolated test environments


