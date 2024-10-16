# CS284A

CS284A Fall 2024

## pipenv

- You can install pipenv with `pip install pipenv`
- to start an environment run `pipenv shell`
- to install packages run `pipenv install <package_name>`
- - this will add the package to the Pipfile
- to install all packages in the Pipfile run `pipenv install`
- you can activate the environment with `pipenv shell`
- - once the environment is activated, you can run code using the installed packages
- - without the environment activated, you can still run code using the packages in the Pipfile with `pipenv run ...`
- - example: `pipenv run jupyter notebook`
- - example: `pipenv run python code.py`
