
# Homework 8



## Purpose

The goal of this module is to familiarize yourself with the basic syntax for a MongoDB query.
## Tasks

### In this homework, you will need to install MongoDB before you start any coding. Please follow notes from MongoDB Setup to install MongoDB.

#### In this section, you are going to use the restaurants collection to get information from the database. Please supply the find query along with any other information that the question asks for (Ex. give the name of the restaurant if the question asks for the name).

##### Read Section

- Find all restaurants from the borough of "Queens"

- Give me the name of the restaurant that has a restaurant_id of "40377124"

- Give me the names of the restaurants that are in building 703. (Hint, there are 6 of them). Use a projection to give the name and address fields of the restaurants

- Give me the name of the restaurant that is located on "Spring Street" in building "300". Use a projection to only show the name and address fields of the restaurant

- Find all restaurants that have either a cuisine of "American" or a cuisine of "French". Use a projection to only show the name and cuisine of the restaurants

- Find all restaurants that received a score greater than 100. Use a projection to only show the name and the grades score of the restaurants

##### Write Section

- Insert an object containing name of 'Charlie', age of 25 and position of 'lecturer' to the users collection

- Insert another user object containing name of 'Alice', age of 20, position of 'student' and grade of 84 to the users collection

- Insert another user object containing name of 'Bob', age of 21, position of 'student' and grade of 89 to the users collection

- Update user object of 'Alice' to grade 95

- Delete user 'Bob'

- Update user of position 'student' to have a new field called homeAddress containing of follwing json:

 {
     street: '1234 Random st.',
     city: 'Los Angeles',
     state: 'CA'
 }
