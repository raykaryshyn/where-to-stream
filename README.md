# CMSC447Project
This is the repository for CMSC447 Project.

## Usage
Installing packages needed for python and flask
	Run these commands:
		sudo apt install -y python3-pip
		sudo apt install -y build-essential libssl-dev libffi-dev python3-dev
		sudo apt install -y python3-venv
	Make sure you're in the CMSC447Project directory
	Run
		python3 -m venv env
To activate environment
	Make sure you're in the CMSC447Project directory
	Run
		source env/bin/activate
	Once you see (env) prior to the username on the terminal
	Run
		pip install -r requirements.txt
To run test.py flask application
	export FLASK_APP=test
	export FLASK_ENV=development
	flask run
In the vm open the web browser and go to http://127.0.0.1:5000/
You should be able to see the web page
