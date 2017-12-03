A tool for displaying incremental file content

It works like 'cat' but always displays only the last lines from the given file.
Action:
We display the contents of the file 'file.log' on the screen with the command: logtail2 file.log
Later, someone will add a few lines to this file.
We run the command again: logtail2 file.log
Now only new lines will be displayed, those that have been added since our last display

usage:

logtail {file_name}
