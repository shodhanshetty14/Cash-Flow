## Cash-Flow

### Local Setup

- `git clone https://github.com/shodhanshetty14/Cash-Flow.git`

- Create Virtual Environment `virtualenv venv`

- Activate Virtual Environment 
    - Windows - `venv/Scripts/activate`
    - Linux - `source venv/bin/activate`

- Install Dependencies `pip install -r requirements.txt`


- Make Migratations `python manage.py makemigrations`

- Run Migratations `python manage.py migrate`

### For Creataing Super User( if required)
- Create Super User `python manage.py createsuperuser`
    - Enter Username and Password and Create Super User

- Start Server `python manage.py runserver`


## API Documentation
- `http://127.0.0.1:8000/`