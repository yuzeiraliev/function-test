# function-test

## Basic information about employees from different companies ##

Using templatefile and lookup functions, we retrieved basic information about an employee .

Initially, two variables were created ( "name" and "role"), then they were referenced in our template file in order to insert the respective variable values into the file.Templatefile function was used in output value which takes two arguments: the template file name and a map of template value assignments.

On the second part of the task, additional variable was created ("test-map") containing a map with information about the employee workplaces and in order to retrieve the value of a specific key in our map , lookup function was used in output value which arguments are a map, the key to access in the map, and optionaly a default value in case the key does not exist. 
