```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the consistent, high-quality, and maintainable development of the AGENTS repository. Adherence to these principles is crucial for building a robust and scalable AI agent system.

**1. DRY (Don't Repeat Yourself)**

*   **Modular Design:**  Each agent module should have a single, well-defined responsibility. Avoid creating overly complex modules that could be duplicated.
*   **Reusable Components:**  Identify and reuse components across multiple agents where appropriate.
*   **Abstraction:**  Use abstraction to hide implementation details and provide a consistent interface.

**2. KISS (Keep It Simple, Stupid)**

*   **Minimal Code:** Strive for the shortest possible code that achieves the required functionality.
*   **Readability:**  Write code that is easy to understand and maintain.
*   **Simplicity:**  Favor simple solutions over overly complex ones.  Complexity should be justified.

**3. SOLID Principles**

*   **Single Responsibility Principle:** Each class/module should have one and only one reason to change.
*   **Open/Closed Principle:**  The system should be open for extension but closed for modification. (Extend with new features, don't rewrite existing code.)
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without affecting the correctness of the program.
*   **Interface Segregation Principle:**  Clients shouldn't be forced to implement interfaces they don't use.

**4. YAGNI (You Aren't Gonna Need It)**

*   **Avoid Over-Implementation:** Don’t add features or functionalities that are not currently required.
*   **Focus on Requirements:**  Prioritize development based on the defined requirements.
*   **Refactor When Necessary:**  Refactor only when functional changes are required and a redesign is warranted.

**5. Code Style & Formatting**

*   **Consistent Indentation:** Use 2 spaces for indentation.
*   **Line Length:** Max 80 characters per line.
*   **Naming Conventions:** Follow established naming conventions (e.g., camelCase for variables and functions).
*   **Comments:** Concise and helpful comments should explain the *why*, not just the *what*.
*   **Code Formatting:** Use a code formatter (e.g., Prettier, Black) to ensure consistent code style.

**6. Testing & Coverage**

*   **Unit Tests:** All code must be covered by at least 80% unit tests.
*   **Test-Driven Development:** Write tests *before* implementing the code.
*   **Test-Driven Development Practices:** Follow a defined test-driven development methodology.
*   **Test Suite:** Maintain a well-organized and documented test suite.

**7. File Limits**

*   **Maximum Files:** 180 files.
*   **File Structure:**  Organize files into logical directories.

**8.  Documentation (Minimal)**

*   Provide a brief README.md with a description of the project and relevant setup instructions.

**9.  Asset Management**

*   Use a dedicated asset management system (e.g., npm, yarn, pnpm) to manage dependencies and libraries.

**10.  Error Handling & Logging**

*   Implement robust error handling and logging.  Don’t expose sensitive information in logs.

**11.  Code Review**

*   All code changes must be reviewed by at least one other developer before merging into the main branch.

**12.  Version Control**

*   Use Git for version control.
*   Follow a clear branching strategy.

**13.  Dependencies**

*   Clearly document all dependencies used in the project.
*   Keep dependencies as lightweight as possible.

**14.  Security**

*   Adhere to secure coding practices to mitigate vulnerabilities.

**15.  Reproducibility**

*   Ensure the entire development process is reproducible – build, test, and run the same codebase.

**16.  Data Validation**

*   Where appropriate, include validation checks within the agent logic to prevent invalid data from being processed.

**17.  Configuration Management**

*   Consider a configuration management strategy to easily configure agent behavior.

**18.  Documentation of Core Concepts**

*   Provide inline documentation for essential concepts and algorithms used within the agent system.
```