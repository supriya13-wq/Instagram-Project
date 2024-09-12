# Instagram-Project
This repository contains the SQL schema and sample data for a simplified Instagram clone. The schema includes tables for users, posts, likes, comments, and other essential features required for a social media platform. The provided SQL file initializes the users table with sample user data, showcasing how to insert records with timestamps.

1. Instagram Clone Database Schema & Data Insertion
The first part of the project focuses on building a foundational database schema that powers a simplified Instagram clone. Key tables include:

Users Table: Contains user information, including unique user IDs, usernames, and timestamps of account creation.
Posts Table: Tracks posts made by users, including post content, creation time, and the user responsible for the post.
Comments Table: Stores user comments on posts, referencing both the post ID and the user ID.
Likes Table: Captures the 'like' interactions between users and posts, maintaining a record of which user liked which post.
A dataset is seeded into the database, and 50 sample user records are pre-loaded into the Users table, making the schema ready for analysis and further development.

2. Real-World Problem Solving with SQL
The second part of the project tackles complex, real-world queries to extract meaningful insights from the database. These queries reflect the types of analytical questions a social media platform would ask to enhance its user engagement, improve features, and address operational challenges.

Some of the real-world SQL queries implemented include:
Oldest Users: Identify the five longest-standing users on the platform.
User Registration Analysis: Determine which day of the week sees the highest user registrations, to guide advertising and engagement campaigns.
Inactive Users: Identify users who have never posted a photo, in order to target them with engagement campaigns.
Contest Winner: Determine the user who has received the most likes on a single photo during a contest.
Average User Posts: Calculate how many times the average user posts.
Top Hashtags: Identify the five most popular hashtags used across all posts.
Bot Detection: Find users who have liked every photo on the platform, signaling potential bot behavior.
Celebrity Accounts: Detect users who have never commented on any post, a common behavior of celebrity or passive accounts.
Advanced Analytical Challenges:
Bot and Celebrity Detection: Calculate the percentage of users who either never commented on a post or have commented on every photo.
User Interaction Analysis: Discover patterns in user activity, identifying frequent likers and commenters to understand interaction dynamics.
These queries offer practical insights into user behavior, content engagement, and platform health, and the project simulates real-world business use cases for a social media platform. The combination of database schema design and complex analytical SQL queries showcases a deep understanding of both data modeling and query optimization.
