# Student Enrollment & Employee Form System

## Description
This is my mini-project where I created two forms (Student and Employee) that connect to a database called **JSONPowerDB**. The main goal was to make a form that is smart enough to know if a person is already in the database and help the user either save new data or update old data without making mistakes.

## Table of Contents
* [Why I used JsonPowerDB](#why-i-used-jsonpowerdb)
* [What the form can do](#what-the-form-can-do)
* [How to use it](#how-to-use-it)
* [Project Status](#project-status)
* [Sources](#sources)

## Why I used JsonPowerDB
I chose JSONPowerDB for this project because:
* It is **really fast** at saving and finding data.
* It doesn't need a complicated setup like traditional SQL databases.
* It works directly with JavaScript, so I didn't need to write a separate back-end.
* It handles "Schema-less" data, which made it easy to add all the fields I needed.

## What the form can do (Scope)
* **Smart ID Check**: As soon as you type a Roll No or Employee ID, the form checks the database for you.
* **Auto-Fill**: If the person is already in the system, it fills out all their info automatically.
* **Locked Fields**: It locks the ID field when you are updating so you don't accidentally change the wrong record.
* **Safety Lock**: If you start changing the ID after it's been checked, the form locks up and clears out until you validate the new ID.
* **Validation**: It won't let you save if you leave any fields empty.

## How to use it (Examples)
1. **To Add New Data**: Type a new Roll-No. The other boxes will open up. Fill them in and hit **Save**.
2. **To Change Data**: Type an ID that's already in the database. The info will pop up. Change whatever you need and hit **Update**.
3. **To Clear**: Just hit **Reset** to start over with a fresh form.

## Project Status
* **Current Version**: 1.0.0
* **Status**: Fully working and finished!

## Release History
* **First Release**: Created the basic form and JPDB connection.
* **Final Update**: Added the "Human-Made" design, multi-column layout, and the final safety logic.

## Sources
* JSONPowerDB Docs: [login2explore.com](https://login2explore.com)
* Styling: Bootstrap 3 and some custom CSS I wrote.

---
*Created by Giri as part of my JSONPowerDB training.*
