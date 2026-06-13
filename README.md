  # EuroLeagues Database Management System

A relational database project implemented in MS SQL Server (T-SQL) designed to track European football leagues, teams, match data, and statistics.

## Project Architecture
The database consists of 7 main tables connected via foreign key relationships to prevent data anomalies:
* **Leagues & Teams:** Core setup for national divisions and clubs.
* **Players & Matches:** Tracks individual athletic records and fixtures.
* **Stats Tables:** Stores aggregate data points for both team performance and player scoring sheets.

## What is Inside
* Strict relational layout with safe cascading mechanics via subqueries.
* Analytical queries featuring string formatting, specific sorting rules, and accurate decimal tracking.
* Programmability units including an inline Table-Valued Function (TVF) to list top scorers and a flexible updates Stored Procedure.

## How to run
1. Open Microsoft SQL Server Management Studio (SSMS).
2. Create a clean database named `EuroLeagues`.
3. Run the scripts found inside `setup-database.sql`.
