"# remote-python" 

https://gist.github.com/alvarocavalcanti/24a6f1470d1db724a398ea6204384f00


To rebuild this image use: 
`docker-compose build` or `docker-compose up --build`


# Project Setup Instructions

## Steps to Open and Run an Existing Python Project in PyCharm

1. **Open PyCharm**: Launch the PyCharm application.

2. **Open Project**: 
   - Select 'File' > 'Open' from the top menu.

3. **Locate Project**: 
   - Navigate to the local directory where your Python project is stored.
   - Select the project folder and click 'OK'.

4. **Create Virtual Environment**: 
   - In PyCharm, go to 'File' > 'Settings' > 'Project: [Your Project Name]' > 'Python Interpreter'.
   - Click the gear icon, select 'Add', and choose 'Virtualenv Environment'.
   - Under 'Base Interpreter', navigate to `C:/swtools/Python39/Scripts/python.exe`.
   - Click 'OK' to create the virtual environment.

5. **Access Files**: 
   - Your project files will appear in the Project pane on the left side.

6. **Run the Project**: 
   - Right-click the main Python file (e.g., `main.py`) in the Project pane.
   - Select 'Run'.
