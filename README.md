# Python Native Environment Commands
Python Native Environment Commands - Making and controling environments in python.

## List the pip packages of your global set, or an environment set:
    `pip3 list`

## Make a new environment:
    `python3 -m venv <add project env name here>` 

## Activate environment:
    `source <add project env name here>/bin/activate`

## Check to see which python you are in (environment, or global):
    `which python`

## Install packages:
    `pip install <package name>`

## Freeze packages into correct format for requirment file:
    `pip freeze`

## Put frozen package into requirment file:
    `pip freeze > requirments.txt`

## Check requirments:
    `cat requirments.txt`

## Deactivate environment:
    `deactivate`

## Delete environment:
    `rm -rf <add project env name here>`

## Add a pre-made requirments file to a new environment:
    `pip install -r requirments.txt`

## Put all global package into an environment:
    `python3 -m venv <add project env name here> --system-site-packages`
