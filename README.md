This is a simple prototype for fastAPI with PostgreSQL on local server. 

Follow these steps to get up and running this project in your local system:

#Prepare your Database instance

Step 1: Download and Install PostgreSQL from it's official website: 'https://www.postgresql.org/'.

Step 2: Open GUI application of PostgreSQL named as 'pgAdmin 4', in your system and create a database named as 'my_team2'. (Feel free to play around names, don't forget to make the respective changes in the code too).

Step 3: Create  a table named as 'teams' with three columns for now, 'id', 'name' and 'city'.

#Prepare your environment

Step 4: Create a project folder and inside it, Create a new environment, and install all dependencies in it. (Libraries to be installed are mention in the 'requirements.txt' file).

#Prepare your project

Step 5: Copy and Paste these three Python files (here in this project folder) named as 'database.py', 'main.py', 'models.py'.

#Running your project

Step 6: In CMD, simply change directory to your project folder, activate your environment and run following command to run the project: 'uvicorn main:app --reload'.

Step 7: Open 'http://127.0.0.1:8000/', you should see a message as 'server is running' and open 'http://127.0.0.1:8000/docs' for complete API test.

For any help or assistance, connect aalekh.rai.futurense@gmail.com
