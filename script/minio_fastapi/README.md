# Create virtual env, then active it
python3 -m venv venv
source venv/bin/activate

# Freezing dependencies to requirements file
pip freeze > requirements.txt

# Using requirements file
pip install -r requirements.txt