Python Environment Setup and Installation Guide

This README provides step-by-step instructions for setting up your Python environment and installing the necessary dependencies for running your project.

Prerequisites

Before installing any dependencies, ensure you have the following:

Python Installed:

Download and install Python from python.org.

Add Python to the system PATH during installation.

Verify the installation:

python --version
pip --version

Pip (Python Package Installer):

Pip is included by default in Python installations (Python 3.4+).

If not installed, install pip manually:

python -m ensurepip --upgrade


Dependency Installation

1. Install Quart

Quart is the primary web framework being used:

pip install quart

2. Install Quart-CORS

For Cross-Origin Resource Sharing (CORS):

pip install quart-cors

3. Install pymavlink

For communicating with drones:

pip install pymavlink

4. Install pyserial

For serial communication with devices:

pip install pyserial

5. Additional Recommended Libraries

Ensure these libraries are installed if needed for your project:

Flask-SocketIO: For WebSocket support:

pip install flask-socketio

aiohttp: For asynchronous HTTP handling:

pip install aiohttp

Verifying Installations

To verify that all libraries are installed correctly, run:

pip list

Check for the following packages and their versions:

quart

quart-cors

pymavlink

pyserial

Common Troubleshooting Tips

Ensure Pip Is Working:
If pip is not recognized, use:

python -m pip install --upgrade pip

Handle Permissions Issues:
Use the --user flag if you encounter permissions problems:

pip install <package_name> --user

Correct Python Version:
Ensure you're using the correct Python version (e.g., Python 3.7+).
Check the version:

python --version


Final Step: Running the Project

Once all dependencies are installed, run your project:

python <script_name>.py

Replace <script_name> with the name of your Python script, e.g., backend.py.

