# SentiMind

A twitter sentiment analysis web app based on a hashtag (using machine learning to assess sentiment)

## How To Use

In the terminal:

1. `git clone https://github.com/marcusfgardiner/SentiMind.git`
2. From the route of the directory `cd fullstack_template/static`
3. npm install

In order to run the server, you will need to [download python](https://www.python.org/downloads/) and then run: `pip3 install pipenv`

once pipenv is installed, run `pipenv install requests` to download the dependancies.

to run the server:

1. `cd fullstack_template/server`
2. `python3 server.py`

To run python tests:
1. Ensure you have run 'pipenv install requests' and 'npm install' as above to download dependencies
2. 'pipenv shell' to set up the python environment
3. 'nosetests' to run tests
