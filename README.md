# restwithflaskswagger


## Start Application Instructions

Clone the repo to your local machine by running the command:

```sh
git clone https://github.com/blackMastery/restwithflaskswagger
```

You must have python installed in your machine. The code presented will run in python3. If you want to use python2 and/or are following this procedure in a Windows machine please refer to the instructions presented in the [Flask installation guide](https://flask.palletsprojects.com/en/1.1.x/installation/)

After that, go into the folder with the project and create a virtual environment with the following command:

```sh
python3 -m venv venv
```

Active the the respective environment by running:

```sh
. venv/bin/activate
```

**Note:** It might be important to specify the environment you are considering when running this code in your IDE.

Install the project's dependencies with the following command. This will consider the packages detailed in the requirements.txt file. This is done using [pip]
(https://pypi.org/) (Python package installer):

```sh
pip install -r requirements.txt
````

Before running the application set the Flask environment variables:

```sh
export FLASK_APP=main.py
export FLASK_ENV=development
```

Run Flask... RUN!!

```sh
flask run
```