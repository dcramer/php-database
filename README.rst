An intuitive and simple database library with expressions based on sprintf formatting.

Example::

$result = $mydb->query("SELECT 1 FROM table WHERE fieldname = %s AND other_fieldname = %d", 'mystring', 5);