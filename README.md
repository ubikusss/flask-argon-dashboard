## [Flask Dashboard Argon](https://appseed.us/admin-dashboards/flask-dashboard-argon)

Beautiful [Argon Dashboard](https://www.creative-tim.com/product/argon-dashboard) design coded in [Flask](http://flask.pocoo.org/) 

<hr>

![Flask Dashboard Argon](https://github.com/app-generator/flask-argon-dashboard/blob/master/screenshots/flask-argon-dashboard-intro.gif)

<hr>

Features
------

- SQLite database
- Login, Register
- REST API node on top of [Flask-RESTful](https://flask-restful.readthedocs.io/en/latest/)


### Screenshot - generic page

![Material Dashboard - coded in Flask](https://github.com/app-generator/flask-argon-dashboard/blob/master/screenshots/flask-argon-dashboard-main.jpg)


### Quick Start

1. Clone the repo
  ```
  $ git clone https://github.com/app-generator/flask-argon-dashboard.git
  $ cd flask-argon-dashboard
  ```

2. Initialize and activate a virtualenv:
  ```
  $ virtualenv --no-site-packages env
  $ source env/bin/activate
  ```

3. Install the dependencies:
  ```
  $ pip install -r requirements.txt
  ```

4. Create the database, using Flask shell
  ```
  $ flask shell
  $ >>> from app import db
  $ >>> db.create_all()
  ```

5. Run the development server:
  ```
  $ flask run
  ```

6. See the running app by visiting [http://localhost:5000](http://localhost:5000) in your browser


## Support
- For issues and features request, use [Github](https://github.com/app-generator/flask-argon-dashboard/issues/new) or join [AppSeed](https://appseed.us) community on [Discord](https://discord.gg/fZC6hup)   


### App Screenshots

![Flask Dashboard](https://github.com/app-generator/flask-argon-dashboard/blob/master/screenshots/flask-argon-dashboard-login.jpg)
![Flask Dashboard](https://github.com/app-generator/flask-argon-dashboard/blob/master/screenshots/flask-argon-dashboard-profile.jpg)

### Resources

 - [Flask Dashboard Argon](https://appseed.us/admin-dashboards/flask-dashboard-argon) - app info
 - Product [documentation](https://docs.appseed.us/admin-dashboards/flask-dashboard-argon/)
 - Live [DEMO](https://flask-argon-dashboard.appseed.us/)
 - Related [Blog Article](https://blog.appseed.us/flask-dashboard-argon-zero-to-full-stack/)
 - [Argon Dashboard](https://www.creative-tim.com/product/argon-dashboard) - design information (Creative-Tim)
 - [Flask](http://flask.pocoo.org/) - official website
 

---
Made with ♥ by [AppSeed](https://appseed.us?ref=github)

