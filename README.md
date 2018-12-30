Bash script that attempts to replicate virtualenvwrapper's workon command. You must have a $WORKON_HOME environment variable set to use this. At the moment, this only works if you source the script while giving it the name of the virtual environment you want to use.

For example, for a virtual environment names "virtualenv", you would do "source workon virtualenv" and it would run the command ". $WORKON_HOME/virtualenv/bin/activate". Running it with no parameters will run the command "ls $WORKON_HOME".
