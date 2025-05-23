# E-commerce Auction Site with real time bid validation

A Django-based auction platform where users can create, bid on, and manage listings. This project was developed as part of CS50W (Web Programming with Python and JavaScript).

## Features

- User Authentication (Register, Login, Logout)
- Create, Edit, and Delete Listings
- Place Bids on Active Listings
- Add/Remove Listings to/from Watchlist
- Comment on Listings
- Close Auctions (Winning Bid)
- Category-based Listing Organization
- Responsive Design

## Technologies Used

- Python 3.x
- Django 4.x
- SQLite3
- HTML5
- CSS3
- Bootstrap

## Prerequisites

- Python 3.x
- pip (Python package installer)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ADDIS0NI/E-commerce-Auction-site.git
cd E-commerce-Auction-site
```

2. Create a virtual environment:
```bash
python -m venv venv
```

3. Activate the virtual environment:
- Windows:
```bash
venv\Scripts\activate
```
- Unix/MacOS:
```bash
source venv/bin/activate
```

4. Install dependencies:
```bash
pip install -r requirements.txt
```

5. Run migrations:
```bash
python manage.py migrate
```

6. Create a superuser (admin):
```bash
python manage.py createsuperuser
```

7. Run the development server:
```bash
python manage.py runserver
```

8. Visit `http://127.0.0.1:8000` in your browser

## Project Structure

```
E-commerce-Auction-site/
├── auctions/                 # Main app directory
│   ├── migrations/          # Database migrations
│   ├── static/              # Static files (CSS, images)
│   ├── templates/           # HTML templates
│   ├── models.py           # Database models
│   ├── views.py            # View functions
│   └── urls.py             # URL configurations
├── commerce/                # Project settings directory
│   ├── settings.py         # Project settings
│   ├── urls.py             # Main URL configuration
│   └── wsgi.py             # WSGI configuration
└── manage.py               # Django management script
```

## Key Features Implementation

### User Authentication
- Secure user registration and login system
- User-specific watchlists and bids

### Listing Management
- Create new listings with title, description, starting bid, and image
- Edit and delete own listings
- View all active listings

### Bidding System
- Place bids on active listings
- Automatic bid validation
- Winning bid tracking

### Watchlist
- Add/remove listings to/from watchlist
- View watchlist items

### Categories
- Browse listings by categories
- Create new categories

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the MIT License.

## Author

ADDIS0NI

## Acknowledgments

- CS50W Course Staff
- Django Documentation
- Bootstrap Documentation 
