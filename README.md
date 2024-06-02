# Shop

Shop is an e-commerce website built with the python based Django framework and PostgreSQL database.

## Features

- **Product catalog**
- **Shopping cart** - Django sessions
- **Asynchronous notifications** - Celery
- **Monitoring** - Flower
- **RabbitMQ** - Message broker
- **Payment gateway** - Stripe
- **Export orders** - CSV files
- **Generate PDF invoices**
- **Coupon system**
- **Product recommendation engine** - Redis
- **Internationalization** - Rosetta, django-parler, django-localflavor

## Installation

Clone the project and install the dependencies using [pip](https://pip.pypa.io/en/stable/)

```bash
git clone https://github.com/Eddy-123/shop.git
cd shop
python -m venv .shop
source .shop/bin/activate
pip install -r requirements.txt
```

## Usage

```bash
python manage.py runserver
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
