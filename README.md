# [Cookie-Cutter Flask](https://blog.appseed.us/cookie-cutter-flask-generate-website-templates/) Sites

**Flask Cookie-Cutter** is an open-source `cookiecutter` template built on top of a simple **Flask** codebase with a modern design. For newcomers, **Cookiecutter** is a command-line utility that creates projects from project templates and Django is a leading web framework built by experts using a batteries-included concept.

- UI Themes: `Pixel Lite` / `Material Kit` 
- Generated Projects Features:
  - `Up-to-date dependencies`: **Flask 2.0.1**
  - `SCSS` -> `CSS` compilation via **Gulp**   
  - Persistence: `SQLite` / `MySql` / `PostgreSQL`
  - `Session-Based Authentication`, Forms validation
  - **Deployment**: `Gunicorn` / `Nginx`
  - One-line **Docker** setup
    - `docker-compose up --build` 

<br />

![Cookie-Cutter Flask - open-source generator provided by AppSeed.](https://user-images.githubusercontent.com/51070104/143268488-323b8bf6-298c-4fc6-b81e-d5cdced1a1db.jpg)

<br />

> Project Customization:

- Project information: `name`, `author`, `email`
- Database Engine: `SQLite`, `MySql` or `PostgreSql`
- UI Themes:
  - LIVE Preview: [Pixel Lite](https://flask-pixel-lite.appseed-srv1.com)
  - LIVE Preview: [Material Kit](https://flask-material-kit.appseed-srv1.com)

<br />

> Links

- [Flask Apps](https://appseed.us/apps/flask-apps) - index provided by AppSeed
- [Open-Source Dashboards](https://appseed.us/admin-dashboards/open-source) - crafted in **Flask**, **Django**, [React](https://appseed.us/apps/react)
- Support via **Github** (issues tracker) and [Discord](https://discord.gg/fZC6hup).

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
$ cookiecutter https://github.com/app-generator/cookiecutter-flask-sites.git
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
>>> from appseed_shell import generate_flask_sites
>>> generate_flask_sites()
```

<br />

## Credits & Links

For more resources and support please access: 

- [AppSeed](https://appseed.us) - For more starters and support
- [AppSeed Shell](https://github.com/app-generator/appseed-shell-py) - source code (MIT License)

<br />

---
**[Cookie-Cutter Flask](https://blog.appseed.us/cookie-cutter-flask-generate-website-templates/)** - Provided by **AppSeed** [App Generator](https://appseed.us/app-generator).
