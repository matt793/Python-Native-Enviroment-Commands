# Python Native Enviroment Commands
Python Native Enviroment Commands - Making and controling enviroments.

## List the pip packages of your global set, or an enviroment set:
    `pip3 list`

## Make a new enviroment:
    `python3 -m venv <add project env name here>` 

## Activate enviroment:
    `source <add project env name here>/bin/activate`

## Check to see which python you are in (enviroment, or global):
    `which python`

## Install packages:
    `pip install <package name>`

## Freeze packages into correct format for requirment file:
    `pip freeze`

## Put frozen package into requirment file:
    `pip freeze > requirments.txt`

## Check requirments:
    `cat requirments.txt`

## Deactivate enviroment:
    `deactivate`

## Delete enviroment:
    `rm -rf <add project env name here>`

## Add a pre-made requirments file to a new enviroment:
    `pip install -r requirments.txt`

## Put all global package into an enviroment:
    `python3 -m venv <add project env name here> --system-site-packages`
