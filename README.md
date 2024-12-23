# Simple-Portfolio-Tracker-CAPX
This code sets up a Flask-based web application for a simple portfolio tracker. The application allows users to manage their stock holdings, calculate the total portfolio value based on real-time stock prices (using Yahoo Finance), and view key metrics.

Features Implemented:
Add/View/Edit/Delete Stock Holdings:

RESTful endpoints (POST, GET, PUT, DELETE) for portfolio management.
Track Total Portfolio Value:

Endpoint /api/portfolio/value fetches live stock prices and calculates the total value.
Dashboard with Key Metrics:

Endpoint /api/portfolio/metrics provides:
Total portfolio value.
Top-performing stock.
Portfolio distribution.


# Frontend: React Application
1. Setup
Use create-react-app to initialize a React project:

# App Structure
Components: Dashboard, StockForm, StockList.
Routing: Use react-router-dom for navigation
