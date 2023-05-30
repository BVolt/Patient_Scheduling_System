# Patient Scheduling System

## Instructions for Running Localy

First ensure the desired system has docker installed. After cloning the repostiory, execute `docker compose up -build` in the project directory. This will build the necessary container for frontend, backend, and database. The frontend client will be present at http://localhost:3000 on your web browser. The mock user credentials for patient and clerk are as follows (email, password): (user@hosptial.com, user) (clerk@hospital.com, clerk).


## Description

This web application simulates a subsystem for scheduling appointments for patients. The application is designed to take in two types of users either the clerk or the patient. The system provides CRUD operations for patients records, user accounts, and appointments. 
