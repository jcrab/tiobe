# tiobe
Create a fully functional, database-driven, PHP system for the [TIBOE index](https://www.tiobe.com/tiobe-index/) of popular programming languages.  Create the DDL for your database based on the current rankings.  Be sure to include: current rank, last year's rank, and language.  Since all three of these values may change, it will be important to create a row id that is unique (auto increment values work nicely).  Within your DDL file insert rows for at least the current top 10 languages.

This application must support all of the CRUD operations:

* Create: insert a new language with rankings
* Read: display the entire contents of the table (excluding id)
* Update: allow the end-user to choose a row to change, display the current values, and then allow them to change any or all three of the values
* Delete: allow the user to delete a row

Anyone can display the list of rankings at any time.  In order to modify the table, the user must be a registered user.  Allow new users to register as well.

This is a group project using a single repository.  You will need to negotiate the use of git with your team.  Branching and merging are encouraged.  You may use pull requests and/or issues or any other technique for team communication.  Grading may include evaluating the contributions of your teammates.  Please choose tasks that challenge your current abilities and take advantage of the opportunity to learn from others.
