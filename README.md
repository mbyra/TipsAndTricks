###Create python2 virtualenv
	environment_name = myenv
	virtualenv -p `which python2` ~/.virtualenvs/$environment_name 
	source ~/.virtualenvs/$environment_name/bin/activate
	echo 'alias activate="source ~/.virtualenvs/$environment_name"' >> ~/.bash_aliases

###Create python3 virtualenv
	environment_name = myenv
	python3 -m venv ~/.virtualenvs/$environment_name/bin/activate
	source ~/.virtualenvs/$environment_name/bin/activate
	echo 'alias activate="source ~/.virtualenvs/$environment_name"' >> ~/.bash_aliases

