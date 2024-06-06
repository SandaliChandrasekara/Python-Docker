**Python Application**

_Run the application_

Inside the python-docker directory, run the following command in a terminal.


**docker compose up --build**

Open a browser and view the application at http://localhost:8000. You should see a simple Flask application.

In the terminal, press ctrl+c to stop the application.


_Run the application in the background_

You can run the application detached from the terminal by adding the -d option. Inside the python-docker directory, run the following command in a terminal.


**docker compose up --build -d**
Open a browser and view the application at http://localhost:8000.

You should see a simple Flask application.

In the terminal, run the following command to stop the application.


**docker compose down**
