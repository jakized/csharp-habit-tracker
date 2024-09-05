

1. Create database and table
	connectionString;
	instance of SqliteConnection class
	using statement because of proper use of garbage collector
	command to send to the db (@"CREATE TABLE IF NOT EXISTS table_name)
	ExecuteNonQuery no return from db, no values

2. Creating user input (MENU STYLE)
	always clear the console
	get input using a loop
	switch the user input (depending on the variable type)


3. Method for Adding
	since the input has a date, a method for adding a date is needed
	same for quantity (a new method)
	INSERT INTO

4. Method for getting all the habits
	open the connection to db
	make a list of class <whatever_habit> to store db data
	create an sqlite reader to read the data from db (SqliteDataReader reader = tableCmd.ExecuteReader();)

5. Method for deleting a habit
	getting the user input for habit Id is important
	call the method GetNumberInput, pass the message
	open the db connection
	DELETE FROM push_ups WHERE Id = '{habitId}

6. Update
	