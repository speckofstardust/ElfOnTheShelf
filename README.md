# ElfOnTheShelf
A Book store inventory management application for managing a bookstore, built using Django.

## Setup Instructions

### 1. Clone the Repository: ###
  
    git clone https://github.com/speckofstardust/ElfOnTheShelf.git


### 2. Create virtual environment: ###

    python -m venv .venv

   
   **Activate on Windows:** 

    .venv\Scripts\activate

   **Activate on macOS/Linux:**

    source .venv/bin/activate

### 3. Install Dependencies: ###

    pip install -r requirements.txt

### 4. Apply Migrations: ###

    python manage.py migrate

### 5. Create Admin User: ###

    python manage.py createsuperuser

### 6. Run the Server: ###

    python manage.py runserver

Then open your browser and go to:

App: http://127.0.0.1:8000

Admin: http://127.0.0.1:8000/admin