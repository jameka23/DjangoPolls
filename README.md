# Django Polls App
This is a polls app following the django tutorial using django 2.0.5 and python 3.6.4

## Getting Started
After forking a copy of the files on your local machine you then would want to get into a virtual environment to specifically download prerequisites 

### Prerequisites
Once you are in your main directory start your virtual environment running the following command:
```
python3 -m venv myvenv
```
Note that this is for Mac
Next run the command to activate the environment. This will ensure packages wil be installed in this environment and will not affect any other sites you're working on.

```
source/bin/activate
```

You will then see the following: (myvenv).... followed by the usual terminal prompt

### Installing Django
Install pip first 

```
pip install --upgrade pip
```
Next you will want to install Django. If you already have Django, pip will automatically unistall and install a new version....only if you've used pip to install in the first place. 

```
pip install django~=2.0.5
```
You should see "Successfully downloaded django 2.0.5 

### Local Server
To run the app on your local server you should be in the main directory still and cd into the first mysite folder. Once doing that run the command
```
python manage.py runserver
```

You should then be able to see the address given which will start with '127'. Copy and paste into your browser. 
  
