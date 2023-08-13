# Deliverable: Virtual environments

Instructor: Carlos Mejia
Student: Gabriela Sánchez

Virtual environments allow the isolated execution of a project given certain conditions, generally libraries or packages with certain versions.

This deliverable consists of two things:
1. Instructions for installing a virtual environment (Windows and Linux) described in a README.md file.

    - Let's remember the steps to create virtual environments:
        1. Have the necessary software installed (python, github...)
        2. In the console or in the terminal, enter the path of the project.
        
        Example: C:\Users\gcsanchez\Documents\GitHub\mlops_mod3-2>
        
        3. Write the following line of code to create the environment with python version 10:

        py -3.10 -m venv venv310
        
        4. Then let's write the following line of code to activate the environment:

        venv310\scripts\activate.bat

        5. Let's install the file with the package requirements and versions to be used in the virtual environment:

        pip install -r requirements-venv.txt

        6. Let's verify that our environment was created in VS CODE.
        7. Let's select our kernel to run the notebooks in the virtual environment created.

2. Requirements.txt file with the packages and versions.

    - The file is called requirements-venv.txt and it is the one that will be used to load the packages and versions with which the virtual environment will work.