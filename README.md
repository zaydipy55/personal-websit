# Personal Portfolio Website

A modern, responsive personal portfolio website built with Django, featuring a dark theme and minimalist design.

## Features

- Responsive design with Bootstrap 5
- Dark theme with glass morphism effects
- Contact form with email functionality
- Project showcase section
- Skills and technologies display
- Social media integration

## Technologies Used

- Django 5.0.7
- Python 3.x
- Bootstrap 5
- HTML5/CSS3
- JavaScript

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/zaydipy55/personal-website.git
cd personal-website
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Start the development server:
```bash
python manage.py runserver
```

## Configuration

To enable email functionality, update the following settings in `personal_website/settings.py`:

```python
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = 'your-email@gmail.com'
EMAIL_HOST_PASSWORD = 'your-app-specific-password'
```

## Project Structure

- `main/` - Main Django app containing views and forms
- `templates/` - HTML templates
- `static/` - Static files (CSS, JS, images)
- `personal_website/` - Project settings and configuration

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- GitHub: [@zaydipy55](https://github.com/zaydipy55)
- Email: zaydipy555@gmail.com 