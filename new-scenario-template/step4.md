# Test Booking API

To run the test, we need to install pytest & redis, Execute

`python3 -m pip install pytest`{{execute}}

`python3 -m pip install redis`{{execute}}

After installed the pytest, Execute

`python3 -m pytest -v test_booking.py`{{execute}}

# Services
1. Get Booking Details `GET` /booking/{booking_id}

2. Get Active Created Booking `GET` /restaurant/{restaurant_id}/created-bookings

3. Get Get Latest Canceled Booking `GET` /restaurant/{restaurant_id}/canceled-bookings

4. Accept Booking `POST` /booking/{booking_id}/accept_pos_bookings

5. Deny Booking `POST` /booking/{booking_id}/deny_pos_bookings

6. Cancel Booking `POST` /booking/{booking_id}/cancel
