Workstation Wonders
Welcome to Workstation Wonders, a custom website offering a curated selection of desk essentials and gadgets to enhance your workspace experience. This repository contains all the necessary files and instructions to get started with the project.

Overview
Workstation Wonders is comprised of the following components:

Backend: Python FastAPI backend code responsible for handling server requests and database operations.
Database: Contains the dump of the MySQL database. Import this dump into your MySQL database using MySQL Workbench tool.
Dialogflow Assets: Includes training phrases and other data for configuring intents in Dialogflow.
Frontend: Website code for the Workstation Wonders website.
Installation:

![Workstation Wonders Logo](image.png")


To set up the project, follow these steps:

Install required Python modules:
bash

>>> pip install mysql-connector
>>> pip install "fastapi[all]"

Or simply run:
bash

>>> pip install -r backend/requirements.txt

Running the Backend Server
To start the FastAPI backend server, follow these instructions:

Navigate to the backend directory in your command prompt.
Run the following command:
bash

>>> uvicorn main:app --reload
>>> Ngrok for HTTPS Tunneling

For HTTPS tunneling, you can use ngrok. Follow these steps to set it up:

Install ngrok from https://ngrok.com/download and choose the version suitable for your OS.
Extract the zip file and place ngrok.exe in a folder.
Open Windows command prompt, navigate to that folder, and run the following command:
bash

>>> ngrok http 8000

Note: Ngrok sessions can timeout. If you encounter a session expired message, restart the session.

Contributors
Your Name : Madhumitha Kolkar

Acknowledgments
Special thanks to Dialogflow for providing the conversational platform for our chatbot, Noah.
Inspired by the need for efficient and enjoyable workspaces everywhere.