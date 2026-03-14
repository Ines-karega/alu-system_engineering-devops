# HTTPS SSL

This project focuses on securing web infrastructure using HTTPS and SSL. It includes a script for subdomain auditing and HAProxy configurations for SSL termination and redirection.

## Tasks

### 0. World wide web
A Bash script `0-world_wide_web` that displays information about subdomains (www, lb-01, web-01, web-02) for a given domain using `dig` and `awk`.

### 1. HAproxy SSL termination
A HAProxy configuration file `1-haproxy_ssl_termination` that terminates SSL on port 443.

### 2. No loophole in your website traffic
A HAProxy configuration file `2-redirect_http_to_https` that redirects all HTTP traffic to HTTPS with a 301 status code.
