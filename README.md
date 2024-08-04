# my-first-project
This is a simple flask hosted static website as my first intro to flask
# Restaurant Website

This is a simple web application built using Flask for a restaurant. The website provides information about the restaurant's services, menu, user reviews, and includes a user login system.

## Features

- **Home Page:** A welcoming page with navigation links to other sections of the site.
- **Services:** Information about the different services offered by the restaurant.
- **Menu:** A detailed view of the restaurant's menu items.
- **User Reviews:** A section showcasing reviews from customers.
- **About Us:** Information about the restaurant's history, mission, and team.
- **Login:** A user login system for accessing personalized features.

## Project Structure
RestaurantWebsite/
├── app/
│ ├── init.py
│ ├── forms/
│ │ ├── user_forms.py
│ │ └── init.py
│ ├── models/
│ │ ├── user.py
│ │ └── init.py
│ ├── routes/
│ │ ├── home_routes.py
│ │ ├── init.py
│ │ └── pycache/
│ ├── static/
│ │ ├── css/
│ │ │ ├── index.css
│ │ │ ├── login.css
│ │ │ └── styles.css
│ │ ├── img/
│ │ │ ├── aboutbg.jpg
│ │ │ ├── bg1.jpg
│ │ │ ├── bg1_c.jpg
│ │ │ ├── bg2.jpg
│ │ │ ├── delivery.png
│ │ │ ├── food.png
│ │ │ ├── image.jpg
│ │ │ ├── logo.png
│ │ │ ├── menubg.jpg
│ │ │ ├── party.png
│ │ │ └── servicesbg.jpg
│ │ ├── js/
│ │ │ ├── jquery.min.js
│ │ │ ├── login.js
│ │ │ ├── menu.js
│ │ │ ├── menu1.js
│ │ │ ├── reviews.js
│ │ │ └── script.js
│ ├── templates/
│ │ ├── aboutus.html
│ │ ├── home.html
│ │ ├── login.html
│ │ ├── menu.html
│ │ ├── reviews.html
│ │ └── services.html
│ └── pycache/
│ └── init.cpython-312.pyc
├── config.py
├── requirements.txt
├── run.py
└── tests/
├── test_models.py
├── test_routes.py
└── init.py

## Getting Started

### Prerequisites

- Python 3.x
- Flask

### Installation

1. **Clone the repository:**
git clone https://github.com/Gdivyabharathi/sample_restaurants_flask_app.git
cd restaurant-website

2. **Create and activate a virtual environment:**

python -m venv venv
source venv/bin/activate # On Windows use venv\Scripts\activate

3. **Install dependencies:**
pip install -r requirements.txt

5. **Open the application in your browser:**

python run.py
wait for browser to open or open browser and type localhost:5000



