# Blog API (Django REST)

# Как запустить проект

```bash
git clone <https://github.com/abdievaasani/monat_5_test.git>
cd blog_api
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## Получение токена

POST запрос на:

```
/api-token/
```



```json
{
  "username": "admin",
  "password": "123"
}
```

---

## Документация API

Swagger:

http://127.0.0.1:8000/swagger/
