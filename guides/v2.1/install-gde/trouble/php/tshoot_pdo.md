---
group: install_trouble
subgroup: 03_install
title: During installation, fatal PDO error displays
menu_title: During installation, fatal PDO error displays
menu_node:
menu_order: 21
redirect_from:
  - /guides/v1.0/install-gde/trouble/tshoot_pdo.html
  - /guides/v2.0/install-gde/trouble/tshoot_pdo.html
functional_areas:
  - Install
  - System
  - Setup
---

### Details

	PHP Fatal error:  Class 'PDO' not found in /var/www/html/magento2/setup/module/Magento/Setup/src/Module/Setup/ConnectionFactory.php on line 44

### Solution:

Make sure you installed all required PHP extensions ([Ubuntu]({{ page.baseurl }}/install-gde/prereq/php-centos.html">CentOS</a>, <a href="{{ page.baseurl }}/install-gde/prereq/php-ubuntu.html)). 

