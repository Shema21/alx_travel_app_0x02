﻿#  ALX Travel App 0x01

This project is an API for managing travel listings and bookings using Django and Django REST Framework. It builds upon `alx_travel_app_0x00`, adding full CRUD operations and Swagger documentation for easier API exploration.

---

## 📌 Objective

- Build API views using DRF's `ModelViewSet`.
- Manage `Listing` and `Booking` resources through RESTful endpoints.
- Document the API with Swagger.
- Enable clients (like Postman) to test GET, POST, PUT, DELETE operations.

---

## 🛠️ Technologies Used

- Python 3.9+
- Django 4.x
- Django REST Framework
- drf-yasg (for Swagger/OpenAPI documentation)

---


### ✨ Documented Endpoints:

#### 📌 Listings
- `GET /api/listings/`: List all listings
- `POST /api/listings/`: Create a new listing
- `GET /api/listings/{id}/`: Retrieve a listing
- `PUT /api/listings/{id}/`: Update a listing
- `DELETE /api/listings/{id}/`: Delete a listing

#### 📌 Bookings
- `GET /api/bookings/`: List all bookings
- `POST /api/bookings/`: Create a booking
- `GET /api/bookings/{id}/`: Retrieve a booking
- `PUT /api/bookings/{id}/`: Update a booking
- `DELETE /api/bookings/{id}/`: Delete a booking
