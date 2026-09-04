# RaceDay - Part 1: System Planning and Database

## What this project is about

RaceDay is a web based system built for the South African road running, walking, and cycling community. It helps Event Organisers create and manage events, categories, and participant results. It also helps Participants browse events, enter events, and track their own results.

This part of the project, Part 1, only covers planning. No application code was written in this part. The goal was to plan the database, the API, and the roles before any coding starts in Part 2.

## The two user roles

**Organiser**
An Organiser can create, edit, and delete events. An Organiser can also manage the categories inside their events, capture participant results, and view everyone who has enrolled in their events.

**Participant**
A Participant can create an account, browse all events, enter an event by picking a category, view their own enrolments, and check their own past results.

## What is inside the /docs folder

- `raceday_erd.png` - the Entity Relationship Diagram showing all 6 database tables, their fields, and how they connect to each other.
- `api_endpoint_plan.md` - a table listing every API endpoint the system will have, including the method, route, description, role needed, request body, and expected response.
- `raceday_database.sql` - the SQL script that creates the full database in SQL Server Management Studio (SSMS) and fills it with sample test data.

## How to run the SQL script

1. Open SQL Server Management Studio (SSMS).
2. Connect to your local SQL Server.
3. Open the file `raceday_database.sql`.
4. Click Execute to run the whole script.
5. The script will create a new database called `RaceDayDB` with all 6 tables and sample data already inside it.

## CI/CD Build Status

[Add your screenshot of the successful green build here]

## YouTube Video

[Add your unlisted YouTube video link here]

In the video, I walk through the ERD and explain each table and relationship, walk through the API endpoint plan and explain the choices made, and run the SQL script live in SSMS to show it works with no errors.
