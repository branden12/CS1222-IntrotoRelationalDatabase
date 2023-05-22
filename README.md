# Homework 1

## Purpose

Purpose 

The purpose of this assignment is to demonstrate knowledge of the basic syntax of a SQL query. Specifically, you will be asked to demonstrate:

- use of the SELECT clause to specify which fields you want to query

- use of the FROM clause to specify which tables you want to query, and 

- use of the WHERE clause to specify which conditions the query will use to query rows in a table.

These are the basic commands that will make up your foundational knowledge of SQL. There are other clauses besides SELECT, FROM, and WHERE, but by building up your knowledge of these basic clauses, you will have constructed a foundation upon which to base your knowledge of SQL.


## Tasks

#### Question: Design the following queries, using the lyrics.sql schema:

- List the Title, UPC and Genre of all CD titles. (Titles table)

- List all of the information of CD(s) produced by the artist whose ArtistID is 2. (Titles table)

- List the First Name, Last Name, HomePhone and Email address of all members. (Members table)

- List the Member ID of all male members. (Members table)

- List the Member ID and Country of all members in Canada. (Members table)

- List the first name, last name, and region of all members from Virginia who either have a work phone or an email address. (Members Table)


# Homework 2

## Purpose

Purpose 

The purpose of this assignment is to

- review the basic syntax of a SQL query, and

- use aggregate functions to group the values of an entire table or several rows to form a single summary value.

Aggregations a very powerful means to get statistics about large amounts of data. Oftentimes it isn't enough to query records, you may need to calculate summaries of a table or subgroups of a table. Aggregation operations group values from multiple rows together, and can perform variety of operations on the grouped data to return a single result.
## Tasks

### Question: Design the following queries, using the lyrics.sql schema:

#### Part 1
- List the first name, last name, home phone, and gender of all members from Georgia who either have a home phone in area code 822 or are  female

- List all the information of tracks that do not have an MP3.

- List the TitleID, Title, and UPC of any titles whose UPC end with '2'

- List the artist name and web address of any artists who has a web address. Rename the attributes artistname, webaddress as Artist Name, Web Address.

- List the TitleID, TrackNum, and TrackTitle of all tracks with 'Song' at the beginning of the TrackTitle

#### Part 2

- Report the average, shortest and longest track length in minutes of all tracks.

- Report the number of male members who are in US.

- Report the number of tracks for each TitleID

- Report the total time in minutes for each titleid

- Report the number of members by state and gender. Sort the results by the region

