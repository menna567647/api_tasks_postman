# Backend Training Projects – MediLink & Mo7amer

This repository contains API endpoints developed during my **Backend Developer Training**.  
The screenshots demonstrate the implemented APIs and their responses using **Postman**.

---

## MediLink – Doctor Booking System

### Overview
MediLink is a doctor booking system that provides APIs for managing doctors, specialties, appointment slots, and patient bookings.  
The system allows patients to browse doctors, view available appointment times, and book appointments easily.

### Training Experience
This project was developed during backend training.

### Responsibilities
- Developed RESTful APIs for the doctor booking workflow.
- Implemented appointment management:
  - Book appointment
  - Confirm appointment
  - Cancel appointment
- Built APIs for:
  - Doctor profiles
  - Specialties
  - Appointment slots
- Developed user settings APIs (personal information, language, privacy settings).
- Implemented notifications APIs.
- Created database **seeders and factories** to generate sample data.
- Wrote **unit tests** to verify API functionality.
- Used **Git/GitHub** for version control and collaboration.

### Technologies
Laravel, MySQL, REST API, Laravel Sanctum, Carbon, PHPUnit, Git/GitHub

---

## Mo7amer – Restaurant Management API

### Overview
Mo7amer is a restaurant management system that provides APIs for displaying food items, offers, and categories, as well as managing the customer cart, checkout process, and online payments using Stripe.

### Training Experience
This project was developed during backend training at **MediLink & Mo7amer**.

### Responsibilities
- Developed APIs for home page data including:
  - Offers
  - Food sections
  - Most requested meals
- Implemented cart management APIs:
  - Add to cart
  - Edit cart items
  - Remove items from cart
- Built checkout and payment APIs with **Stripe integration**.
- Used **Git/GitHub** for version control and teamwork.

### Technologies
Laravel, MySQL, REST API, Stripe Payment Gateway, Git/GitHub

---

## API Demonstration
The repository includes **Postman screenshots** demonstrating the implemented API endpoints and their responses.

#### MediLink – Doctor Booking
show doctors schedules based on booking type
![doctors_schedules](MediLink/booking/doctors_schedules.png)
show available slots
![doctor_available_slots](MediLink/booking/doctor_available_slots.png)
booking process
![book an appointment](MediLink/booking/booking_appointment_other.png)
![book an appointment](MediLink/booking/booking_appointment_myself.png)
confirm booking
![confirm_appointment](MediLink/booking/confirm_appointment.png)
cancel booking
![cancel_appointment](MediLink/booking/cancel_appointment.png)

show patient appointments
![patient_appointments](MediLink/booking/patient_appointments.png)

request withdrawals
![request_withdrawal](MediLink/doctor/request_withdrawal.png)
doctor withdrawals
![doctor withdrawals](MediLink/doctor/doctor_withdrawals.png)

Notifications
![user notifications](MediLink/notifications/user_notifications.png)
mark as read
![mark_as_read](MediLink/notifications/mark_as_read.png)

show patient profile
![patient_profile](MediLink/patient/patient_profile.png)

delete profile
![delete_profile](MediLink/settings/delete_profile.png)

show languages
![languages](MediLink/settings/languages.png)

settings
![privacy$policy](MediLink/settings/settings_privacy$policy.png)

Specialties
![Specialties](MediLink/specialties.png)

#### Mo7amer – Restaurant Management

cart
![cart](Mo7amer/cart/cart.png)
add to cart
![add_to_cart](Mo7amer/cart/add_to_cart.png)
remove item from cart
![remove_item_from_cart](Mo7amer/cart/remove_item_from_cart.png)
edit cart item
![edit_cart_item](Mo7amer/cart/edit_cart_item.png)
![edit_cart_item_addon](Mo7amer/cart/edit_cart_item_addon.png)

home page
most requested meals
![most_requested_meals](Mo7amer/home/most_requested_meals.png)
food sections
![food_sections](Mo7amer/home/food_sections.png)
customer offer for first meal
![customer offers](Mo7amer/home/customer_offers.png)

payment
checkout url
![checkout](Mo7amer/payment/checkout.png)
![stripe checkout](Mo7amer/payment/stripe.png)
![payment successful](Mo7amer/payment/payment_successful.png)

cancel order
![cancel order](Mo7amer/payment/cancel_order.png)
