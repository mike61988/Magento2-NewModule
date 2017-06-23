**Just Magento 2 NewModule by Mk**

### Install via composer

Run the following command in Magento 2 root folder

```
composer require mike61988/magento2-NewModule

php bin/magento module:status
php bin/magento module:enable Mk_NewModule
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```