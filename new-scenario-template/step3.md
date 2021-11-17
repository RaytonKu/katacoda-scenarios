# Test Menu API

To run the test, we need to install pytest & redis, Execute

`python3 -m pip install pytest`{{execute}}

`python3 -m pip install redis`{{execute}}

After installed the pytest, Execute

`python3 -m pytest -v test_menu.py`{{execute}}

# Services
1.Get Menu `GET` /restaurant/{restaurant_id}/menu

2. Upload Menu `PUT` /restaurant/{restaurant_id}/menu

3. Update item `POST` /restaurant/{restaurant_id}/menu/items
