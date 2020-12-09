# Magento 2 Milestone GraphQL/PWA

Magento 2 Milestone GraphQL is a part of Pre Order extension that add GraphQL features, this support for PWA Studio.
## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageplaza/module-milestone-graphql
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

**Note:**
Magento 2 Milestone GraphQL requires installing [Mageplaza Milestone](https://www.mageplaza.com/magento-2-milestone/) in your Magento installation.

## 2. How to use

To perform GraphQL queries in Magento, please do the following requirements:

- Use Magento 2.3.x or higher. Set your site to [developer mode](https://www.mageplaza.com/devdocs/enable-disable-developer-mode-magento-2.html).
- Set GraphQL endpoint as `http://<magento2-server>/graphql` in url box, click **Set endpoint**. 
(e.g. `http://dev.site.com/graphql`)
- To view the queries that the **Mageplaza Milestone GraphQL** extension supports, you can look in `Docs > Query` in the right corner

## 3. Devdocs

- [Milestone API & examples](https://documenter.getpostman.com/view/10589000/T1LJm8wp)
- [Milestone GraphQL & examples](https://documenter.getpostman.com/view/10589000/TVmTaZia)


## 4. Contribute to this module

Feel free to **Fork** and contribute to this module and create a pull request so we will merge your changes main branch.

## 5. Get Support

- Feel free to [contact us](https://www.mageplaza.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star** ![star](https://i.imgur.com/S8e0ctO.png)
