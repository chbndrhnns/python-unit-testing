# python-unit-testing

Training repository for getting started with unit testing in Python.

## Scenario

We have a simple calculator library that allows to

- read a number from the file `test_number.txt`
- add 3 to the number found in the text file
- multiply the number from the text file with a given factor.

## How-To

### Access dummy REST API

- Use `<http://faker.hook.io?property=random.number>`

### Run the tests

- `pytest tests/`

### See test coverage report in browser

- Run `pytest --cov-report=html`
- Go to `htmlcov` folder
- Open `index.html` in your browser

### Get more information on mocking

- There are some shortcuts when using `pytest`: <https://pypi.org/project/pytest-mock/>
- <https://santexgroup.com/wp-content/uploads/2014/10/mock_python.html>
