# MongoDB Bookstore a.k.a. CRUD with Books!

## Install MongoDB
- brew update
- brew install mongodb
- type 'mongod' to enter the MongoDB console. You will need to be in the mongoDB console to complete this exercise.

## Create Database
Useful commands: 
- use DATABASE_NAME (creates database, or switches to it if it exists)
- db (check current database)
- show dbs (shows databases, only shows databases that are not empty)

## Create A Collection of Books with some new books in the collection

- Each document in books should have the fields title, rating, and author.
- Make one book that has the {title: "Moby Dick", rating: 4, author: "Capybara"}
- Make one book that has the {title: "Love That Dog", rating: 5, author: "Momo"}

## Read some books in the collection

- Find the book that has the title "Love That Dog"

## Update some book details

- Update the author for the book with title "Moby Dick" to "Herman Melville"
- Update the author for the last book again, but this time re-name it from "Herman Melville" to {evenObjectsCanBeStored: True}

## Destroy some books

- Delete the book with the title "Love That Dog"

## Writing Questions

### Refer to docs.mongodb.org

- What is a document?

- What is a field

- What is BSON?

- What is a collection?

- What is a resource?

### BONUS Questions(may not find in docs.mongodb.org)

- What is ACID in database terms? 

- What is a non-relational database? What is a relational database?

- What is a document-oriented database?

- How are relations between collections created in MongoDB?

- How does embedded documents work?

- How does document references work?







 







