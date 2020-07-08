## Django Coding Challenge - datamindedsolutions

### Features - 

- A user can create a restaurant. (Name, foodtype, address, rating etc.)

- A user can obtain a list of restaurants.

- A user can view details of a restaurant based on the restaurant they select from the list.

- A user can edit and delete a restaurant.

- A user can submit a rating for a restaurant.

- A user can sort the list of restaurants by Highest Rating.

## Setup environment -

- Clone or Download the repository
```bash
git clone https://github.com/devanshipatel21/Noteworth.git
```
- Go to root directory
```bash
cd noteworth
```
- Create virtual environment and activate
```bash
python -m venv env

source env/bin/activate 
```

- In your python virtual env, install all dependencies

```bash
pip install -r requirements.txt
```

- After environment setup, make migrations and migrate changes

```bash
python manage.py makemigraations

python manage.py migrate
```

- Now run the server with
```bash
python manage.py runserver
```

- The server is up and running on *http://localhost:8000*

- For test cases, run in terminal
```bash
python manage.py test
```


### Available Routes - 

- http://localhost:8000/api/restaurant **POST** 

- http://localhost:8000/api/restaurants **GET** 

- http://localhost:8000/api/restaurant/:id **GET, PUT, DELETE**

- *http://localhost:8000/api/restaurant/:id/rate  **POST**