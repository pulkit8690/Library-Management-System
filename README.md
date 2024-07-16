# Library Management System

This project is a library management system developed using NetBeans IDE.
## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/pulkit8690/library-management-system.git
    ```

2. **Open the project in NetBeans IDE:**
    - Open NetBeans IDE.
    - Navigate to `File` > `Open Project`.
    - Select the cloned project directory.

3. **Configure the MySQL Database:**
    - Ensure you have MySQL installed and running.
    - Create a database named `library_db`.

4. **Modify the database connection settings:**
    - Open the `DatabaseConnection.java` file.
    - Update the database URL, username, and password as per your MySQL setup.

### Functions

1. **Login Page**: Allows authorized access to the system.

   ![Login Page](images/Login%20page.png)


2. **Books Available**: Displays a list of books currently available in the library.

   ![Books Available](images/Books%20Availble.png)


3. **Staff Details**: Shows information about staff members.

   ![Staff Details](images/Staff%20Details.png)


4. **Add Books**: Enables addition of new books to the library collection.

   ![Add Books](images/Add%20Books.png)


5. **Remove Books**: Facilitates removal of books from the library collection.

   ![Remove Books](images/Remove%20Books.png)


6. **Add Staff**: Allows addition of new staff members to the system.

   ![Add Staff](images/Add%20Staff.png)


7. **Remove Staff**: Enables removal of staff members from the system.

   ![Remove Staff](images/Remove%20Staff.png)


## Back End

**Database:** MySQL

### Tables

1. **Admin Table**

   Description: Stores information about administrators for the system.

   | USER_ID    | NAME         | PASSWORD  | CONTACT    |
   |------------|--------------|-----------|------------|
   | pulkit@123 | PULKIT ARORA | pulkit123 | 8488251171|

2. **Books Table**

   Description: Contains details of all books available in the library.

   | BOOK_ID | CATEGORY           | NAME                                  | AUTHOR              | COPIES |
   |---------|--------------------|---------------------------------------|---------------------|--------|
   | 1001      | Computer Science              | Java Fundamentals                                  | John                | 4      |
   | 1002    | Science Fiction    | Dune                                  | Frank Herbert       | 3      |
   | 1003    | Fantasy            | Harry Potter and the Sorcerer's Stone | J.K. Rowling        | 7      |
   | 1004    | Mystery            | The Da Vinci Code                     | Dan Brown           | 6      |
   | 1005    | Biography          | Steve Jobs                            | Walter Isaacson     | 4      |
   | 1007    | Horror             | It                                    | Stephen King        | 8      |
   | 1008    | Historical Fiction | The Book Thief                        | Markus Zusak        | 9      |
   | 1009    | Romance            | Pride and Prejudice                   | Jane Austen         | 5      |
   | 1010    | Thriller           | Gone Girl                             | Gillian Flynn       | 7      |
   | 1011    | Self-Help          | The Power of Habit                    | Charles Duhigg      | 12     |
   | 1012    | Science            | A Brief History of Time               | Stephen Hawking     | 6      |
   | 1013    | Poetry             | The Sun and Her Flowers               | Rupi Kaur           | 4      |
   | 1014    | Graphic Novel      | Maus                                  | Art Spiegelman      | 3      |
   | 1015    | Adventure          | The Hobbit                            | J.R.R. Tolkien      | 5      |
   | 1016    | Classic            | To Kill a Mockingbird                 | Harper Lee          | 8      |
   | 1017    | Young Adult        | The Fault in Our Stars                | John Green          | 7      |
   | 1018    | Philosophy         | The Republic                          | Plato               | 2      |
   | 1019    | Drama              | Hamlet                                | William Shakespeare | 6      |
   | 1020    | Travel             | Into the Wild                         | Jon Krakauer        | 4      |
   | 1030    | cs                 | java                                  | unknown             | 2      |


3. **Staff Table**
Description: Holds information about staff members working in the library.

| staffid | name          | contact    | mailid                    |
|---------|---------------|------------|---------------------------|
|8005    | Travis Head         | 88866568129   | travishead138@gmail.com                       |
| 8000    | John Doe      | 1234567890 | john.doe@example.com      |
| 8001    | Jane Smith    | 0987654321 | jane.smith@example.com    |
| 8002    | Alice Johnson | 1122334455 | alice.johnson@example.com |
| 8003    | Bob Brown     | 2233445566 | bob.brown@example.com     |
| 8004    | Charlie Davis | 3344556677 | charlie.davis@example.com |
| 8006    | Eve Adams     | 5566778899 | eve.adams@example.com     |
| 8008    | Grace Lee     | 7788990011 | grace.lee@example.com     |
| 8009    | Hank King     | 8899001122 | hank.king@example.com     |
| 8010    | Ivy Hill      | 9900112233 | ivy.hill@example.com      |
| 8011    | Jess Head      | 9900112233 | Jess.headl@example.com      |
