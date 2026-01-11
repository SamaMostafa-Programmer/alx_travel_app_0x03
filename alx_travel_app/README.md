# ALX Travel App - Background Tasks with Celery

## Setup

1. Install RabbitMQ
2. Install dependencies:
   pip install celery django
3. Run migrations:
   python manage.py migrate
4. Start Django server:
   python manage.py runserver
5. Start Celery worker:
   celery -A alx_travel_app worker -l info

## Testing

- Create a booking using the API
- Check console output for booking confirmation email
