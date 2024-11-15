# Power_Consumption_forcasting
Description

power consumption forecasting model which uses Mean Squared Error (MSE) as metric for predition
Git and other commands used in command prompt:

    mkdir <file_name> to create the folder
    cd <file name> to go inside the folder
    git init, initializing folder as git repository
    git add . to add all the files into git track
    git commit -m "<message>", it commits whatever is there in the track
    git remote add origin <GitHub repository link>, builds connection between git and github
    git push --set-upstream origin master, sends all the files from git to github.

Docker commands:

    docker build -t <folder_name> .
    docker run <folder_name>

Selenium: pip install selenium
Steps:

    Create the required files such as the dataset csv file, training model python file, requirements.txt file and Dockerfile
    Create a new item under Freestyle Project in Jenkins
    Select Git in Source Code Management and paste your repository url in the given space
    Add Execute Windows Batch Command step in Build Steps
    Save the configurations
    Build now and visualize the console output
    Now open the command prompt with the path of the folder containing the requied files
    Run the docker commands mentioned above in the command prompt
    Visualize the result in the command prompt and in the Docker desktop app
    Install selenium from the command prompt
    Execute the selenium commands
