# Setting Up E-commerce Using WooCommerce

## Description

In this lesson you will learn the basics of using the WooCommerce plugin for WordPress. By the end of this lesson, you will understand installation, general store settings, adding and editing products, order management, sales reporting, and the system status report.

## Objectives

After the end of this lesson, you will be able to:

*   Identify multiple ways in which WooCommerce satisfies the needs of an eCommerce retailer.
*   Install the WooCommerce plugin and complete the initial setup wizard.
*   Add and modify products, review orders, and change your store settings.

## Prerequisite Skills

You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   Basic knowledge of [installing and activating WordPress plugins](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-plugins/)
*   Basic knowledge of [installing and activating WordPress themes](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-a-theme/)
*   [Managing Media](https://make.wordpress.org/training/handbook/user-lessons/managing-media/)
*   [Categories vs Tags](https://make.wordpress.org/training/handbook/user-lessons/categories-vs-tags/)

## Assets

*   [WooCommerce](https://wordpress.org/plugins/woocommerce/) plugin
*   Installation of WordPress
*   [Storefront](https://wordpress.org/themes/storefront/) theme
*   Sample pictures to represent the products: [Phewa lake](https://make.wordpress.org/training/files/2016/07/phewa.jpg), [Karelian forest](https://make.wordpress.org/training/files/2016/07/karelia.jpg) (any other may be used)

## Screening Questions

*   Are you familiar with the concept of a plugin in WordPress?
*   Do you have a self-hosted WordPress website?
*   Do you have a user role that allows you to install plugins?

## Teacher Notes

*   **Time Estimate:** 45 minutes
*   The recommended way to approach the scenarios would be to demonstrate and explain the process first, and then ask students to repeat the actions using their own devices, while you’re available for questions and troubleshooting if something doesn’t work out.
*   It is easiest for students to work on a locally installed copy of WordPress. Set some time aside before class to assist students with installing WordPress locally if they need it or, if possible, send them instructions before the class so they come prepared. For more information on how to install WordPress locally, please visit our [Teacher Resources](https://make.wordpress.org/training/teacher-resources/) page.
*   The preferred answer to the screening questions is “yes.” Participants who reply “no” to question #1 might require a bit of explanation, and if they answer “no” to questions 2 & 3 they may be grouped with other students to work in pairs on the installation.
*   You may print out the Hands-On Walkthrough part to use it as handouts or send it out as a .pdf file to keep it green and preserve the links used throughout the document.
*   This lesson is meant  to serve as an introduction to using WooCommerce and does not aspire to fully cover its functionality. At the end of the lesson feel free to refer your students to the WooCommerce documentation to help them fine-tune their shops. It will be helpful to demonstrate what the documentation looks like and how to use it.

## Hands-on Walkthrough

### Introduction: What is WooCommerce for?

WooCommerce is an e-commerce plugin designed for small to large-sized online merchants using WordPress. Some of its important benefits are:

*   The plugin itself is free.
*   It has very flexible settings including a wide range of product options to sell and over 300 free and paid extensions to choose from.
*   The customer data is independent of any third party software platform.
*   WooCommerce is 100% open source (which allows you to benefit from an active and growing community of contributors).

During the flow of the lesson, we will be working for an imaginary company called YayWP! which sells large sized photo prints that you might want to use to decorate your home. You will install the WooCommerce plugin, set up the newly created e-shop to operate, add some products to the store, and review the menu options and reports. You will also learn about resources you can study to continue refining your e-shop to suit your needs.

### Setting up the shop

#### Preparation

First, you need to have WordPress installed. The second step will be to select a theme for the shop look & feel. Generally, it’s best if the theme is built and optimized for WooCommerce (here is [a guide](https://docs.woocommerce.com/document/choosing-the-right-theme/) you can use). In this lesson, you'll use the [Storefront](https://wordpress.org/themes/storefront/)  theme, which is from WooThemes, the creators of WooCommerce, and is designed to build e-commerce Web sites. Install and activate the theme before you proceed. [tip]Although Storefront is the theme WooThemes recommends for use with WooCommerce (it's their theme, after all!), there are plenty of other themes, both free and commercial, that are designed to integrate well with WooCommerce. If you don't use a theme designed for WooCommerce--and any will do--you'll probably have to add code and other modifications to make your store work.[/tip]

#### WooCommerce Installation

[tip]For the training purposes it’s okay to be using a local installation of WordPress, but for a real-life scenario you need to be running WordPress on a self-hosted site and review server requirements before installation. Otherwise, you may encounter issues when using WooCommerce.[/tip] 1\. You will now perform an automatic install of WooCommerce plugin. Log into your WordPress Dashboard and go to **Plugins > Add New**. In the search field, type “WooCommerce” and click Search Plugins. [![Selection_024](https://make.wordpress.org/training/files/2016/07/Selection_024.png)](https://make.wordpress.org/training/files/2016/07/Selection_024.png) Install the newly found plugin by clicking **Install Now** and activate a plugin when prompted by clicking **Activate**. 2\. Once the plugin is activated it will prompt you to set up some initial settings. Click **Let’s go** to proceed. [![Selection_027](https://make.wordpress.org/training/files/2016/07/Selection_027.png)](https://make.wordpress.org/training/files/2016/07/Selection_027.png)

#### Onboarding Wizard

An onboarding wizard will guide you through the steps needed to perform the initial configuration of WooCommerce. 1\. **Page Setup**: This step creates some pages required for an e-commerce store, such as the shop page, cart page, and checkout page. [![Selection_028](https://make.wordpress.org/training/files/2016/07/Selection_028-1024x905.png)](https://make.wordpress.org/training/files/2016/07/Selection_028.png) Select **Continue** to automatically install the default pages. 2\. **Store Locale**: Here you can select your store’s location, currency, and dimensional units for shipping calculations. [![Selection_029](https://make.wordpress.org/training/files/2016/07/Selection_029-1024x891.png)](https://make.wordpress.org/training/files/2016/07/Selection_029.png) Make sure your location is correctly auto-detected then click **Continue**. 3\. **Shipping & Tax**: if you enable taxes, further options will appear and you will be able to choose how to enter prices, with/without tax, and check the list of taxes WooCommerce will create for you (which you can change later). Normally you would need to consult a tax professional in your country to ensure these rates are correct. [![Selection_030](https://make.wordpress.org/training/files/2016/07/Selection_030-1024x886.png)](https://make.wordpress.org/training/files/2016/07/Selection_030.png) For this demo, disable the option to charge sales tax and enable the “shipping physical goods” one. 4\. **Payments**: Here you can set the payment methods used by your shop. The PayPal option is powered by Braintree and/or Stripe which are free but separate plugins downloaded automatically from WordPress.org. You'll need a PayPal account configured to receive payments to use this option. To simplify the configuration here, you won't configure the PayPal payment option. [![Selection_031](https://make.wordpress.org/training/files/2016/07/Selection_031.png)](https://make.wordpress.org/training/files/2016/07/Selection_031.png) Select the **Cash on Delivery** option and click **Continue.** 5\. After the wizard is complete, you will be prompted to click **Create your first product!** button. Go ahead and click that button to start the process of adding your first product to the shop. [![Selection_032](https://make.wordpress.org/training/files/2016/07/Selection_032-1024x889.png)](https://make.wordpress.org/training/files/2016/07/Selection_032.png)

### Adding a new product

#### Shop Organization: Categories, product tags, and attributes

Recall that your imaginary client YayWP! is selling large posters. Presumably, YayWP! customers are interested in the thematics and the size of the picture. You will use **Product Categories** to indicate the thematic, and you also have to manage the sizes available for sale. Product categories and tags are very similar to regular post categories and tags. So, for sizes you could try to use product categories as well, but there are two reasons why that is not the most convenient option:

*   The larger the print becomes, the more expensive it is, so it would be best to be able to set different prices for different sizes, while still having the picture and all its sizes listed as one item. This will make it easier for your customers to find and order the product.
*   A user might want to include both size and thematics as their search parameters simultaneously.

**Variable products** are a product type in WooCommerce that lets you offer a set of variations on a product, with control over prices, stock, image, and more for each variation. **Attributes** are pieces of data that can add more technical information to a product and help users refine your catalog while browsing/searching. Additionally, attributes are a key component of authoring variable products. [![Selection_034](https://make.wordpress.org/training/files/2016/07/Selection_034.png)](https://make.wordpress.org/training/files/2016/07/Selection_034.png) In the **WooCommerce > Products > Attributes** section, add an attribute before you create different variations of the picture. Type in “size” for the attribute name, and click **Add Attribute**.

#### Managing a new variable product

1\. Go to: **WooCommerce > Add Product**. Generally, adding a product feels quite similar to writing a regular post in WordPress, so the view of the form should be familiar. [![Selection_047](https://make.wordpress.org/training/files/2016/07/Selection_047-1024x964.png)](https://make.wordpress.org/training/files/2016/07/Selection_047.png) You'll fill in the basic data first: name of the product, description, and  product categories as shown in the image above. 2\. Add a product image using the Product Image form (under product tags). You may use a sample picture provided to “sell” it or use some other picture of your liking. This is how an added image appears once you add it: [![Selection_048](https://make.wordpress.org/training/files/2016/07/Selection_048.png)](https://make.wordpress.org/training/files/2016/07/Selection_048.png) 3\. Now, make the product variable. Select **Variable product** option in the Product Data dropdown list. [tip] Here is a bit more detail about the some of the other product options:

*   A **Simple** product type describes the physical off-line product which requires shipping. A book or a laptop which do not require variation would be simple products.
*   A **Virtual** product is a product that doesn’t require shipping, for example online tarot reading.
*   A **Downloadable** product is similar to virtual, however, the customer is given a file to download - could be an indie video game.

At the moment virtual and downloadable products are not present in our list as we have no digital payment method configured. [/tip] 4\. Click through the first tabs of Product data meta box: **Inventory**, **Shipping**, and **Linked products**. This is where you can add some important data for your products. At the moment, you will skip through them and go straight to setting the product attributes and variations. Open the **Attributes** section. [![Selection_036](https://make.wordpress.org/training/files/2016/07/Selection_036.png)](https://make.wordpress.org/training/files/2016/07/Selection_036.png) 5\. Select "size" from the select box, and click **Add**. [tip]By choosing ‘Custom product attribute’ from the select box you can apply custom product-level which will not be available in layered navigation or other products.[/tip] [![Selection_037](https://make.wordpress.org/training/files/2016/07/Selection_037.png)](https://make.wordpress.org/training/files/2016/07/Selection_037.png) 6\. Once you have chosen an attribute and added it, apply the terms attached to that attribute to the product. The attribute can be hidden on the frontend of your site by leaving the **Visible on the product page** checkbox unchecked. Check both of the checkboxes and click **Add new** to add the values to the poster's available sizes. [![Selection_059](https://make.wordpress.org/training/files/2016/07/Selection_059.png)](https://make.wordpress.org/training/files/2016/07/Selection_059.png) 7\. Type in 27x39" and click **OK**. Repeat adding with 18x11" size. [![Selection_039](https://make.wordpress.org/training/files/2016/07/Selection_039.png)](https://make.wordpress.org/training/files/2016/07/Selection_039.png) 8\. Save the entered attributes data by clicking **Save attributes**. 9\. Switch to the **Variations** tab. [![Selection_040](https://make.wordpress.org/training/files/2016/07/Selection_040.png)](https://make.wordpress.org/training/files/2016/07/Selection_040.png) Make sure **Create variations from all attributes** option is selected and click **Go**. Then click **OK** on the confirmation message pop-up. 10\. Now the two variations for your product are created, it's time to set up how they should be distinguished on your product page. [![Selection_061](https://make.wordpress.org/training/files/2016/07/Selection_061.png)](https://make.wordpress.org/training/files/2016/07/Selection_061.png) Click each of the variation panels for each combination and enter price - 15$ for the larger poster and 10$ for the smaller one. [![Selection_062](https://make.wordpress.org/training/files/2016/07/Selection_062.png)](https://make.wordpress.org/training/files/2016/07/Selection_062.png) 11\. Click **Save changes** when you are finished. 12\. Try to save the product now. Click **Publish** to publish the product. You'll get a pop-up warning that the shipping settings are not set up. Select **Setup shipping zones** to set them up. [![sh](https://make.wordpress.org/training/files/2016/07/sh.png)](https://make.wordpress.org/training/files/2016/07/sh.png) 13\. **Shipping zones** are regions that you ship to. You can have multiple shipping methods and rates that apply to a certain region. For now, to keep things simple, be generous and set up free shipping worldwide. Set the shipping method for the "Rest of the World" zone by selecting **Free Shipping** in the **Add shipping method** pop-up. Click **Save changes** to save your changes. [![sh2](https://make.wordpress.org/training/files/2016/07/sh2.png)](https://make.wordpress.org/training/files/2016/07/sh2.png)

### Shop Overview

At this point, the shop is fully operational. Take a look on how it looks by going to the **Shop** page of your site. [![v](https://make.wordpress.org/training/files/2016/07/v-1024x924.png)](https://make.wordpress.org/training/files/2016/07/v.png) [![v2](https://make.wordpress.org/training/files/2016/07/v2.png)](https://make.wordpress.org/training/files/2016/07/v2.png) The look is quite not polished, but this could be a foundation of a great WordPress-based shop. Note you can also create custom menus and place it in your theme’s menu areas or in a widgetized area with the menus widget if you like. **Exercice:** Create an order with the product. This is required to display how the orders are treated in the dashboard.

### WooCommerce menu items

#### Dashboard

The WordPress customizable dashboard is normally the first thing you see when you log in to the site.  After being activated, WooCommerce adds two dashboard widgets you can use for an overview of your store:

*   The **WooCommerce Status** widget gives you a quick overview of your store, alerting you if you have a processing order or an order on-hold, or a product is running low on stock. It also displays sales statistics.
*   The **WooCommerce Recent Reviews** widget displays your store’s most recent reviews.

[![dash](https://make.wordpress.org/training/files/2016/07/dash.png)](https://make.wordpress.org/training/files/2016/07/dash.png) What you have in your store for now is quite modest. Below is a screen capture of another shop’s dashboard with some customized widgets so you can see what the dashboard for a fully implemented WooCommerce store might look like. [![dash4](https://make.wordpress.org/training/files/2016/07/dash4.jpg)](https://make.wordpress.org/training/files/2016/07/dash4.jpg)

#### WooCommerce Menu

Take a look at the other menu sections. [![orders](https://make.wordpress.org/training/files/2016/07/orders-1024x405.png)](https://make.wordpress.org/training/files/2016/07/orders.png) 1.Use the **Orders** section to view and manage orders. If you have completed a product purchase, this menu item will appear. 2.The **Coupons** section allows giving discounts by creating coupons that can be applied by customers on the checkout page. [![rep](https://make.wordpress.org/training/files/2016/07/rep-1024x846.png)](https://make.wordpress.org/training/files/2016/07/rep.png) 3\. In the **Reports** section, you can view data on the store activity and export it as a .csv file. [![sett](https://make.wordpress.org/training/files/2016/07/sett.png)](https://make.wordpress.org/training/files/2016/07/sett.png) 4.The **Settings** section contains all the settings that you briefly explored when setting up the shop: page setup, catalog setup, tax, shipping, and payment gateways. [![syssta](https://make.wordpress.org/training/files/2016/07/syssta-1024x499.png)](https://make.wordpress.org/training/files/2016/07/syssta.png) 5. **System Status** provides an overall snapshot of your setup, as well as potential conflicts, and is mostly used for troubleshooting on your own or when contacting support. [![addons](https://make.wordpress.org/training/files/2016/07/addons-1024x553.png)](https://make.wordpress.org/training/files/2016/07/addons.png) 6.The **Add-ons** section is where you can browse for additional plugins and extensions to extend the functionality and features of your store.

#### Products Menu

[![products](https://make.wordpress.org/training/files/2016/07/products-1024x426.png)](https://make.wordpress.org/training/files/2016/07/products.png) This top-level menu has sections relating to managing products. This lesson used the **Products** and **Attributes** sections earlier. There are additional sections to modify, add, and delete product **Categories** and **Tags.** [tip]Click on the star in the product listing to make the product "featured".[/tip]

## Exercises

Suggested exercises are meant to reinforce the acquired knowledge of performing basic operations within the shop, navigating the menu, and adjusting settings without the teacher's guidance.

1.  Add another product: you may use provided Karelian forest picture or use some picture of your liking. This poster is expected to be so popular it should be available in 3 sizes: 27x39", 18x11" and 36x54''.
2.  Change the location and currency to something different (i.e. Turkey, Turkish liras).
3.  Change the shipping settings: keep it free in your home country but add a price for the rest of the world.
4.  Mark an earlier created pending order as complete and observe the changes.

## Quiz

**Which of the following is NOT a part of WooCommerce core functionality?**

1.  SEO
2.  Reports on sales volume
3.  Coupons management
4.  Orders management

**Answer:** 1\. SEO **Which of the following describes a WooCommerce variable product?**

1.  A set of variations on a product, with a random option chosen
2.  A product listed and described at a website but sold from a third-party website
3.  A product that doesn’t require shipping
4.  A set of variations on a product, with control over prices, stock, image, etc.

**Answer:** 4. A set of variations on a product, with control over prices, stock, image, etc **Why would you choose to use attributes instead of product categories to categorize items? (select as many options as apply)**

1.  To allow users to search for several parameters simultaneously.
2.  To ensure better SEO
3.  To define some extra pieces of technical information about the product like color, size, weight, etc
4.  To simplify adding new products
5.  To be able to create coupons to provide discounts to the customers based on their geographical location

**Answer:** 1\. To allow users to search for several parameters simultaneously. & 3. To define some extra pieces of technical information about the product like color, size, weight, etc

## Additional Resources

1.  [WooCommerce blog](https://woocommerce.com/blog/)  is a nice resource to follow for advice,
2.  WooCommerce also offers extensive [documentation](https://docs.woocommerce.com/)  - among the many topics you may want to pay attention to the [Getting started](https://docs.woocommerce.com/documentation/plugins/woocommerce/getting-started/) section and the [WooCommerce-101](https://docs.woocommerce.com/document/woocommerce-101-video-series/) video series for video-oriented people.
3.  An unofficial [Facebook group](https://www.facebook.com/groups/woohelp)<span class="text_exposed_show"> for those who use WooCommerce.</span>
