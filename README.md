# twebix
A set small-footprint applications to implement a fully functional server in a low footprint device (such as a Raspberry Pi Zero).

Tools:

* libtwebix: include the basis to create all twebix applications. Include functions to read/write configuration files (in Lua), interpret JSON, call REST, etc.
* twhttps: convert https requests to http
* 

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
