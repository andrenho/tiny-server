# twebix
A set small-footprint applications to implement a fully functional server in a low footprint device (such as a Raspberry Pi Zero).

Tools:

Libraries:

* **libtwebix**: include the basis to create all twebix applications.
  * include functions to read/write configuration files (in Lua), interpret JSON, call REST, etc.
  * make a HTTP interface available to check for memory usage, CPU usage, etc
* **libtwapp**: Spring-like library, used to create web apps

Basic infrastructure:

* **tw-https**: convert https requests to http
* **tw-redirect**: redirect http requests based on path, parameters, headers
* **tw-loadbalancer**: perform load balancing and health checks

Full-fledged applications:

* **tw-webstatic**: serve static HTTP content
* **tw-health**: information about server health
