# RPMFanatics - Virtual Garage & Car Meet Platform

A web application built in **Go (Golang)** designed for automotive enthusiasts to showcase their vehicles, document modifications, and organize local car meets.

## Overview
RPMFanatics acts as a digital garage and community hub where users can share their car specs and build logs, discover vehicles from other members, and join upcoming automotive events.

## Planned Features
* **Authentication & RBAC:** Role-based access control for Guests, Registered Members, and Administrators using JWT authentication and `bcrypt` password hashing.
* **Virtual Garage & Tuning Log:** Full CRUD management for user vehicles and tuning logs,with ownership checks (members manage only their own content, admins can manage everything).
* **Car Meets:** Event creation and RSVP system for local meetups, with strict date/time validation, maximum capacity, organizer approval of join requests, and one RSVP (with one car) per user per event.
* **Search, Filtering & Pagination:** Dynamic filtering (by make, year, fuel type, etc.), sorting (by popularity, horsepower, or date), and paginated listings.
* **Landing Page & Seeding:** Public showcase for trending builds and upcoming meets, populated with realistic test data.

## Tech Stack
* **Backend:** Go, Gin Web Framework
* **Database & ORM:** PostgreSQL / SQLite, GORM, `golang-migrate`
* **Security:** JWT, `bcrypt`

## Status
🚧 *In development — project setup and architecture planning.*
