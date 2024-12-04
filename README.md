# WebUniversity

This project is an **ASP.NET Core MVC application** for managing courses, groups, and students. It provides a user-friendly interface for navigating through courses and their related data, along with separate forms for managing groups and students.

## Features

- **Default Page**:
  - Displays a list of **courses**.
  - Selecting a course shows the associated **groups**.
  - Selecting a group displays the list of **students** in that group.

- **Group Management**:
  - A dedicated form for editing group details, such as the **group name**.
  - Groups cannot be deleted if they contain at least one student.

- **Student Management**:
  - A separate form for editing student details, including **first name** and **last name**.

- **Data Integrity**:
  - Prevents actions (like group deletion) that could compromise data consistency.