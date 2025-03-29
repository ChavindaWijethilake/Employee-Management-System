# Employee Management System (Java - Console Application)

This is a simple console-based Employee Management System built using Java. It allows users to create accounts, log in, and perform basic CRUD (Create, Read, Update, Delete) operations on employee records.

## Features

* **User Authentication:**
    * Users can create new accounts with a username and password.
    * A login mechanism allows access to the employee management features.
* **Employee Management (CRUD Operations):**
    * **Insert:** Adds new employee records with name, designation, and salary.
    * **View:** Displays the details of a specific employee by their ID.
    * **Update:** Modifies the name, designation, and salary of an existing employee.
    * **Delete:** Removes an employee record from the system by their ID.
    * **View All:** Lists all employee records currently stored in the system.
* **Simple Console Interface:** Provides a text-based menu for easy interaction.
* **In-Memory Data Storage:** Employee and user data are stored in memory during the program's execution (data is not persistent across runs).
* **Basic Test Data:** Includes an initial test user ("admin") and employee records for demonstration.

## Getting Started

### Prerequisites

* **Java Development Kit (JDK):** Java must be installed on your system. You can download it from [Oracle's website](https://www.oracle.com/java/technologies/javase-downloads.html) or through your operating system's package manager.

### Installation

1.  **Clone the repository (if applicable):** If this code is in a Git repository, clone it to your local machine:
    ```bash
    git clone [repository_url_here]
    cd employee-management-system
    ```
    (Replace `[repository_url_here]` with the actual URL of your repository.)

2.  **Save the code:** If you have the Java code directly, save it as `EmployeeManagementSystem.java` in a directory of your choice.

### Compilation

1.  Open a terminal or command prompt.
2.  Navigate to the directory where you saved the `EmployeeManagementSystem.java` file.
3.  Compile the Java code using the Java compiler:
    ```bash
    javac EmployeeManagementSystem.java
    ```
    This will generate a `EmployeeManagementSystem.class` file in the same directory.

### Running the Application

1.  In the same terminal or command prompt, run the compiled Java class:
    ```bash
    java EmployeeManagementSystem
    ```
2.  The application will start, and the login menu will be displayed.

## Usage

1.  **Creating an Account:**
    * From the login menu, choose option `2. Create Account`.
    * Enter a new username and password when prompted.
    * After account creation, you can log in.

2.  **Logging In:**
    * From the login menu, choose option `1. Login`.
    * Enter your username and password.
    * Successful login will display the main menu.

3.  **Employee Management (Main Menu):**
    * **`1. Insert New Employee`:** Enter the name, designation, and salary of the new employee.
    * **`2. View Employee Details`:** Enter the ID of the employee to view.
    * **`3. Update Employee Details`:** Enter the ID of the employee to update and then provide the new details (leave blank to keep the existing value).
    * **`4. Delete Employee`:** Enter the ID of the employee to delete.
    * **`5. View All Employees`:** Displays a list of all employees in the system.
    * **`6. Logout`:** Returns to the login menu.

4.  **Exiting:**
    * From the login menu, choose option `3. Exit` to close the application.

## Current Limitations

* **In-Memory Data Storage:** All user and employee data resides in memory and is lost when the application terminates.
* **Basic Authentication:** The current authentication is simple and lacks advanced security features like password hashing.
* **Minimal Input Validation:** The application performs limited checks on user input, which could lead to unexpected behavior with invalid data.
* **Console-Based Interface:** The user interacts with the system through a basic text-based console.

## Areas for Future Development

* Data persistence can be added using file storage (e.g., CSV, JSON) or a database.
* The security of the authentication process can be improved by implementing password hashing.
* More comprehensive input validation and error handling can be incorporated.
* A graphical user interface (GUI) could enhance the user experience.
* Additional features such as searching, sorting, and reporting on employee data could be implemented.
* The system could be extended to include user roles and permissions for different levels of access.



