# Primenumbers Technologies Assignment Using Django

## Problem statement
Design an admin-template-based Django search application that can search through the names of dishes and recommend the best match for the same.The application utilizes SQLite as its database backend, ensuring smooth and reliable data management.

## Installation 
1. Clone this repository
2. Activate virtual environment
   ```
   python -m venv venv
   source venv/bin/activate
   ```
3. Install Libraries
   ```
   pip install -r requirements.txt
   ```
4. Migrations
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```
5. Import the CSV data into the Database (if db.sqlite3 already exists then ignore this step)
   ```
   python import_csv.py
   ```
6. Run Server
   ```
   python manage.py runserver
   ```

## Screenshots

1. Search query for "Pasta" :
   ![Screenshot (563)](https://github.com/Aryan200902/Django-Dish-Search-App/assets/94388629/038b209a-455a-4236-82a7-c5336d8f1148)

   Details of the Restaurant related to this Dish :
   ![Screenshot (564)](https://github.com/Aryan200902/Django-Dish-Search-App/assets/94388629/d21e0e75-bce0-4126-a06f-02de0c1a0cc3)

2. Search Query for "Chicken" :
   ![Screenshot (565)](https://github.com/Aryan200902/Django-Dish-Search-App/assets/94388629/cf415aa7-27e1-41ea-87c2-844c546b6d50)

   Details of the Restaurant related to this Dish :
   ![Screenshot (566)](https://github.com/Aryan200902/Django-Dish-Search-App/assets/94388629/f8bfdc98-10af-4a7f-8283-d77e3aa45e2f)
