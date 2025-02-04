# **EXAM PRINTING SYSTEM**

## **Description**

The Exam Printing System is a PHP and SQL-based application designed to preparation and management of exam materials. It supports multiple user roles, from uploading exam files to printing and distribution.

## **Overview**

The **Exam Printing System** is a PHP and SQL-based application designed to streamline the process of managing and printing exam materials. It supports multiple user roles, each with specific responsibilities to ensure efficient exam preparation and printing.

## **User Roles**

1. **Admin**

   - Manages user accounts and permissions.
   - Oversees the overall system settings.

2. **Instructor**

   - Uploads exam files in PDF format for their respective courses.
   - Ensures exam files are uploaded correctly for scheduled exams.

3. **Media Department**

   - Reviews and manages all exam schedules and associated course details.
   - Coordinates with other departments to ensure everything is in place.

4. **Exam Printing Department**

   - Accesses and downloads the exam files uploaded by instructors.
   - Prepares and prints exam materials for distribution.

## **Key Features**

- **User Management**: Admins can add, edit, or remove users and assign appropriate roles.
- **File Upload and Management**: Instructors can upload PDFs for specific courses, ensuring secure and organized file handling.
- **Schedule Management**: The Media Department can review and organize courses with upcoming exams.
- **File Access and Printing**: The Exam Printing Department can download uploaded files to facilitate efficient printing.

## **Technology Stack**

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## **How to Run the Project**

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/username/EXAM_PRINTING_SYSTEM.git
   cd EXAM_PRINTING_SYSTEM
   ```

2. **Set Up the Database**:

   - Create a new MySQL database.
   - Import the provided SQL file into the database:
     ```bash
     mysql -u username -p database_name < database_file.sql
     ```
   - Update the database connection details in the PHP configuration file (e.g., `config.php`).

3. **Set Up the Server**:

   - Place the project files in your web server's root directory (e.g., `htdocs` for XAMPP or `www` for WAMP).
   - Start the server using your preferred tool (e.g., XAMPP, WAMP, or MAMP).

4. **Access the System**:

   - Open a web browser and navigate to `http://localhost/EXAM_PRINTING_SYSTEM` (or the folder name where the project is located).

