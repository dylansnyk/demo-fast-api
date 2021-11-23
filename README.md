Running the API locally

### Create virtual environment

`python -m venv env`

### Activate the environment

`source ./env/bin/activate`

### Install dependencies

`pip3 install -r requirements.txt`

### Run application in develop mode

`./env/bin/uvicorn main:app --reload`