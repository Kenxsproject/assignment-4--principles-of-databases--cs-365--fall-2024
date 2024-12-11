# Fall 2024 Principles of Databases — Assignment 4

* **Do not start this project until you’ve read and understood these instructions. If something is not clear, ask.**

---

## ❖ Introduction ❖

For this assignment, you will write responses to nine questions based on different topics from our textbook, *Database Systems — The Complete Book* and to one question based on your notes. Reply to each question in the provided region using Markdown syntax.

---

## ❖ Questions ❖

### 1. [2.4] What is the difference between a Cartesian Product, a Natural Join, and Theta-Joins?

The difference between these three is that cartestian combines every row of one relation with every row of another relation which results in all combinations of a tuple. While a natural join combines common attributes of two relations deleting duplicates in the result. Theta-Joins combine rows based on a specified condition regardless of attribute names.

### 2. [2.5] What is a Referential Integrity Constraint?

A referential integrity contraint ensures that a foreign key in one relation is refering to a valid primary key in another relation which keeps the consistency between tables.

###  3. [2.5] What is a Key Constraint?

A key constraint specifies that a set of attributes which is a key uniquely identifies each tuple in a relation.

### 4. [4.1] What is an Entity/Relationship Model? What purpose does it serve in the process of creating/designing databases?

An E/R model is a modeling framework that visualizes the structure of a database. It defines the entities,attributes and relationships. The purpose it serves is to provide a representation of the data and its relationships to ensure the accuracy and consistency before implementation.

### 5. [4.4] What is a Weak Entity Set?

a set of entities in a relational database that can't be uniquely identified by their own attributes

### 6. [5.2.7; 6.3.8] Explain the concepts of Outerjoin, Natural Right Outer Joins, Natural Left Outer Joins, and Full Outer Joins.

Replace this content with your answer

### 7. [6.6.3] What is the difference between the SQL command `TRANSACTION` and the execution of any statement in SQL?

a transaction involves managing multiple statements as a unit, while individual statements execute independently unless explicitly wrapped in a transaction.

### 8. [8] What is a Virtual View and what are its advantages?

A virtual view is a sql query that acts like a virtual table in that it doesn't store data itself but provides a dynamic way to access it from  one or more tables. The advantages is that it simplifies complex queries by using a consistent interface. 

### 9. [8.3] What is an *index* and what are its advantages?

An index is a data structure that improves the speed of which data is retrieved from the database by using a sorted order of the indexed columns.The advantages of this is faster query search, much more efficient searching since it uses indexed columns.

### 10. Explain the concept of an MVC, or model, view, controller, framework for designing full stack applications

MVC is a framework for designing full stack apps the model represents the application's data and business logic, managing data storage, retrieval, and processing, often interacting with a database.it is responsible for notifying the view when data changes occur.The view handles the user interface and presentation layer. It displays data to the user as provided by the model and forwards user actions to the controller. The controller serves as an intermediary between the model and the view. It processes user input, invokes the necessary methods in the model, and updates the view accordingly, ensuring the flow of the application is maintained.
---

## ❖ Due ❖

Sunday, 15 December 2024, at 10:00 AM.

---

## ❖ Grading ❖

| Item        | Points |
|-------------|:------:|
| Question 1  | `10`   |
| Question 2  | `10`   |
| Question 3  | `10`   |
| Question 4  | `10`   |
| Question 5  | `10`   |
| Question 6  | `10`   |
| Question 7  | `10`   |
| Question 8  | `10`   |
| Question 9  | `10`   |
| Question 10 | `10`   |

---

## ❖ Submission ❖

**NO late submissions will be accepted.**

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the **Issuing Pull Requests** section of [this site](http://code-warrior.github.io/tutorials/git/github/index.html) for help on how to submit your assignment.

**Note**: This assignment may **only** be submitted via GitHub. **No other form of submission will be accepted**.
