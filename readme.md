**tutorial:** https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react - note there are a few bugs in the tutorial which I've patched up here. 

**setup:** 

- do a `yarn install` in `/frontend` 

- `pip` or `pipenv` `install djangorestframework django-cors-headers` depending on whether you're using pipenv.

**run:** `python backend/manage.py runserver & yarn --cwd frontend start`
