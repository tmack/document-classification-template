# Document Classification Template
A template for Document Classification using Deep Learning. Inspired by: https://medium.com/analytics-vidhya/how-i-built-a-document-classification-system-using-deep-convolutional-neural-networks-e1d9a83cbabd

## Installing Requirements
```bash
$ pip install -r requirements.txt
```

## Setting up configs
Create the json file 'test-local.settings.json', this is a place to put project settings you'd like to use. Each key/value pair is set as environmental variable during run time.
```json
{
"env_variable_name" : "env_variable_value"
}
```

## Running Tests
To run tests use the following command. 
```bash
 python -m unittest discover -s tests -p 'test_*.py'
```
Tests can also be configured to run from an IDE. See tests/example_of_pycharm_test_configurations.png for an example from pycharm

### Example Testing Output
Here's what testing should look like when its up and running

 ```bash
$ python -m unittest discover -s tests -p 'test_*.py'
............
----------------------------------------------------------------------
Ran 1 tests in 0.001s

OK
```

