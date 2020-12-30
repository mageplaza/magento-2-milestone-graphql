# Magento 2 Milestone GraphQL/PWA

**Magento 2 Milestone GraphQL is now a part of the Mageplaza Milestone GraphQL extension that adds GraphQL features. This upgrade supports PWA Studio.** 

[Mageplaza Milestone for Magento 2](https://www.mageplaza.com/magento-2-milestone/) is a useful tool that helps online store owners segment and categorize customers into different groups to manage better and take care of them. Accordingly, you deliver different policies and benefits in each separate group, and customers in each of these groups will get the respective benefits. This makes it easier for you to serve different types of customers coming to your stores, such as newcomers, customers who purchase in bulk, or loyal customers. It ensures that you target marketing to the right customers. 

At first, you can automatically switch customers to different groups based on: 
- Customer data: name, gender, email, etc. 
- Shipping address 
- The original group of customers

When shoppers come to your website, their conditions to match different groups might be changing if they continue purchasing. That’s why you need to arrange them into more appropriate groups to serve them in a better manner. The conditions to switch customer groups can be set up easily based on customer attributes, orders, and items in their carts. There will be an email sent to customers to notify them about their changed customer group. It timely updates customers’ benefits in new groups so that customers can confidently shop more with their up-leveled benefits. You can also group and switch customers to another group based on the order attributes and order data, including category, product quality, average order amount, total order amount, product type, or color, etc. 

For newcomers to a group, you can offer extra discount coupons as gifts to welcome them and an incentive to boost sales. The details of these coupons will be sent via email to customers so that you don’t have to worry that your coupons will be lost out of nowhere and your customers can’t use them for their purchases. 

Furthermore, you can set up the switching rules based on events or cron. If choosing events, the rule will be activated whenever there are any actions, like creating and saving accounts or orders. If selecting cron, the switching rules will be run according to frequency, daily, weekly, monthly, and more. 

In short, Mageplaza Milestone extension will give you peace of mind with effective customer management that enables you to serve customers in a way more personalized than ever.

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

- [Magento 2 Milestone API & examples](https://documenter.getpostman.com/view/10589000/T1LJm8wp)
- [Magento 2 Milestone GraphQL & examples](https://documenter.getpostman.com/view/10589000/TVmTaZia)


## 4. Contribute to this module

- Feel free to **Fork** and contribute to this module. 
- You can create a pull request and we will merge your changes main branch.

## 5. Get Support

- Feel free to [contact us](https://www.mageplaza.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star** ![star](https://i.imgur.com/S8e0ctO.png)
