# Graphene Cookbook

Example Application with django graphene package(Docs) with reformatting structure.

### Setup Steps

1. git clone https://github.com/kamranhossain/graphene_cookbook.git
2. cd graphene_cookbook
3. virtualenv venv
4. source venv/bin/activate
5. pip install -Ur requirments/base.txt
6. python manage.py makemigrations
7. python manage.py migrate
8. python manage.py createsuperuser
9. python manage.py runserver
10. Goto the localserver 127.0.0.1:8000/graphql
11. Writing quiries in Graphql like this: 

```graphql
query {
  allIngredients {
    id
    name
  }
}
```
