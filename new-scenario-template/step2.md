# Test Restaurant API

To run the test, we need to install pytest & redis, Execute

`python3 -m pip install pytest`{{execute}}

`python3 -m pip install redis`{{execute}}

After installed the pytest, Execute

`python3 -m pytest -v test_restaurant.py`{{execute}}

# Services
1. List All Store `GET` /restaurant

2. Get Restaurant Details `GET` /restaurant/{restaurant_id}

3. Get Restaurant Holiday Hours `GET` /restaurant/{restaurant_id}/holiday-hours

4. Set Restaurant Holiday Hours `POST` /restaurant/{restaurant_id}/setHoliday-hours
