# Recipes

Code for a simple web page to store recipes.

### Virtual Environment Installation

Linux |
--- |
git clone https://github.com/devpmac/Recipes.git |
cd learn |
python3 -m venv env |
source env/bin/activate |
pip install -r requirements.txt |


### Start Django server

Linux |
--- |
mkdir src_django |
django-admin startproject recipes src_django |
python src_django/manage.py migrate |
python src_django/manage.py runserver |
