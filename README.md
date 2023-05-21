# Django Angular Boilerplate
The Django-Angular Boilerplate is a starting point for building web applications that combine the Django backend framework with a Angular frontend where Angular app is being served by Django

## Requirements
- Python 3.7+
- Node.js (version 12 or higher)
- npm (Node Package Manager) or Yarn
- Angular v10

## Installation

### Backend
- Clone the repository and navigate to the project directory
  ```
  git clone https://github.com/madhvi-n/django-angular-boilerplate.git
  cd django-angular-boilerplate
  ```

- Create an environment and activate it
  ```
  virtualenv venv --python=python3
  source venv/bin/activate
  ```

- Install Python dependencies
  ```
  pip install -r requirements.txt
  ```

- Run database migrations and start the development server
  ```
  python manage.py migrate
  python manage.py runserver
  ```

### Frontend
- Navigate to the `static/frontend` directory:
  ```
  cd static/frontend/project
  ```

- Install frontend dependencies
  ```
  npm install
  ```
  or
  ```
  yarn install
  ```

- Build the angular app
  ```
  npm run build
  ```
  or
  ```
  yarn build
  ```

- Open your browser and visit `http://localhost:8000` to see the application.

### Project Structure
- The Django backend code is located in the root directory.
- The Angular frontend code is located in the `static/frontend` directory.


### Configuration
- Django settings can be found in the project/settings.py file.
- Angular configuration can be found in the static/frontend/project/package.json file.
