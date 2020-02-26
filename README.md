### Create virtual environment
virtualenv fvenv -p python3
source fvenv/bin/activate

### install required packages
pip install uvicorn
pip install fastapi

### run the project
uvicorn main:app --reload
