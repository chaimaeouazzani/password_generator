# README
	This file runs a simple command that prints "Hello WelcomeFiles!"

## Common commands
	'make' or 'make hellomakes' to compile the file, everytime a change is made in the file
this command should be rerun. 
	for example: 
hellomake: hellomake.o hellofunc.o
	 $(CC) -o hellomake hellomake.o hellofunc.o
hellomake.o and hellofunc.o checks if a change had made run the command

	'clean':  remove hello and all object files, it clears up the temporary files that has been
created
