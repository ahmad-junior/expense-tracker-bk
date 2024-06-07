# Expense Tracker

This a expense tracker APIs which is used to track the expenses of the user.

## Setup
1. Clone the repository

```git clone https://github.com/ahmad-junior/expense-tracker-bk.git```

2. Install Poetry

```pip install poetry``` or ```pip3 install poetry```

> Note: If you already have poetry installed, you can skip this step.

3. Make a virtual environment

```python3 -m venv env```

4. Activate the virtual environment

```source env/bin/activate``` (Linux)

```env\Scripts\activate``` (Windows)

5. Install dependencies

```poetry install --no-root```

6. Migration

```python manage.py migrate```

7. Run the server

```python manage.py runserver```

## Pre-commit
This project uses pre-commit to enforce some code style. To install pre-commit, run the following command:

```pre-commit install```

> Note: You should run this command after cloning the repository and before making any changes to the code. Most import thing is that never forget to run this command in side the cloned repository.
