# Instagram-Project
This repository contains the SQL schema and sample data for a simplified Instagram clone. The schema includes tables for users, posts, likes, comments, and other essential features required for a social media platform. The provided SQL file initializes the users table with sample user data, showcasing how to insert records with timestamps.

1. Instagram Clone Database Schema & Data Insertion
The first part of the project involves building a foundational database schema for an Instagram-like social media platform. The schema includes the following tables:

Users: Stores basic information like user IDs, usernames, and timestamps for when the account was created.
Posts: Contains information about the posts made by users, including the post's content, the timestamp, and references to the users who created them.
Comments: A table designed to store user comments on posts, along with the timestamp and associated post and user IDs.
Likes: A simple table tracking which user liked which post, providing basic functionality to simulate the 'like' feature.
The database is seeded with a dataset of users, making it ready for testing and further development. The users table is initialized with a set of 50 sample user records, each containing a username and timestamp for when the account was created.

2. Real-World Problem Solving with SQL
The second part of this project tackles various real-world queries using SQL, simulating the types of analytical queries that might be executed on an actual social media platform. Some examples of real-world problems answered in this part include:

Finding Active Users: Identifying users who have posted or interacted (liked, commented) most frequently over a given time period.
Popular Posts: Writing queries to find which posts have the most likes and engagement.
User Interaction Analysis: Queries to identify which users interact with each other the most, either through likes or comments.
Content Trends: Analyzing which type of posts (by keywords or hashtags) generate the highest engagement.
Growth Analytics: Tracking user growth by calculating how many users registered during specific time periods.
