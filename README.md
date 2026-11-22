# Fast & Furious Cars API

A CRUD API for cars from the Fast & Furious movies, built with **FastAPI** to learn how to work with **MySQL** databases using XAMPP.

> Frontend: [fast-furious-cars-web](https://github.com/Joao-Adegas/fast-furious-cars-web)

## Tech stack

Python, FastAPI, MySQL, XAMPP

## Getting started

### Prerequisites

- [XAMPP](https://www.apachefriends.org/index.html)
- Python

### 1. Database (XAMPP)

1. Open XAMPP, click **Apache Config** and open `httpd.conf`.
2. Replace port `8000` with `8080` (use `Ctrl + F` to find it).
3. Start **Apache** and **MySQL**.
   - If MySQL starts and then stops, open the Task Manager and end all `mysql` processes.
4. Click **MySQL Admin** (phpMyAdmin) and import the file `Database/carros_velozes_e_furiosos.sql`.

### 2. Environment variables

Create a `.env` file with your database credentials. Never commit this file.

<!-- CONFIRM: names of the variables read by the API -->

### 3. Run the API

```bash
python -m venv env

# Windows
./env/Scripts/activate
# macOS / Linux
source env/bin/activate

pip install -r requirements.txt
python main.py
```

## Author

João Pedro dos Santos Adegas — [@Joao-Adegas](https://github.com/Joao-Adegas)
