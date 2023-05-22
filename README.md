
# Homework 6

## Purpose

The goal of this module is to familiarize yourself with some of the ways in which database schemas use constraints to ensure consistency.

## Tasks

### Data Manipulation

#### In this lab, you will be manipulating the database to add, delete and modify the values in the database. Please use a "select * from..." after each query to show the effects of your data manipulation query.

- The title 'Time Flies' now has a new track, the 11th track 'Spring', which is 150 seconds long and has only a MP3 file. Insert the new track into Tracks table (Don’t hand-code any data for insert that can be looked up from the Titles table).

- Create a new table called Members2 with the same fields as the Members table. (Use DESCRIBE to check if Members2 table is created). 

- Populate Members2 with the content of the Members table.

- The area code for Columbus, Ohio has been changed from 277 to 899. Update the homephone and workphone numbers of all members in Members2 table accordingly.

- Delete all members who work for the artist 'Sonata' from Members2 table.

### Extra Credit

#### The following are harder questions. They have to do with either multiple joins on tables, multi insert queries, or using the CASE keywords.

- Members Doug Finney and Terry Irving are forming a new artist to be called "Doug and Terry." Add this record to the Artists table, using ArtistID 13, the address information of Doug Finney, no web address, today's entry date, and no lead source. Don’t hand-code any data for insert that can be looked up from the Members table.

- Add the appropriate new records to the XrefArtistsMembers table for the artist "Doug and Terry". Doug is the responsible party. Don’t hand-code any data for insert that can be looked up from the Members table. (This will use the CASE keyword to get it to work. Go back to the Functions ppt to see an example of how CASE works)
