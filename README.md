python3 manage.py runserver
python3 manage.py startapp todo
python3 manage.py makemigrations --dry-run
python3 manage.py showmigrations
python3 manage.py migrate --plan
python3 manage.py migrate 
python3 manage.py createsuperuser

-- testing
. = Pass
F = Fail
E = Error

python3 manage.py test # run all test files
python3 manage.py test [file path e.g todo.test_forms] # run specific test file
python3 manage.py test [file path].test[classname] # run specific test class
python3 manage.py test [file path].test[class]name of def to run] #run specific test from file