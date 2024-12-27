# Music_Store_Data_Analysis_Using_SQL

##Project Overview:

The "Music Store Data Analysis" project focuses on utilizing SQL to answer business-related queries by analyzing a music store's dataset. The dataset comprises multiple relational tables capturing various aspects of the music store's business operations, such as albums, artists, customers, invoices, tracks, playlists, and more.

The project is divided into three levels of difficulty, with each set of questions focusing on different business metrics and operations:

Easy
Moderate
Advanced
This SQL project covers queries ranging from basic retrievals to advanced data manipulation and analysis, demonstrating skills in SQL functions, joins, aggregations, subqueries, and advanced filtering techniques.

Detailed Table Information:
album.csv: Stores information about the music albums in the store.
artist.csv: Contains details about the artists who have contributed to the albums.
customer.csv: Includes customer details such as name, email, and country.
employee.csv: Information about employees, including their job titles and the hire date.
genre.csv: Holds the genre information for various tracks.
invoice.csv: Records transactions made by customers, including invoice date and billing details.
invoice_line.csv: Represents individual items in each invoice, linking invoices to tracks.
media_type.csv: Describes the format of each track, such as MP3, AAC, etc.
playlist.csv: Holds details of playlists created in the music store.
playlist_track.csv: Links tracks to playlists.
track.csv: Stores information about each track, including track name, album, genre, and length.
Questions Addressed:
Question Set 1 - Easy:
Who is the senior most employee based on job title?

Query to find the highest-ranking employee based on their job title.
Which countries have the most invoices?

Analyze invoices and group by country to determine the regions with the highest sales.
What are the top 3 values of total invoices?

Identify the three largest invoices in terms of total amount.
Which city has the best customers?

Find the city with the highest revenue from customers, a key metric for promotional events.
Who is the best customer?

Identify the customer with the highest total spending, defining them as the store's "best" customer.
Question Set 2 - Moderate:
Find all Rock music listeners (with email, first name, and last name) ordered alphabetically by email.

Query to list customers who have purchased Rock music, with results sorted by their email addresses.
Top 10 Rock music artists based on track count.

Identify the most prolific Rock artists by counting the number of tracks attributed to them.
Tracks longer than the average song length.

Return all tracks that have a length greater than the average, ordered from longest to shortest.
Question Set 3 - Advanced:
Amount spent by each customer on specific artists.

For each customer, calculate how much they have spent on music by individual artists.
Most popular music genre per country.

Determine the top-selling genre for each country based on invoice data, with special handling for ties.
Top customer by spending in each country.

Find the customer who has spent the most money in each country, with tie-handling for customers who spent equally.
SQL Concepts Covered:
This project demonstrates the use of SQL in various scenarios, such as:

Basic SELECT queries to extract necessary data.
JOIN operations to combine data from multiple tables.
GROUP BY and aggregation to compute sums, counts, averages, etc.
Subqueries and nested queries for advanced filtering.
Sorting and ordering of query results.
Handling ties in grouped data.
Filtering with WHERE conditions and HAVING clauses.
The project walks through each question step-by-step, providing a comprehensive analysis of business data using SQL.
