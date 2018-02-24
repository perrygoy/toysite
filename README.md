# Toy Site!
This site is just a playground for me to mess around with Django ideas.

## Setup
`$ pipenv install`
`$ pipenv run ./launch.sh`

## Apps
### Superlist
This app allows you to create collaborative lists. You can create and name
any number of lists, then invite other users by e-mail to join one of your
lists, allowing them to see or edit it themselves. Only you and the people
you invite can see your lists.

You can create shopping lists, serial number lists, movies-to-watch lists,
top-ten lists... I could even use the app to make a list of all this.

## Testing
To run all tests:
`$ pipenv run ./manage.py test`

To run a subset of tests:
```
# All of one app's tests
$ pipenv run ./manage.py test apps.appname.tests

# Specific test suite
$ pipenv run ./manage.py test apps.appname.tests.test_suite_name

# Specific test case
$ pipenv run ./manage.py test apps.appname.tests.test_suite_name.TestSuite.test_case_name
```
