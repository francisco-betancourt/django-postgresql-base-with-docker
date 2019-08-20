# Django REST base project

## Local dev
For local development start by cloning the repository into a local folder. After that you must create a virtual environment with pipenv. If you're using Linux (and you should) start by installing python 3, pip and postgresql dependencies with the command:

```
sudo apt install python3 python3-pip libpq
```

Then to install pipenv run the command:

 ```
 sudo -H pip3 install pipenv
 ```

Change to the cloned repository directory and then to create the virtual env then use:

```
pipenv install
```

Then to activate the recently created virtualenv just run
```
pipenv shell
```

Remember pipenv is associated with folder in which you first install the environment, so in order to use the same virtual environment again just change to the project directory and run the shell command again.

Once the virtualenvironment is created you can proceed to start the dependencies by running:

```
pipenv install -r api/requirements.txt
```




 