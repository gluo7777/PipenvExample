https://packaging.python.org/tutorials/managing-dependencies/

pip install --user pipenv

export PATH=$PATH:$(python -m site --user-site)

pipenv install requests

# pipenv run python main.py
pipenv run main.py

pipenv shell
python main.py