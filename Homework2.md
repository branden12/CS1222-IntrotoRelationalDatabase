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
