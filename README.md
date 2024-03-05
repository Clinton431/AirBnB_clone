AirBnB_clone
This is a miniture version of the Airbnb website that uses the console as the main point interaction with the User(frontend)

'frontend' - console: cmd module

'Backend' - python OOP concepts

'Database' - file storage: JSON module

'Testing' - unitest module

_ 'pycodestyle' - version 2.8.*

project structure
'''bash ├── AUTHORS ├── console.py ├── models │   ├── base_model.py │   ├── engine │   │   ├── file_storage.py │   │   └── init.py │   ├── init.py │   └── models ├── README.md └── tests

'''

'console,py' - this is the entry point of our program(where to use 'if name=="main")'

'models/' - contains all classes used for the entire project

'base_model' - This is the parent class and contains elements common to all other classes:

attributes;
  'id':
  'created_at':
  'updated_at':
methods;
  'save():'
  'to_json()':
'init()' : this is a magic method that converts our module to a package.

'engine/' - contains all storage classes

-'tests/' - Contains all our test files with the 'test_' prefix

How to use:
Examples:
