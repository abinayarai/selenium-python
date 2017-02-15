This is selenium project written in python

1. Clone this project into the machine or get the zip file.
2. Run the command to create a virtual environment 
        virtualenv selenium-python
   If you don't have virtualenv, run the following command
        sudo apt-get install python-virtualenv
3. Go inside the folder (selenium-python) and start the virtual environment using the commands
        cd selenium-python
        source bin/activate
4. Install selenium using the following command
        pip install -U selenium
5. Download the drivers from https://pypi.python.org/pypi/selenium and add the path to the drivers in PATH
        export PATH=$PATH:path_to_drivers


# This is just a suggestion as I like it this way
Create a folder inside the root folder(selenium-python) called 'drivers' to install the folder
