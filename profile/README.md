<p align="center">
  <img src="https://raw.githubusercontent.com/fastapi-users/fastapi-users/master/logo.svg?sanitize=true" alt="FastAPI Users">
</p>

<p align="center">
    <em>Ready-to-use and customizable users management for FastAPI </em>
</p>

---

**Documentation**: <a href="https://fastapi-users.github.io/fastapi-users/" target="_blank">https://fastapi-users.github.io/fastapi-users/</a>

**Source Code**: <a href="https://github.com/fastapi-users/fastapi-users" target="_blank">https://github.com/fastapi-users/fastapi-users</a>

---

Add quickly a registration and authentication system to your [FastAPI](https://fastapi.tiangolo.com/) project. **FastAPI Users** is designed to be as customizable and adaptable as possible.

## Features

* [X] Extensible base user model
* [X] Ready-to-use register, login, reset password and verify e-mail routes
* [X] Ready-to-use social OAuth2 login flow
* [X] Dependency callables to inject current user in route
* [X] Pluggable password validation
* [X] Customizable database backend
    * [X] SQLAlchemy async backend included thanks to [encode/databases](https://www.encode.io/databases/)
    * [X] MongoDB async backend included thanks to [mongodb/motor](https://github.com/mongodb/motor)
    * [X] [Tortoise ORM](https://tortoise-orm.readthedocs.io/en/latest/) backend included
    * [X] [ormar](https://collerek.github.io/ormar/) backend included

* [X] Multiple customizable authentication backends
    * [X] JWT authentication backend included
    * [X] Cookie authentication backend included
* [X] Full OpenAPI schema support, even with several authentication backends

## 📚 Discover my book: *Building Data Science Applications with FastAPI*

<img src="https://static.packt-cdn.com/products/9781801079211/cover/smaller" alt="Building Data Science Applications with FastAPI" height="256px" align="right">

**Develop, manage, and deploy efficient machine learning applications with Python**

### What is this book about?

This book covers the following exciting features:

* Explore the basics of modern Python and async I/O programming
* Get to grips with basic and advanced concepts of the FastAPI framework
* Implement a FastAPI dependency to efficiently run a machine learning model
* Integrate a simple face detection algorithm in a FastAPI backend
* Integrate common Python data science libraries in a web backend
* Deploy a performant and reliable web backend for a data science application

If you feel this book is for you, get your [copy](https://amzn.to/3kTvgjG) today!
