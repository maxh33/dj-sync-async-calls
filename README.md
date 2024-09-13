**Description:** A Django project demonstrating the use of asynchronous and synchronous views. This project includes examples of making HTTP requests using both async and sync methods, showcasing how to handle non-blocking and blocking HTTP requests in Django.

**Features:**

* Asynchronous HTTP requests using httpx and asyncio
* Synchronous HTTP requests using httpx
* Example views to demonstrate non-blocking and blocking behavior
* Basic project structure with necessary configurations

**Getting Started:**

1. Clone the repository:
```bash
git clone <https://github.com/maxh33/dj-sync-async-calls>
cd async-views
```
2. Set up a virtual environment and install dependencies:
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install -r requirements.txt
```
3. Run the Django development server:
```bash
python manage.py runserver
```
4. Access the views:

* Asynchronous view: http://127.0.0.1:8000/api/
* Synchronous view: http://127.0.0.1:8000/sync/

**Requirements:**

* Python 3.x
* Django
* httpx
* celery