# Requirement

To install this theme you must have a working version of WordPress. Please refer to WordPress documentation for further instructions. You can download the latest version of WordPress here [https://wordpress.org/download/](https://wordpress.org/download/)

* WordPress 4.6 or higher
* WooCommerce 4.0 or higher
* [For best performance we recommend using PHP 7.2 or higher.](https://wordpress.org/support/upgrade-php/)
* MySQL 5.6 or greater OR MariaDB 10.0 or greater
* Nginx or Apache with mod\_rewrite module
* This theme is tested under Mac, Windows and Linux.
* Please install the XMLReader PHP extension on your server

{% hint style="warning" %}
If the import stalls and fails to respond after a few minutes, or it fails with a simple error message like “Import failed,” You are suffering from PHP configuration limits that are set too low to complete the process. You should contact your web host and ask them to increase those limits to a minimum as follows:

* max\_execution\_time 3600
* max\_input\_time 3600
* memory\_limit 256M
* post\_max\_size 64M
* upload\_max\_filesize 64M
* max\_input\_vars 3000
* **allow\_url\_fopen on** (!important)
* Please install the XMLReader PHP extension on your server
{% endhint %}
