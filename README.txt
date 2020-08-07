SQL to MYSQL Copy
by pftq
August 6, 2020

This is a quick application for copying all rows from one SQL table to one with the same columns in MySQL.  There are additional options to loop (it will use insert or update on duplicates) or wipe the table clean each time for a full bulk re-insert.  Calling it with any arguments in commandline will have it run with last saved paramaters.
  
As with my other scripts, this was created in C# for a few tasks I needed to get done, but perhaps others out there might also find it useful.