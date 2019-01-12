# lampstack-wordpress

Install Apache / PHP / MySQL / WordPress / LetsEncrypt
```
bash <(wget --no-check-certificate -qO- https://raw.githubusercontent.com/aristosv/lampstack-wordpress/master/lamp)
```
Run the command above on a clean, minimal installation of Debian Stretch.

You will be asked to enter some information and the script will install Apache, PHP, MySQL and WordPress.

You will also be given 2 more options:
- use a gmail account for php mail functionality
- secure your website with a Let's Encrypt certificate

As soon as the script is done you can visit your domain URL and start the WordPress wizard.
