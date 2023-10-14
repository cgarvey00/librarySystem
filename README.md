Note: This is part ONE of this CA. A second part will be released with an extra aspect that slots into this same
system structure. Therefore, it is vital that you do not wait until the last minute to start building this project.
You have been tasked with writing a basic library system. Your system should provide the following functionality:
1) Registering with the library (a member must provide more than just a username and password to register).
2) Logging in to your library account (by providing your username and password).
3) Viewing the details of all books in the library.
4) Viewing the details of all loans currently active for you.
5) Viewing the details of all loans you have made since joining the library.
6) Borrowing a copy of a book in the library (if there are no copies available in the library, this will not succeed). A
member can only borrow a single copy of any title in a single transaction (they can borrow multiple books at a
time, just no more than one copy of a specific title). However, once they return their copy of a book, they can
borrow it again in the future.
7) Returning a book you currently have on loan (late fees should be considered)
8) Logging out.
You are required to:
1. Create a MySQL database to hold all of the required information for the library system to function in a welldesigned fashion. Primary and foreign keys should be included, and the database should include reasonable levels
of information, not merely the minimum required to allow the system to function.
2. Write the front-end interface for the system – this MUST be based on the command-line.
3. Write the set of Java classes that control access to the database & provide the program’s functionality. These
classes MUST implement the DAO pattern for all database access & you MUST create and use Data Transfer
Objects (DTOs).
4. Write a set of Junit tests for all table-specific DAO classes (no need for DTOs to be tested)
5. Write Javadoc comments for all DAO methods as well as any other non-DTO code. These should include
information on return types, parameters, method functionality and the meaning of any potential exceptions that
can be thrown.
Marks will be awarded as follows:
• Implementation of the DAO pattern, construction of DAO classes & provision of database functionality - 40%
• Database design and population of tables with dummy information – 10%
• Program interface – 15%
• Junit tests – 25%
• Javadocs – 10%
Project management:
You are required to create and maintain source control via git and github. Code should be regularly committed (with
appropriate commit messages indicating what is being added/changed/removed/fixed etc) and pushed to the shared
repository by all team members
.
Submission instructions:
Upload a zipped copy of your Intellij project to Moodle, as well as a link to your project on GitHub. This zipped file MUST
also include files containing the SQL statements used to create and populate your MySQL “live” and test databases. If
these files are not included, your project will not be marked.
Deadline: 23:59 on 5
th November 2023
