# Contribute to BlogHub

## Steps to perform

+ Fork this repository
+ Clone the repository
  ```
  git clone git@github.com:[YOUR USERNAME]/bloghub.git
  ```
+ On the root of project create `.env` file, refer to [this](../.env.example) for creating `.env`.
+ For `SECRET_KEY`, get one from [here](https://djecrety.ir/)
+ Create python virtual env and activate
  ```
  python3 -m venv venv && source venv/bin/activate
  ```
+ Install dependencies
  ```
  pip install -r requirements.txt
  ```
+ Migrate DB
  ```
  python manage.py migrate
  ```
+ Collect the static files
  ```
  python manage.py collectstatic
  ```
+ To run the development server
  ```
  python manage.py runserver
  ```
