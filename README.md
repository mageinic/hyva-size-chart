# Hyvä Size Chart

**Hyvä Size Chart is a part of MageINIC Size Chart extension that adds Hyvä features.** This extension extends Size Chart definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/hyva-size-chart

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Size Chart requires installing [MageINIC Size Chart](https://github.com/mageinic/size-chart) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/size-chart
```

## 2. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
