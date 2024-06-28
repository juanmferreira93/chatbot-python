# ChatBot
## Setup Environment
For a proper use of python, we should create a virtual environment (venv) to isolate the project packages from the global python configuration.
To create this venv run:
`python -m venv path/to/venv`

Then you need to activate this new venv, so for that run:
`source path/to/venv/bin/activate`

Please take a look to this little guide about how to create and activate a [venv](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments)

## Env Vars
Create an empty file `.env` in the root directory of your project.
Then look into `.env.test` to understand which ENV VARS we will need.
For now, we only use OPENAI_API_KEY, so please in the `.env` put your API_KEY for OpenAI.

## Install dependencies
To install the project dependencies `run pip install -r requirements.txt`.
This will install all the requirements for the project and all loaders requirements.

## Runing the project
Just run `streamlit run chatbot.py`