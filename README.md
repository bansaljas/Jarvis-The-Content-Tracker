# Jarvis-The-Content-Tracker

This project is an attempt for <b>a basic implementation</b> of a version control system from scratch. 

>We have implemented the following commands:<br>
><i>1.	init<br>
>2.	status<br>
>3.	add<br>
>4.	commit<br>
>5.	diff<br>
>6.	log<br>
>7.	hash-object<br>
>8.	cat-file<br>
>9.	ls-files<br>
>10.	reset </i>

These commands are at the core of the VCS, and we have implemented them with the same functionality as in a normal VCS system.<br> 
Note: This VCS implementation will run only on a <i>Unix-based platform</i>.

<b>How to run the VCS:</b>

To begin tracking of changes by the VCS, we need to first initialize a repository(directory). This could be done in two ways: <br>1) telling the VCS to create a new repository<br> 2) giving the VCS path to an existing empty repository. This is done by the init command.

><div align="center"><i>For example:  <b>python3 jarvis.py init myrepo</b></i></div>

Thus, first we need to write python3 (version of python) then we need to specify the name of our VCS file, finally the command along with its arguments.

Note: To obtain information about the commands and their arguments type:<br>
><div align="center"><i><b>python3 jarvis.py --help</b></i></div><br>
Then change your directory to the current repository. After that, to run the commands you wish you need to specify the complete path of jarvis.py file.

