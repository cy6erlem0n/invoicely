# Invoicely

💸 Simple invoicing app built with Django + Vue.js

## 🔧 Stack

- Django + DRF
- Djoser + Token Auth
- Vue 3 + Vuex + Vue Router
- Bulma

## 🚀 How to run

### Backend

```bash
cd invoicely
python -m venv venv
source venv/bin/activate # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
### Frontend

```bash
cd invoicely_vue
npm install
npm run serve
```