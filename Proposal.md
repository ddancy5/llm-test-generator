Project Name: AutoTest LLM
Objective: The goal of this project is to develop a software tool that leverages Large Language Models (LLMs) to automatically generate a comprehensive set of software test cases from a provided codebase and a plain text specification file. This tool will simplify and accelerate the software testing process while maintaining high-quality coverage.
Scope:
Input: 
    Source Code Folder**: A complete project written in a single programming language (Python)
    Specification File**: A 'txt' file containing detailed descriptions of each function’s expected behavior
Output:
    A 'Test Folder' containing the following:
    **White-box Test Cases**:
        Statement Coverage
        Block Coverage
        Condition Coverage
        Path Coverage
    **Black-box Test Cases**:
        Derived from the textual specification
    **Boundary Value Analysis (BVA)** Test Cases
    **Equivalence Class Partitioning (ECP)** Test Cases
    **Automation Script**:
        A GitHub Actions YAML workflow to automatically run the generated test suite
Language Supported: Python
Assumptions:
    The input codebase is syntactically correct and functional
    The `.txt` specification file is complete, unambiguous, and maps to the functions in the codebase
    No dynamic code generation or obscure metaprogramming used in the source code
Technologies: 
    **Python**: Core logic, parsing, and test generation
    **LLM API (OpenAI)**: To generate test cases using structured prompts
    **AST module (Python)**: For static code analysis and function extraction
    **GitHub Actions**: To automate the execution of generated test suites
    **Markdown & YAML**: For documentation and workflow configuration
Deliverables:
    'Specifications.md': Detailed explanation of tool functionality
    `Proposal.md': This file
GitHub repository with:
    Initial file structure
    Example inputs/outputs
    Generated test cases
    CI/CD automation script
    README file with usage instructions
