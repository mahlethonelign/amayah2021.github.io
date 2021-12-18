
#### Mahlet Honelign
#### 2021-12-18
## Relational and Document-Based Databases Final Project
### This project contains a conceptual and logical model for the City of Fairfield Public Libraries system, and its implementation of the database using MongoDB.
### The Fairfield-Public-Libraries-DB database has six collections: books, members, bookLoanRecords, Libraries, publishers, and authors.
### Publishers and authors are embedded in books even though they exist as independent collections, inorder to have the flexibility of accessing their records both independently and within the documents of books.
### The design implementation of the database would fullfil the following quries.
### 1. search for books based on their subject, 
### 2. find location of a certain book,
### 3. sort books by bookid,
### 4. display publisher details of a book,
### 5. update the address and phonenumber of a publisher,
### 6. find book Loan record of a member including how much they owe to the library,
### 7. add a new bookloan record,
### 8. display address and phonenumber of a member,
### 9. remove a record of a member to cancel the membership, 
### 10. add a new member to the system.
