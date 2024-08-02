# MySQL Student Management System using PyQt

## Description

This project is a Student Management System built using PyQt and MySQL. It provides a graphical interface for managing student records, including adding, editing, deleting, and searching for student information. The application uses MySQL as the database backend to store and retrieve student data.

## Process

1. **Setup Database**: Created a MySQL database named `school` and a table named `students` with fields `id`, `name`, `course`, and `mobile`.
2. **Develop PyQt Interface**: Designed a graphical user interface using PyQt6 that allows users to interact with the student data.
3. **Implement CRUD Operations**: Enabled the functionality to create, read, update, and delete student records.
4. **Integrate MySQL**: Connected the PyQt application to the MySQL database to perform operations on the student records.

## Technology Used

- **Programming Language**: Python
- **GUI Framework**: PyQt6
- **Database**: MySQL
- **Database Connector**: `mysql-connector-python`
- **IDE**: PyCharm

## What I Learned from This Project

- **PyQt6**: Gained experience in building graphical user interfaces with PyQt6, including creating dialogs, tables, and menus.
- **MySQL**: Learned how to set up and interact with a MySQL database, including executing SQL commands and handling database connections in Python.
- **CRUD Operations**: Implemented create, read, update, and delete operations using PyQt and MySQL, which are essential for any database-driven application.
- **Database Integration**: Understood how to integrate a Python application with a MySQL database using a connector library.

## Future Insights

- **User Authentication**: Implement user authentication and authorization to manage access to the application.
- **Data Validation**: Add data validation checks to ensure that the entered data meets specific criteria before saving it to the database.
- **Enhanced Search Functionality**: Improve search functionality to support more complex queries and filters.
- **UI Enhancements**: Enhance the user interface with additional features such as sorting and pagination for better user experience.
- **Error Handling**: Implement robust error handling and logging to manage database connection issues and other potential errors gracefully.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    ```

2. **Install Dependencies**:
    ```bash
    pip install PyQt6 mysql-connector-python
    ```

3. **Setup MySQL Database**:
    - Create a MySQL database named `school`.
    - Create a table named `students` with the following schema:
        ```sql
        CREATE TABLE students (
            id INT AUTO_INCREMENT PRIMARY KEY,
            name VARCHAR(255),
            course VARCHAR(255),
            mobile VARCHAR(255)
        );
        ```

4. **Run the Application**:
    ```bash
    python main.py
    ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

