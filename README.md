# Recipes

Code for a simple web page to store recipes.

### Virtual Environment Installation

`
git clone https://github.com/devpmac/Recipes.git && cd Recipes
`

| Linux | Windows |
| --- | --- |
| `python -m venv env` | `python -m venv env` |
| `source env/bin/activate` | `\env\Scripts\activate.bat` |

`pip install -r requirements.txt`


### Start Django server

| Setup |
| --- |
| `mkdir src_django` |
| `django-admin startproject recipes src_django` |
| `python src_django/manage.py migrate` |
| `python src_django/manage.py runserver` |
