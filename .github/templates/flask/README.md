# python_project_template Flask Application

This is a Flask application.

## Installation

From source:

```bash
git clone https://github.com/mondbev1/python-project-template python_project_template
cd python_project_template
make install
```

From pypi:

```bash
pip install python_project_template
```

## Executing

This application has a CLI interface that extends the Flask CLI.

Just run:

```bash
$ python_project_template
```

or

```bash
$ python -m python_project_template
```

To see the help message and usage instructions.

## First run

```bash
python_project_template create-db   # run once
python_project_template populate-db  # run once (optional)
python_project_template add-user -u admin -p 1234  # ads a user
python_project_template run
```

Go to:

- Website: http://localhost:5000
- Admin: http://localhost:5000/admin/
  - user: admin, senha: 1234
- API GET:
  - https://localhost:5000/api/v1/product/
  - https://localhost:5000/api/v1/product/1
  - https://localhost:5000/api/v1/product/2
  - https://localhost:5000/api/v1/product/3


> **Note**: You can also use `flask run` to run the application.
