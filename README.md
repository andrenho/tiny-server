# tiny-web-mvc
A C++ framework to create a MVC web application, meant for tiny servers (like Raspberry Pi Zero).

Modules:

- Load balancer
  - HTTPS to HTTP offloader
  - Redirection (target groups)
  - Health checks and scaling
- Static web server
- REST web server
  - REST support: HTTP controller + JSON parser
  - MVC architecture (Spring-like)
  - Hibernate-like (SQLite)
