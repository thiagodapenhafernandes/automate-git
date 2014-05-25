automate-git
============

Do faster versioning at you daily git comand processes with this great shell tool!


###Instalation

Run inside the project:
	$ echo functions.txt >> ~/.bashrc && source ~/.bashrc
	
	
###Usage
	#comit your files, change branch, and syncronize with your cloud repository:
	super-project(develop)$ comit "<comand>"

	#just syncronize local work tree with your cloud repository:
	super-project(develop)$ update
	
	#bring changes from master branch and run default comands for rails:
	super-project(develop)$ merge_master_and_run
