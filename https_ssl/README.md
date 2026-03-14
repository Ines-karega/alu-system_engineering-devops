# 0x0C. HTTPS SSL

## Resources
### Read or watch:
* [What is HTTPS?](https://www.instantssl.com/http-vs-https.html)
* [What are the 2 main elements that SSL is providing](https://www.sslshopper.com/what-is-ssl.html)
* [HAProxy SSL termination on Ubuntu16.04](https://www.digitalocean.com/community/tutorials/how-to-implement-ssl-termination-with-haproxy-on-ubuntu-14-04)
* [SSL termination](https://en.wikipedia.org/wiki/TLS_termination_proxy)
* [Bash function](https://tldp.org/LDP/abs/html/functions.html)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
* What is HTTPS SSL 2 main roles
* What is the purpose encrypting traffic
* What SSL termination means

## Tasks

### 0. World wide web
Configure your domain zone so that the subdomain www points to your load-balancer IP (lb-01). Let’s also add other subdomains to make our life easier, and write a Bash script that will display information about subdomains.

### 1. HAproxy SSL termination
Create a certificate using certbot and configure HAproxy to accept encrypted traffic for your subdomain www.

### 2. No loophole in your website traffic
Configure HAproxy to automatically redirect HTTP traffic to HTTPS.
