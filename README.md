# Nginx Virtual Host Setup on Ubuntu

## Project Overview

This project demonstrates how to configure multiple virtual hosts using Nginx on Ubuntu Linux.

## Technologies Used

- Ubuntu Linux
- Nginx
- Virtual Hosts
- Linux File Permissions
- Networking
- Git & GitHub

## Websites Created

### Site 1
URL:
http://site1.local

Features:
- Custom HTML page
- Dedicated document root
- Separate Nginx server block

### Site 2
URL:
http://site2.local

Features:
- Custom HTML page
- Dedicated document root
- Separate Nginx server block

## Project Structure

/var/www/site1

/var/www/site2

/etc/nginx/sites-available/site1

/etc/nginx/sites-available/site2

/etc/nginx/sites-enabled/

## Configuration Validation

```bash
sudo nginx -t
```

Output:

```text
syntax is ok
test is successful
```

## Learning Outcomes

- Configure Nginx Virtual Hosts
- Manage Linux directories and permissions
- Create custom server blocks
- Configure local DNS resolution using hosts file
- Test and validate Nginx configurations


