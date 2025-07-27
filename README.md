# 🚀 AIML-Hackathon
The AIML-Hackathon project is a comprehensive supply chain management system built using Django, a high-level Python web framework. The system aims to streamline the interaction between manufacturers and suppliers, facilitating a more efficient and transparent procurement process.

## 📝 Description
The project consists of multiple modules, including manufacturer and supplier registration, quote requests, bidding, and negotiation. It also features a carbon footprint calculator to help companies make more environmentally conscious decisions. The system is designed to be user-friendly, with a simple and intuitive interface for both manufacturers and suppliers.

The project uses a range of technologies, including Python, Django, and various libraries such as geopy and openroute. The carbon footprint calculator utilizes the OpenRoute API to estimate emissions based on route distance and vehicle type. The system also includes email notification functionality to keep users informed of important events, such as new quote requests or bid submissions.

## 🚀 Features
* Manufacturer and supplier registration
* Quote requests and bidding system
* Negotiation module for price and delivery discussions
* Carbon footprint calculator for environmentally conscious decisions
* Email notification system for important events
* User-friendly interface for easy navigation

## 📊 Installation Instructions
To get started with the AIML-Hackathon project, follow these steps:
1. Clone the repository: `git clone https://github.com/inevitablegs/AIML-Hackathon`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the migrations: `python manage.py migrate`
4. Start the development server: `python manage.py runserver`

## 📝 Usage
To use the system, simply navigate to the URL displayed in the terminal after starting the development server. You can register as a manufacturer or supplier, and then use the various features of the system to manage your procurement process.

```python
# Example usage:
from manufacturer.models import Manufacturer
from supplier.models import Supplier

# Create a new manufacturer
manufacturer = Manufacturer.objects.create(
    company_name="Example Manufacturer",
    city="New York",
    state="NY",
    business_type="Electronics"
)

# Create a new supplier
supplier = Supplier.objects.create(
    company_name="Example Supplier",
    city="Los Angeles",
    state="CA",
    business_type="Logistics"
)
```

## 📊 Configuration
The system uses various configuration settings, such as API keys and email server settings. These can be found in the `settings.py` file.

## 📊 Technologies
| Technology | Description |
| --- | --- |
| Python | High-level programming language |
| Django | High-level web framework |
| geopy | Library for geocoding and distance calculations |
| openroute | API for route distance and emissions calculations |
| Email | Library for sending email notifications |

## 🤖 Technologies Explanation
The system uses a range of technologies to provide a comprehensive supply chain management solution. Python is used as the primary programming language, with Django providing a high-level web framework for building the application. geopy and openroute are used for geocoding and distance calculations, while Email is used for sending notifications.

## 📸 Screenshots
[Placeholder for screenshots]

## 🤝 Contributing Guidelines
To contribute to the AIML-Hackathon project, please follow these guidelines:
1. Fork the repository
2. Make your changes and commit them
3. Create a pull request with a clear description of your changes
4. Wait for review and approval before merging your changes

Note: This is a basic example, please make sure to add more details and follow the instructions carefully.
