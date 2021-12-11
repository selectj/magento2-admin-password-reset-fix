# Magento 2 Admin Password Reset Fix

Magento 2.4 seemed to introduce a bug with the admin reset password form whereby the page rendered, but the form had no content.

This module overwrites the `resetforgottenpassword.phtml` template to fix the issue


## Installing 

To install, follow these steps:

```
composer require selectj/magento2-admin-password-reset-fix
bin/magento setup:upgrade
bin/magento setup:di:compile
bin/magento setup:static-content:deploy
bin/magento cache:flush
```


## Contact

If you want to contact me you can reach me at josephjamesmetcalfe@gmail.com.
