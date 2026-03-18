# Load Balancer Project

This project focuses on improving web infrastructure redundancy by setting up a load balancer and multiple web servers.

## Tasks

### 0. Double the number of webservers
Configure `web-01` and `web-02` to include a custom Nginx response header: `X-Served-By` which contains the hostname of the server. This allows tracking which server is responding to HTTP requests.

### 1. Install your load balancer
Install and configure HAproxy on `lb-01` to distribute traffic to `web-01` and `web-02` using a round-robin algorithm.