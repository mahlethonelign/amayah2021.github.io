
#### Mahlet Honelign
#### 2021-12-18
## Relational and Document-Based Databases Final Project
### This project contains a conceptual and logical model for the City of Fairfield Public Libraries system, and its implementation of the database using MongoDB.
### The Fairfield-Public-Libraries-DB database has six collections: books, members,bookLoanRecords,Libraries,publishers, and authors.
### Publishers and authors are embedded in books even though they exist as independent collections, inorder to have the flexibility of accessing their records both independently and within the documents of books.
### The design implementation of the database would fullfil the following quries.
#### search for books based on their subject, 
#### find location of a certain book,
#### sort books by bookid,
#### display publisher details of a book,
#### update the address and phonenumber of a publisher,
#### find book Loan record of a member including how much they owe to the library,
#### add a new bookloan record,
#### display address and phonenumber of a member,
#### remove a record of a member to cancel the membership, 
#### add a new member to the system.