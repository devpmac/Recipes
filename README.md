# Recipes

Code for a simple web page to store recipes.

### Virtual Environment Installation

Linux | Windows |
--- | --- |
<td colspan=2> git clone https://github.com/devpmac/Recipes.git |
<td colspan=2> cd Recipes |
python3 -m venv env | python -m venv env |
source env/bin/activate | \env\Scripts\activate.bat |
<td colspan=2> pip install -r requirements.txt |


### Start Django server

Setup |
--- |
mkdir src_django |
django-admin startproject recipes src_django |
python src_django/manage.py migrate |
python src_django/manage.py runserver |
