# [Atlantis Dark Flask](https://appseed.us/product/atlantis-dark/flask/)

Open-source **Flask Dashboard** generated by `AppSeed` op top of a modern `Bootstrap` design. **[Atlantis Lite](https://appseed.us/product/atlantis-dark/flask/)** is a free bootstrap 4 admin dashboard that is beautifully and elegantly designed to display various metrics, numbers or data visualization. Atlantis Lite admin dashboard has 2 layouts, many plugins and UI components to help developers create dashboards quickly and effectively so they can save development time and also help users to make the right and fast decisions based on existing data.

- 👉 Free [support](https://appseed.us/support/) via Email & `Discord` 
- 🚀 [Custom Development Services](https://appseed.us/custom-development/) for `accelerated growth`
- ✅ [Deploy on AWS, DO, and Azure](https://deploypro.dev/) via `DeployPRO` service (read the [DOCS](https://www.docs.deploypro.dev/))

<br />

### `PROMO` [Discounts for Developers](https://appseed.us/discounts/) Up to `30%OFF`

> The **discount is applicable to all products and licenses** (no stock limits) 

[![Discounts for Developers and Designers - AppSeed](https://user-images.githubusercontent.com/51070104/229268648-6ded378f-33aa-4909-a090-31fca49caa49.png)](https://appseed.us/discounts/)

<br />

> Built with [App Generator](https://appseed.us/generator/), timestamp `2025-02-15 11:54`

- ✅ `Up-to-date dependencies`
- ✅ `Database`: `SQLite`, MySql
  - Silent fallback to `SQLite`
- ✅ `DB Tools`: SQLAlchemy ORM, Flask-Migrate (schema migrations)
- ✅ Session-Based authentication (via **flask_login**), Forms validation
- ✅ `Flask-Minify` (page compression)

<br />

![Atlantis Dark - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172799909-4cbc8eed-fdde-4408-ab61-123f235212d0.png)

<br />





## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/19dcfa53-dd0e-489b-be94-d51eaae313f3.git
$ cd 19dcfa53-dd0e-489b-be94-d51eaae313f3
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Create Users

By default, the app redirects guest users to authenticate. In order to access the private pages, follow this set up: 

- Start the app via `flask run`
- Access the `registration` page and create a new user:
  - `http://127.0.0.1:5000/register`
- Access the `sign in` page and authenticate
  - `http://127.0.0.1:5000/login`

<br />

## ✨ Code-base structure

The project is coded using blueprints, app factory pattern, dual configuration profile (development and production) and an intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/
   |    |
   |    |-- home/                           # A simple app that serve HTML files
   |    |    |-- routes.py                  # Define app routes
   |    |
   |    |-- authentication/                 # Handles auth routes (login and register)
   |    |    |-- routes.py                  # Define authentication routes  
   |    |    |-- models.py                  # Defines models  
   |    |    |-- forms.py                   # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>          # CSS files, Javascripts files
   |    |
   |    |-- templates/                      # Templates used to render pages
   |    |    |-- includes/                  # HTML chunks and components
   |    |    |    |-- navigation.html       # Top menu component
   |    |    |    |-- sidebar.html          # Sidebar component
   |    |    |    |-- footer.html           # App Footer
   |    |    |    |-- scripts.html          # Scripts common to all pages
   |    |    |
   |    |    |-- layouts/                   # Master pages
   |    |    |    |-- base-fullscreen.html  # Used by Authentication pages
   |    |    |    |-- base.html             # Used by common pages
   |    |    |
   |    |    |-- accounts/                  # Authentication pages
   |    |    |    |-- login.html            # Login page
   |    |    |    |-- register.html         # Register page
   |    |    |
   |    |    |-- home/                      # UI Kit Pages
   |    |         |-- index.html            # Index page
   |    |         |-- 404-page.html         # 404 page
   |    |         |-- *.html                # All other pages
   |    |    
   |  config.py                             # Set up the app
   |    __init__.py                         # Initialize the app
   |
   |-- requirements.txt                     # App Dependencies
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- run.py                               # Start the app - WSGI gateway
   |
   |-- ************************************************************************
```

<br />



## [Atlantis Dark PRO Flask](https://appseed.us/product/atlantis-dark-pro/flask/)

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Black Dashboard is a premium Bootstrap Design now available for download in Flask. Made of hundred of elements, designed blocks, and fully coded pages, Black Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [Atlantis Dark PRO Flask](https://appseed.us/product/atlantis-dark-pro/flask/) - product page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Atlantis Dark PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172800034-4d3adb79-d05e-430d-8ffe-f6860fc755f1.png)

<br />

---
[Atlantis Dark Flask](https://appseed.us/product/atlantis-dark/flask/) - Open-source starter generated by **[App Generator](https://appseed.us/generator/)**.
