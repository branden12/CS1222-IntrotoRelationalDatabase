# Homework 3

## Purpose

Purpose 

The purpose of this assignment is to

- review the basic syntax of a SQL query, and

- use aggregate functions to group the values of an entire table or several rows to form a single summary value.

Aggregations a very powerful means to get statistics about large amounts of data. Oftentimes it isn't enough to query records, you may need to calculate summaries of a table or subgroups of a table. Aggregation operations group values from multiple rows together, and can perform variety of operations on the grouped data to return a single result.
## Tasks

### Question: Design the following queries, using the lyrics.sql schema:

#### Part 1

- List the artistname and entrydate of the artist with the earliest entry date.

- List the track titles of all titles in the 'alternative' genre. 

- List all genres from the Genre table that are not represented in the Titles table.

- List the track title with longest length in seconds.

- List length of the longest RealAud track in the 'metal' genre

- List track titles and lengths of tracks with a length longer than all tracks of the 'metal' genre. (Hint: This requires sub-query within a sub-query)

#### Part 2

- List the CD title and the title of all tracks recorded in StudioID 1

- List each title from the Title table along with the name of the studio where it was recorded.

- Find the name of the sales person who works with the member with last name 'Alvarez'

- List name of members from California (CA) and their salespeople.

- List the names of all artists who have recorded more than one titles and the number of titles they have.   

- Report the name of the title and number of tracks for any title that have fewer than 9 tracks.
