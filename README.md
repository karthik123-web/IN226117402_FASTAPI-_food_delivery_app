# FastAPI Food Delivery App

This project is developed as part of my FastAPI internship final assignment. It is a backend application that simulates a basic food delivery system with menu management, cart operations, and order processing.

## Project Overview

The application allows users to:
- View available food items
- Add new items to the menu
- Update and delete items
- Add items to a cart
- Place orders
- Search, sort, and paginate data

All APIs are built using FastAPI and tested through Swagger UI.

## Features

### 1. Menu Management
- Get all menu items
- Get item by ID
- View available items
- Summary of items
- Add new items with validation
- Update item details
- Delete items with conditions

### 2. Cart System
- Add items to cart
- View cart
- Calculate total price
- Checkout functionality

### 3. Orders
- Place orders from cart
- Store order history
- View all orders

### 4. Advanced Functionalities
- Search items (case-insensitive)
- Sort items by price or name
- Pagination support
- Combined browsing (search + sort + pagination)

## Technologies Used
- Python
- FastAPI
- Pydantic
- Uvicorn

## How to Run

1. Install dependencies:
pip install -r requirements

# 2. Run the server
uvicorn main:app --reload