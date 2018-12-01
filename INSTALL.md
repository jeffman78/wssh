# Installation

## Create and activate a python2 Virtual Environnement

	virtualenv2 ./venv
	source ./venv/bin/activate

## Install client & server requirements

	pip install -r requirements.txt
	pip install -r requirements_server.txt

## Install the wssh library

	python setup.py install

## Start the server

	./bin/wsshd

## Connect to the server

	http://0.0.0.0:5000
