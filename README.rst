An intuitive and simple database library with expressions based on sprintf formatting.

Example::
	
	$mydb = new MySQLdb('localhost', 'root', 'password', false, 'database_name);
	$result = $mydb->query("SELECT 1 FROM table WHERE fieldname = %s AND other_fieldname = %d", 'mystring', 5);