# Master's Degree Computer Science Codebase

Welcome to the **Master's Degree Computer Science Codebase** repository! This repository consolidates materials from multiple graduate-level Computer Science (CS) courses, including projects, homework assignments, lecture notes, and supporting data files. Each course within the codebase focuses on distinct areas of computer science, providing a comprehensive resource for master's students and educators alike.

## Table of Contents

- [Courses Overview](#courses-overview)
  - [CS510: Course Management System](#cs510-course-management-system)
    - [Projects](#projects)
    - [Data Files](#data-files)
  - [CS515: Symbolic Logic and Proof Techniques](#cs515-symbolic-logic-and-proof-techniques)
    - [Homework](#homework)
  - [CS512: Postfix Translator and Evaluator](#cs512-postfix-translator-and-evaluator)
    - [Homework](#homework-1)
  - [CS559: System Security and Access Control](#cs559-system-security-and-access-control)
    - [Projects](#projects-1)
    - [Lecture Notes](#lecture-notes)
    - [Additional Components](#additional-components)
- [Conclusion](#conclusion)
- [License](#license)
- [Contact](#contact)

---

## Courses Overview

### CS510: Course Management System

**CS510** focuses on developing systems for managing course-related data, including student enrollments and grade statistics. This course provides a robust system for handling course and student information through Python scripts and a command-line interface (CLI).

#### Projects

##### Project10-sol

**Description:**  
This project is designed to manage course-related data, encompassing student enrollments and grade statistics. It includes Python scripts that define essential classes and offer a CLI for interacting with course and student information.

**Files Included:**
- `course.py`: Defines the `Course` class, managing course attributes such as title and enrolled students. It includes methods for adding students, calculating course size, printing the roster, and determining statistical information like top grade, average grade, and bottom grade.
- `main.py`: Implements the CLI for interacting with courses and students. It provides functionalities such as displaying class rosters, course statistics, student grades with GPA calculations, identifying students on probation, and listing valedictorians.

#### Data Files

**Neuroscience**

- **Location:** `CS510/Projects/Project10-sol/data/Neuroscience`
- **Content:**  
  Contains a list of students enrolled in the Neuroscience course along with their respective grades.

**Summary:**  
The CS510 project offers a comprehensive system for managing courses and student data. The `Course` class encapsulates all course-related information and operations, while `main.py` provides an interactive CLI for data access and manipulation. The accompanying data files facilitate easy import and management of student information within the application.

---

### CS515: Symbolic Logic and Proof Techniques

**CS515** delves into symbolic logic and proof strategies, equipping students with the skills to analyze and validate logical statements and arguments through detailed symbolization and truth table construction.

#### Homework

##### Homework3/Part2.tex

**Description:**  
A LaTeX document for Homework 3 Part 2, focusing on logical analysis and proof techniques. The document includes sections on proof through contraposition, symbolization of statements, truth tables, and the application of rules of inference to determine the validity of arguments.

**Content Highlights:**
- **Proof through Contraposition:** Demonstrates the method of proving statements by showing the contrapositive.
- **Symbolization:** Assigns propositional variables to components of statements and represents them symbolically.
- **Truth Tables:** Constructs truth tables to analyze the validity of logical arguments.
- **Rule of Inference:** Identifies and applies rules of inference such as proof by cases to validate arguments.
- **Analytical Commentary:** Provides critical analysis of logical arguments and identifies errors such as inverse mistakes.

**Summary:**  
The CS515 homework assignment explores symbolic logic and proof strategies, reinforcing principles of logical reasoning and inference through comprehensive symbolization and truth table exercises.

---

### CS512: Postfix Translator and Evaluator

**CS512** focuses on the development and analysis of algorithms for translating and evaluating mathematical expressions in postfix notation. The coursework emphasizes data structures, algorithmic efficiency, and error handling.

#### Homework

##### PA4.4.7/Technical_Analysis_Postfix_Translator_Evaluator.tex

**Description:**  
A technical analysis report of a Postfix Translator and Evaluator script. The document outlines the script's functionality, design considerations, and implementation details.

**Content Highlights:**
- **Overview:** Introduces the purpose of the script, which translates and evaluates mathematical expressions in postfix notation.
- **Program Utility and Academic Relevance:** Discusses the script’s applications in compiler design, data structures, and algorithms.
- **Header and Meta Information:** Details about the script's metadata, such as encoding and creation date.
- **Import Statements:** Lists the Python modules imported, including `re` for regular expressions.
- **Classes:**
  - `OrderedRecordArray` Class: Manages ordered record storage with methods to add, remove, retrieve, and list records.
  - `Token` Class: Handles token management within mathematical expressions.
  - `Expression` Class: Represents and evaluates mathematical expressions, including methods to add tokens, translate to postfix, and evaluate the expression.
- **Error Handling:** Describes mechanisms for managing invalid expressions and undefined variables.
- **Time Complexity:** Analyzes the algorithmic efficiency of the script’s operations.
- **Test Function:** Explains the testing procedures implemented to ensure the script functions correctly under various scenarios.
- **Main Program Logic:** Details the script’s logic for parsing user input and managing variable assignments.
- **Authorship and Documentation:** Highlights the importance of documentation and adherence to programming best practices.

**Summary:**  
The technical analysis for CS512 provides a comprehensive examination of a Postfix Translator and Evaluator script, demonstrating the integration of data structures, algorithmic efficiency, and error handling. The report underscores the academic relevance of such scripts in understanding compiler design and expression evaluation.

---

### CS559: System Security and Access Control

**CS559** covers system security principles, focusing on access control mechanisms, security models, and practical implementations in UNIX environments. The coursework includes projects, lecture notes, and additional materials to provide a thorough understanding of system security.

#### Projects

##### Project1/Project1.tex

**Description:**  
A LaTeX document titled "CS559 Lab Setup Project Report," documenting the setup process for virtualization environments necessary for the CS559 course. This includes the installation and configuration of virtualization software and the Kali and Ubuntu virtual machines (VMs).

**Content Highlights:**
- **Introduction:** Overview of the project's objectives, focusing on setting up required virtual environments.
- **Virtualization Software Setup:** Details the installation and configuration steps for the virtualization software, accompanied by screenshots demonstrating successful setup.
- **Kali VM Setup:**
  - Installation and configuration of the Kali VM.
  - Processor and memory allocation details.
  - Network adapter configuration for NAT (Network Address Translation).
  - **Screenshots:** Visual documentation of each setup stage, highlighting key configurations and successful installations.

**Summary:**  
The CS559 project report provides a meticulous guide on setting up virtual environments essential for cybersecurity practices. Through step-by-step instructions and visual aids, the report ensures reproducibility and adherence to project requirements.

#### Lecture Notes

##### Lec_week4 and Lec_week6

**Description:**  
Text files containing lecture notes for weeks 4 and 6, transcribed using Otter.ai. The notes cover topics related to access control, security models, UNIX file permissions, access control matrices, and the Bell-LaPadula (BLP) security model.

**Content Highlights:**
- **Access Control Fundamentals:**
  - Definitions and importance in system security.
  - Distinctions between authentication and authorization.
  - Access control in various systems like operating systems, databases, and web applications.
- **Access Control Models:**
  - **Discretionary Access Control (DAC):** Resource owners set access permissions.
  - **Mandatory Access Control (MAC):** System-enforced access rules based on security labels.
  - **Bell-LaPadula (BLP) Model:** Focuses on data confidentiality with properties like no read up and no write down.
- **Access Control Matrix:**
  - Structure and implementation.
  - Challenges with scalability and sparsity.
  - Optimizations using Access Control Lists (ACLs).
- **UNIX File Permissions:**
  - Explanation of file permission schemes.
  - Managing and configuring file permissions for security.
- **Security Properties and Proofs:**
  - Simple Security Property: No read up.
  - Star Property: No write down.
  - Security Theorems: Ensuring system states remain secure through controlled state transitions.
- **Practical Implications:**
  - Real-world applications in military and government systems.
  - Common pitfalls and error-prone practices in access control management.

**Summary:**  
The CS559 lecture notes offer an in-depth exploration of access control mechanisms and security models, emphasizing their theoretical foundations and practical applications. Topics such as the Bell-LaPadula model, access control matrices, and UNIX file permissions are thoroughly examined, providing a solid understanding of system security principles.

#### Additional Components

##### CS559/Lec_week4/Note_20240212_1254_otter_ai.txt

**Description:**  
Transcript from a lecture on UNIX file permissions, detailing how files and permissions are managed within UNIX-based systems.

**Content Highlights:**
- **UNIX File Structure:**
  - Everything is treated as a file, including directories and devices.
  - File naming conventions and storage mechanisms.
- **File Permissions:**
  - Read, write, and execute permissions for different user categories.
  - Managing permissions using command-line tools.
- **Hard and Soft Links:**
  - Differences between hard links and symbolic (soft) links.
  - Use cases for each type of link.
- **Directories:**
  - Handling directories as special files.
  - Permissions management for directories.

**Summary:**  
This lecture transcript provides a comprehensive overview of UNIX file permissions, elucidating the intricacies of file management, permission settings, and the role of links and directories within the UNIX file system. It serves as a practical guide for understanding and implementing file security in UNIX environments.

---

## Conclusion

This codebase integrates a diverse range of components across different Computer Science courses within a master's degree program, encompassing project scripts, technical reports, homework assignments, and extensive lecture notes. Each course targets specific areas, such as:

- **CS510:** Course management systems and student data handling.
- **CS515:** Logical proof techniques and symbolic logic.
- **CS512:** Expression evaluation and algorithmic efficiency.
- **CS559:** System security, access control mechanisms, and UNIX file permissions.

This multifaceted approach fosters a well-rounded understanding of computer science principles, from software development and logical reasoning to cybersecurity and system administration. Whether you're a master's student seeking comprehensive resources or an educator looking for structured materials, this repository serves as a valuable asset in the academic journey of computer science.

---

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or contributions, please contact [Your Name](mailto:your.email@example.com).

---

*Happy Coding!*
