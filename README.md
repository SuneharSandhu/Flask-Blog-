# Flask Blog
Blog website using Flask 

You should create a virtual environment and install the required dependencies using pip listed in 'requirements.txt'. 
It prevents using unecessary packages for the application 

# Python Virutal Environment Setup

virtualenv is used to manage Python packages for different projects. Using virtualenv allows you to avoid installing Python packages globally which could break system tools or other projects. You can install virtualenv using pip.

To create a virtual environment, go to your project’s directory and run venv. If you are using Python 2, replace venv with virtualenv in the below commands.

# Creating a Virtual Environment

Windows: 
  
  py -m venv env (second argument is the location to create the virtual environment. Generally, it's named env)


Linux and Mac:
  
  python3 -m venv env
  
# Activating the Virtual Environment
  
  Windows:
  
    .\env\Scripts\activate
    
  Linux and Mac:
  
    source env/bin/activate
    

If you want to leave the virtual environment, just type deactivate
 

# Running the Application 

Once you have the virtual environment setup you can run the program by running the command (python or python3) run.py
  
