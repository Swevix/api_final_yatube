# api_final
Решения проектной задачи на реализацию REST API на django(django rest framework)

Протестировано на python 3.12

## Setup
```bash
python3.10 -m venv venv
.\venv\Scripts\activate
pip3 install -r requirements.txt
python3 yatube_api/manage.py migrate

python3 yatube_api/manage.py runserver
```

## Tests
```bash
.\venv\Scripts\activate
flake8 && pytest
```
