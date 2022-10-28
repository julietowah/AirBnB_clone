# AirBnB_clone
This is a team project to develop a Python3 console that emulates the AirBnb object management.

<!DOCTYPE HTML>
<html>
 <head>
    <link rel="stylesheet" href="styles.css" />
  </head>
 <body>
  <h1>AirBnB clone - The console </h1>
  <div> Description
This team project is part of the ALX School Full-Stack Software Engineer program. It's the first step towards building a first full web application: an AirBnB clone. This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data. </div>
  <div> Description of the command interpreter.
The console is a Unix shell-like command line user interface provided by the python CmdModule It prints a prompt and waits for the user for input, for our project we used (hbnb) </div>
  <table>
   <tr>
   <th>Command</th>
   <th>Examples</th>
   </tr>
   <tr>
   <td>Display commands help</td>
   <td>(hbnb) help <command></td>
   </tr>
   <tr>
   <td>Create object (prints its id)</td>
   <td>(hbnb) create <class></td>
   </tr>
   <tr>
   <td>Destroy object</td>
   <td>(hbnb) destroy <class> <id> or (hbnb) <class>.destroy(<id>)</td>
   </tr>
  <tr>
   <td>Show object</td>
   <td>(hbnb) show <class> <id> or (hbnb) <class>.show(<id>)</td>
   </tr>
   <tr>
   <td>Show "all" objects or instances class</td>
   <td>(hbnb) all or (hbnb) all <class></td>
   </tr>
   <tr>
   <td>Run console</td>
   <td>./console.py</td>
   </tr>
   <tr>
   <td>Quit console</td>
   <td>(hbnb) quit</td>
   </tr>
   </table>
  <p>Execution Example</p>
   <div>In interactive mode
   <div>$ ./console.py
	(hbnb) help

	Documented commands (type help <topic>):
	========================================
	EOF  help  quit

	(hbnb)	
	(hbnb)
	(hbnb) quit
	$
  </div>
  </div>
  <div>In non interactive mode
  <div>$ echo "help" | ./console.py
	(hbnb)

	Documented commands (type help <topic>):
	========================================
	EOF  help  quit
	(hbnb)
	$
	$ cat test_help
	help
	$
	$ cat test_help | ./console.py
	(hbnb)	

	Documented commands (type help <topic>):
	========================================
	EOF  help  quit
	(hbnb)
	$
  </div>
  </div>
  <div>All the code is tested with the unittest module. The test for the classes are in the test_models folder.</div>
</body>
</html>
