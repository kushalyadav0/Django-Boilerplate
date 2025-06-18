# 🧩 Django Basic Boilerplate

A clean and minimal Django boilerplate to kickstart new projects with a structured setup for settings, apps, templates, and static files.

---

## 🚀 Features

- Modular settings (`base.py`, `dev.py`, `prod.py`)
- Structured project layout
- Pre-configured templates and static directories
- Environment variable support via `.env`
- App structure ready for scaling

---

## 📁 Project Structure

Project
├── LICENSE
├── project
│   ├── app
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── __init__.py
│   │   │   └── __pycache__
│   │   │       └── __init__.cpython-312.pyc
│   │   ├── models.py
│   │   ├── __pycache__
│   │   │   ├── admin.cpython-312.pyc
│   │   │   ├── apps.cpython-312.pyc
│   │   │   ├── __init__.cpython-312.pyc
│   │   │   ├── models.cpython-312.pyc
│   │   │   ├── urls.cpython-312.pyc
│   │   │   └── views.cpython-312.pyc
│   │   ├── tests.py
│   │   ├── urls.py
│   │   └── views.py
│   ├── db.sqlite3
│   ├── Django-Boilerplate
│   │   └── project
│   │       └── static
│   │           ├── admin
│   │           │   ├── css
│   │           │   │   ├── autocomplete.css
│   │           │   │   ├── base.css
│   │           │   │   ├── changelists.css
│   │           │   │   ├── dark_mode.css
│   │           │   │   ├── dashboard.css
│   │           │   │   ├── forms.css
│   │           │   │   ├── login.css
│   │           │   │   ├── nav_sidebar.css
│   │           │   │   ├── responsive.css
│   │           │   │   ├── responsive_rtl.css
│   │           │   │   ├── rtl.css
│   │           │   │   ├── unusable_password_field.css
│   │           │   │   ├── vendor
│   │           │   │   │   └── select2
│   │           │   │   │       ├── LICENSE-SELECT2.md
│   │           │   │   │       ├── select2.css
│   │           │   │   │       └── select2.min.css
│   │           │   │   └── widgets.css
│   │           │   ├── img
│   │           │   │   ├── calendar-icons.svg
│   │           │   │   ├── gis
│   │           │   │   │   ├── move_vertex_off.svg
│   │           │   │   │   └── move_vertex_on.svg
│   │           │   │   ├── icon-addlink.svg
│   │           │   │   ├── icon-alert.svg
│   │           │   │   ├── icon-calendar.svg
│   │           │   │   ├── icon-changelink.svg
│   │           │   │   ├── icon-clock.svg
│   │           │   │   ├── icon-deletelink.svg
│   │           │   │   ├── icon-hidelink.svg
│   │           │   │   ├── icon-no.svg
│   │           │   │   ├── icon-unknown-alt.svg
│   │           │   │   ├── icon-unknown.svg
│   │           │   │   ├── icon-viewlink.svg
│   │           │   │   ├── icon-yes.svg
│   │           │   │   ├── inline-delete.svg
│   │           │   │   ├── LICENSE
│   │           │   │   ├── README.txt
│   │           │   │   ├── search.svg
│   │           │   │   ├── selector-icons.svg
│   │           │   │   ├── sorting-icons.svg
│   │           │   │   ├── tooltag-add.svg
│   │           │   │   └── tooltag-arrowright.svg
│   │           │   └── js
│   │           │       ├── actions.js
│   │           │       ├── admin
│   │           │       │   ├── DateTimeShortcuts.js
│   │           │       │   └── RelatedObjectLookups.js
│   │           │       ├── autocomplete.js
│   │           │       ├── calendar.js
│   │           │       ├── cancel.js
│   │           │       ├── change_form.js
│   │           │       ├── core.js
│   │           │       ├── filters.js
│   │           │       ├── inlines.js
│   │           │       ├── jquery.init.js
│   │           │       ├── nav_sidebar.js
│   │           │       ├── popup_response.js
│   │           │       ├── prepopulate_init.js
│   │           │       ├── prepopulate.js
│   │           │       ├── SelectBox.js
│   │           │       ├── SelectFilter2.js
│   │           │       ├── theme.js
│   │           │       ├── unusable_password_field.js
│   │           │       ├── urlify.js
│   │           │       └── vendor
│   │           │           ├── jquery
│   │           │           │   ├── jquery.js
│   │           │           │   ├── jquery.min.js
│   │           │           │   └── LICENSE.txt
│   │           │           ├── select2
│   │           │           │   ├── i18n
│   │           │           │   │   ├── af.js
│   │           │           │   │   ├── ar.js
│   │           │           │   │   ├── az.js
│   │           │           │   │   ├── bg.js
│   │           │           │   │   ├── bn.js
│   │           │           │   │   ├── bs.js
│   │           │           │   │   ├── ca.js
│   │           │           │   │   ├── cs.js
│   │           │           │   │   ├── da.js
│   │           │           │   │   ├── de.js
│   │           │           │   │   ├── dsb.js
│   │           │           │   │   ├── el.js
│   │           │           │   │   ├── en.js
│   │           │           │   │   ├── es.js
│   │           │           │   │   ├── et.js
│   │           │           │   │   ├── eu.js
│   │           │           │   │   ├── fa.js
│   │           │           │   │   ├── fi.js
│   │           │           │   │   ├── fr.js
│   │           │           │   │   ├── gl.js
│   │           │           │   │   ├── he.js
│   │           │           │   │   ├── hi.js
│   │           │           │   │   ├── hr.js
│   │           │           │   │   ├── hsb.js
│   │           │           │   │   ├── hu.js
│   │           │           │   │   ├── hy.js
│   │           │           │   │   ├── id.js
│   │           │           │   │   ├── is.js
│   │           │           │   │   ├── it.js
│   │           │           │   │   ├── ja.js
│   │           │           │   │   ├── ka.js
│   │           │           │   │   ├── km.js
│   │           │           │   │   ├── ko.js
│   │           │           │   │   ├── lt.js
│   │           │           │   │   ├── lv.js
│   │           │           │   │   ├── mk.js
│   │           │           │   │   ├── ms.js
│   │           │           │   │   ├── nb.js
│   │           │           │   │   ├── ne.js
│   │           │           │   │   ├── nl.js
│   │           │           │   │   ├── pl.js
│   │           │           │   │   ├── ps.js
│   │           │           │   │   ├── pt-BR.js
│   │           │           │   │   ├── pt.js
│   │           │           │   │   ├── ro.js
│   │           │           │   │   ├── ru.js
│   │           │           │   │   ├── sk.js
│   │           │           │   │   ├── sl.js
│   │           │           │   │   ├── sq.js
│   │           │           │   │   ├── sr-Cyrl.js
│   │           │           │   │   ├── sr.js
│   │           │           │   │   ├── sv.js
│   │           │           │   │   ├── th.js
│   │           │           │   │   ├── tk.js
│   │           │           │   │   ├── tr.js
│   │           │           │   │   ├── uk.js
│   │           │           │   │   ├── vi.js
│   │           │           │   │   ├── zh-CN.js
│   │           │           │   │   └── zh-TW.js
│   │           │           │   ├── LICENSE.md
│   │           │           │   ├── select2.full.js
│   │           │           │   └── select2.full.min.js
│   │           │           └── xregexp
│   │           │               ├── LICENSE.txt
│   │           │               ├── xregexp.js
│   │           │               └── xregexp.min.js
│   │           └── style.css
│   ├── manage.py
│   ├── project
│   │   ├── asgi.py
│   │   ├── __init__.py
│   │   ├── __pycache__
│   │   │   ├── __init__.cpython-312.pyc
│   │   │   ├── settings.cpython-312.pyc
│   │   │   ├── urls.cpython-312.pyc
│   │   │   └── wsgi.cpython-312.pyc
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── requirements.txt
│   ├── static
│   │   └── style.css
│   └── templates
│       ├── base.html
│       └── index.html
└── README.md



---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/kushalyadav0/Django-Boilerplate.git
cd Django-Boilerplate

```
### 2. Set Up Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Requirements
```bash
pip install -r requirements.txt
```

### 4. Setup `.env`
Create a `.env` file based on the provided example:
```bash
SECRET_KEY=your-django-secret-key
DEBUG=True
```

### 5. Run Migrations
```bash
python manage.py migrate
```

### 6. Start Development Server
```bash
python manage.py runserver
```
Visit: http://127.0.0.1:8000

### 🔐 Environment Variables
Use the `.env` file to store secrets and config. Add your:
```bash
SECRET_KEY

DEBUG

DATABASE_URL (for production, if needed)

API_KEY
```
### 🪪 License
This project is licensed under the MIT License.