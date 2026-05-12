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

## How to use the form
I made the form pretty simple to use. Here is how it works step-by-step:

* **To add someone new**: Just type the Roll-No and hit Enter. The rest of the form will open up so you can type in the name, class, and other info. When you're finished, just hit **Save**.
* **To change a record**: If you type a Roll-No that is already in the database, the form will find it and show you all their details automatically. You can change whatever you need and then hit **Update**.
* **If you make a mistake**: Just click **Reset**. It clears everything out and puts the cursor back at the top so you can start over.


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
