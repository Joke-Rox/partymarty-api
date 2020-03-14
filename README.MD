# Flask API for the Partymarty App

## Setup for Joke

open terminal app
[get homebrew](https://brew.sh/index_de) by entering this command:
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
$ brew install git
$ brew install python3
$ brew install poetry

close the terminal window and open a new one

$ poetry install
$ poetry shell
$ python3
>> from app import db
>> db.create_all()
>> quit()
$ flask db upgrade
$ exit

## General Setup:

[get python3](https://wiki.python.org/moin/BeginnersGuide/Download)
[get poetry](https://python-poetry.org/docs/)

$ poetry install
$ poetry shell
$ python3
>> from app import db
>> db.create_all()
>> quit()
$ flask db upgrade
$ exit

