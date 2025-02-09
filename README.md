# URL Shortener

This project is a URL Shortener built using Django and Django Rest Framework (DRF). It also includes embedded HTML, CSS, and JavaScript for the frontend. Follow the steps below to set up and run the application.

## Installation and Setup

### Step 1: Navigate to the Project Directory
```sh
cd src/urlshortner
```

### Step 2: Create a Virtual Environment
```sh
python -m venv venv
```

### Step 3: Activate the Virtual Environment
- On Windows:
  ```sh
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```sh
  source venv/bin/activate
  ```

### Step 4: Install Dependencies
```sh
pip install -r requirements.txt
```

### Step 5: Apply Migrations
```sh
cd urlshortner/src/main/
python manage.py makemigrations
python manage.py migrate
```

### Step 6: Run the Server
```sh
cd ../
cd urlshortner
python manage.py runserver
```

### Step 7: Open the Application in Browser
Open the following URL in your web browser:
```
http://127.0.0.1:8000/
```

Your URL shortener should now be running successfully!

