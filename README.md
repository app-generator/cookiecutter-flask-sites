# Cookiecutter Flask

**Flask Cookie-Cutter** is an open-source `cookiecutter` template built on top of a simple **Flask** codebase with a modern design. For newcomers, **Cookiecutter** is a command-line utility that creates projects from project templates and Django is a leading web framework built by experts using a batteries-included concept.

- UI Themes: `Volt Design` / `Soft UI` / `Datta Able` / `Material Dashboard`
- Generated Projects Features:
  - `Up-to-date dependencies`: **Flask 2.0.1**
  - `SCSS` -> `CSS` compilation via **Gulp**   
  - Persistence: `SQLite` / `MySql` / `PostgreSQL`
  - `Session-Based Authentication`, Forms validation
  - **Deployment**: `Gunicorn` / `Nginx`
  - One-line **Docker** setup
    - `docker-compose up --build` 

<br />

> Project Customization:

- Project information: `name`, `author`, `email`
- Database Engine: `SQLite`, `MySql` or `PostgreSql`
- UI Themes:
  - LIVE Preview: [Volt Bootstrap](https://flask-volt-dashboard.appseed-srv1.com/)
  - LIVE Preview: [Soft UI](https://flask-soft-ui-dashboard.appseed-srv1.com/)
  - LIVE Preview: [Datta Able](https://flask-datta-able.appseed-srv1.com/)
  - LIVE Preview: [Material Dashboard](https://flask-material-dashboard.appseed-srv1.com/)

<br />

> Links

- [Flask Dashboards](https://appseed.us/admin-dashboards/flask) - index provided by AppSeed
- [Open-Source Dashboards](https://appseed.us/admin-dashboards/open-source) - crafted in **Flask**, **Django**, [React](https://appseed.us/apps/react)
- Support via **Github** (issues tracker) and [Discord](https://discord.gg/fZC6hup).

<br />

![Flask Bootstrap 5 Volt - Template project provided by AppSeed.](https://raw.githubusercontent.com/app-generator/flask-dashboard-volt/master/media/flask-dashboard-volt-intro.gif)

<br />

## How to use it

<br />

### Using `cookiecutter` tool 

> **Step #1** - Create a virtual environment  

```bash
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate 
```

<br />

> **Step #2** - Install Depenedencies 

```bash
$ # Install modules - SQLite Storage
$ pip3 install -r requirements.txt
```

<br />

> **Step #3** - Generate the project 

```bash
$ cookiecutter https://github.com/app-generator/cookiecutter-flask.git
```

<br />

### Using `appseed-shell` package 

> **Step #1** - Install Dependencies

```bash
$ pip3 install cookiecutter
$ pip3 install GitPython
$ pip3 install appseed-shell
```

<br />

> **Step #2** - Launch the Python shell and generate the product

```python
$ python
>>> from appseed_shell import generate_flask
>>> generate_flask()
```

<br />

## Credits & Links

For more resources and support please access: 

- [AppSeed](https://appseed.us) - For more starters and support
- [AppSeed Shell](https://github.com/app-generator/appseed-shell-py) - source code (MIT License)

<br />

---
**Flask Cookie-Cutter** - Provided by **AppSeed** [App Generator](https://appseed.us/app-generator).
