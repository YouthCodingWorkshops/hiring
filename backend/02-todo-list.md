# Challenge 2: TODO List

* Technologies: Python, SQLite3, Flask/DJango
* Tests: Required
* Documentation: Required, in a `README.md` file
* Live Link: Not required, nice to have

For this challenge, you'll be developing an API in python that allows a user to view, create, edit, and delete tasks they need to complete. Each task should contain the following information:
* id: A randomly generated number
* name: Task name 
* description: Task description
* ctime: Timestamp this task was created at
* dtime: Timestamp for this task's due date

Your API should interact with a mock SQL database (look into the SQLite3 python module). If you're using Flask or Django, build a dead simple website (literally bare HTML will do just fine).

Since you store timestamps and use SQL, the UI should be able to do the following:

1. By default, sort tasks based on their creation time from earliest to latest
2. Sort tasks by due date (closest to furthest) from the current datetime. 
3. Allow the user to search their tasks by name

#### Reminders

1. Make sure to have proper error handling
2. The point of using a database is to keep you away from storing all your data in a single giant python dictionary
3. Include tests

Good luck!
