# Simple-Blockchain-Server
A simple blockchain server implemented in Python; uses the Flask Micro-Framework to make it easier to map endpoints to Python Functions. Clients can use http to communicate with the service that can be set up to run on a defined port. See installation instructions below:

## Installation:
1) Requires:
      * [Python 3.6.X or above](https://www.python.org/downloads/)
      * [Pip](https://pip.pypa.io/en/stable/installing/)
      * pipenv -- install using Pip '''$ pip install pipenv'''
 
2) Setup the environment:
      * '''$ pipenv --python=python3.6'''
      * '''$ pipenv install'''

3) Run the Server:
      * Default port: '''$  pipenv run python Server.py'''
      * Specified port: '''$  pipenv run python Server.py [-p or --port <port #>]'''

## Credits: 
1) Daniel Van Flymen's [tutorial](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46) was very helpful for the implementation and some concepts.

2) William Mougayar's [article](https://www.oreilly.com/ideas/understanding-the-blockchain) was helpful for understanding some of the concepts.
