# python cli template

Documentation: `https://c17hawke.github.io/<repo-name>/<add project board link if any>`

## STEPS - 

### STEP 01: Create new repository using this template 

by choosing this as a project template while creating a new repository

### STEP 02: Clone the new repository or use codespaces

- To clone you can use the following command - 
    ```bash
    git clone https://github.com/c17hawke/<repo-name>
    ```
    NOTE: update the repo-name here

- Click on create code spaces or select available codespaces.

### STEP 03: IMPORTANT: Create `.env` file in the root of the project and paste the following content - 

```ini
# update the following values as per your project
PROJECT_NAME=<PROJECT_NAME>
REPO_NAME=<REPO_NAME>
AUTHOR_USER_NAME=<AUTHOR_USER_NAME>
AUTHOR_NAME=<AUTHOR_NAME>
PACKAGE_NAME=<PACKAGE_NAME>
AUTHOR_EMAIL=<AUTHOR_EMAIL>
COMMAND_NAME=${PACKAGE_NAME} # update as per your need, Here it is assumed that command name is package name
SITE_AUTHOR=${AUTHOR_USER_NAME} # update as per your need, Here it is assumed that site author is author user name
GITHUB_USER_NAME=${AUTHOR_USER_NAME} # update as per your need, Here it is assumed that github user name is author user name
PYTHON_VERSION=<PYTHON_VERSION>  
YEAR=<YEAR>
```

> **WARNING: if this step is skipped then exception will be raised**


### STEP 04: Run the template.py file

> NOTE: make sure you have dotenv installed before running the following command. To install it simply run the following command - 
> ```bash
> pip install python-dotenv
> ```


use template.py to create the other required files by running the following command - 

```bash 
python template.py
```

### STEP 05: Add a `LICENSE` file

- Go to your github repository and click on `Add file` and then select `Create new file`.
- Now start typing the name of the file as `LICENSE` and then you'll see the option of selecting the desired template. 

NOTE: You can choose MIT License if you are not sure.

> This completes the basic skeleton of the project!!

### STEP 06: Create and install dependencies - 

- It is assumed that `anaconda` or `miniconda` is intalled in the system. If not then please do your setup by following this tutorial - https://youtu.be/bVM-QujJ0AI

- Update the `requirements_dev.txt` and `requirements.txt` files with the project requirements (i.e. required libraries)
- Now run the `init_setup.sh` file by running the following command - 
    ```bash
    bash init_setup.sh   
    ```
NOTE: if in case you face difficulty in running the init_setup.sh file then you can run the command mentioned in it one by one in the terminal to get the same result.

> This completes the environment setup of the project!!

> Now you can start the development!!!