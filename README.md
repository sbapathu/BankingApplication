# Banking API

This is a Banking rest api which we can execute apis through swagger.

## How to Run api
1. Open a Terminal, and clone the current repository.
    ```
    git clone https://github.com/sbapathu/BankingApplication
    ```
2. Enter the root directory.
    ```
    cd BankingApplication
    ```
3. create virtual env  , activate venv and install python packages
	virtualenv -m venv
	pip install -r requirements.txt
	
5. Go to Banking API folder
	cd BankingAPI

3. Now start the setup by entering the following command.
    ```
    python manage.py runserver
    ```
    If that didn't work, try replacing `python` by `python3` in the above command.

4. Open url in browser "http://localhost:8000/swagger/"
5. We can see the API endpoints. 
	Please skip the apis of GET, PUT, PATCH AND DELETE OF id based retrieval/deletion/updation. Because those apis i did not work on those,  i am working on it will update in repository
