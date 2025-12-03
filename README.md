## Programmer Assessment Q4

This repository contains a broken web app built with Dash. Please follow the tasks below.

Tasks:
1. Clone this repo to your machine.
2. Fix missing dependencies and fill authors section in `pyproject.toml`.
3. Fix bugs prevent the app `main.py` from running.
4. Change port the app ruuning on to `10030`.
5. Commit you changes.
6. Update `README.md` with a instruction
   1. Assuming the user has a fresh minimum Linux installation with no python.
   2. Setup python and virtual environment for this app, remember to use the fixed `pyproject.toml`.
   3. How to run this app and how to access it without portforwarding.
7. Push all the changes to your own repository on Github, and provide a link to your own repo in your submission in the last.



Instructions
1: Install python by running the following commands.
   sudo apt update
   sudo apt upgrade
   sudo apt install python3
2: install pip by running the following command
   sudo apt install python3-pip

3: install dependencies for both python following commands
   sudo apt install python3-dev python3-venv build-essential
4: navigate to where you installed the project and running the following command to download dependencies
   pip install -e

5: Run the app and connect to http://127.0.0.1:10030/. This will run a local copy of the app on your computer
