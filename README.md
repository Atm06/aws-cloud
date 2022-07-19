How To Install HTTPS to Secure Apache with Let's Encrypt TLS/SSL Certificates on UBUNTU LTS.


Let’s Encrypt is a Certificate Authority (CA) that provides a way to obtain and install free TLS/SSL certificates, thereby enabling encrypted HTTPS on web servers. It streamlines the process by providing a software client, Certbot, that attempts to automate most (if not all) of the required steps. Currently, the entire process of obtaining and installing a certificate is fully automated on both Apache and Nginx.

We will use Certbot to obtain a free SSL certificate for Apache on Ubuntu 18.04 and verify that certificate is set up to renew automatically.
