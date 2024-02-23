# Pastelink API Quickstart

This is a simple starter project that demonstrates all of the API endpoints provided by Pastelink.

## Requirements

Python 3

## Quickstart Guide

(This is a basic guide for windows users. Different OSs might need to enter slightly different commands to operate this project.)

Start by creating an API key within your Pastelink account: https://pastelink.net/account/api

If you're new to python, clone this repo and download the dependancies. Open a command line tool and follow these instructions:

We first recommend you create a venv:

cd to the project folder

````python -m venv.````

Activate the env.

On windows: ./.venv/Scripts/activate

On Linux: source ./.venv/bin/activate

````pip install -r 'requirements.txt'````

Copy the env.example

````cp env.example .env````

Edit this new .env file to add your API key

Now you can run main.py with:

```` python main.py````

This should now have pinged the Pastelink servers with all available requests, with the dry_run flag activated. You can now edit main.py and change it to your needs. Make sure to set the dry_run flag to 0 when you're done testing.