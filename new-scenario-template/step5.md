# Test Customer API

To run the test, we need to install pytest & redis, Execute

`python3 -m pip install pytest`{{execute}}

`python3 -m pip install redis`{{execute}}

After installed the pytest, Execute

`python3 -m pytest -v test_customer.py`{{execute}}

# Services
1. Get Customer Details `GET` /eats/customers/{customer_id}

2. Get Customer Status `GET` /eats/customers/{customer_id}/status

3. Set Customer Status `POST` /eats/customers/{customer_id}/status
