# Setting Up E-commerce Using WooCommerce

## Description

In this lesson you will learn the basics of using the WooCommerce plugin for WordPress. By the end of this lesson, you will understand installation, general store settings, adding and editing products, order management, sales reporting, and the system status report.

## Objectives

After completing this lesson, participants will be able to:

*   Identify multiple ways in which WooCommerce satisfies the needs of an eCommerce retailer.
*   Install the WooCommerce plugin and complete the initial setup wizard.
*   Add and modify products, review orders, and change the store settings.


## Target Audience

Who is this lesson intended for? What interests/skills would they bring? Choose all that apply.

* [X] Users
* [X] Designers
* [ ] Developers
* [ ] Speakers
* [ ] All

## Experience Level

How much experience would a participant need to get the most from this lesson?

* [ ] Beginner
* [X] Intermediate
* [ ] Advanced
* [ ] Any

## Type of Instruction

Which strategies will be used for this lesson plan? Choose all that apply.

* [X] Demonstration
* [ ] Discussion
* [X] Exercises
* [ ] Feedback
* [ ] Lecture (Presentation)
* [X] Show & Tell
* [X] Tutorial

## Time Estimate (Duration)

How long will it take to teach this lesson (in minutes)?

60 minutes

## Prerequisite Skills

Participants will get the most from this lesson if they have familiarity with:


*   Basic knowledge of [installing and activating WordPress plugins](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-plugins/)
*   Basic knowledge of [installing and activating WordPress themes](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-a-theme/)
*   [Managing Media](https://make.wordpress.org/training/handbook/user-lessons/managing-media/)
*   [Categories vs Tags](https://make.wordpress.org/training/handbook/user-lessons/categories-vs-tags/)

## Readiness Questions

*   Are you familiar with the concept of a plugin in WordPress?
*   Do you have a self-hosted WordPress website?
*   Do you have a user role that allows you to install plugins and themes?

## Materials Needed

*   [WooCommerce](https://wordpress.org/plugins/woocommerce/) plugin, version 3.4.4
*   Installation of WordPress, version 4.7 or higher
*   Sample pictures to represent the products: [Phewa lake](/images/phewa.jpg), [Karelian forest](/images/karelia.jpg) (any other may be used)

## Notes for the Instructor


*   The recommended way to approach the scenarios would be to demonstrate and explain the process first, and then ask students to repeat the actions using their own devices, while you’re available for questions and troubleshooting if something doesn’t work out.
*   It is easiest for students to work on a locally installed copy of WordPress. Set some time aside before class to assist students with installing WordPress locally if they need it or, if possible, send them instructions before the class so they come prepared. For more information on how to install WordPress locally, please visit our [Teacher Resources](https://make.wordpress.org/training/teacher-resources/) page.
*   The preferred answer to the screening questions is “yes.” Participants who reply “no” to question 1 might require a bit of explanation, and if they answer “no” to questions 2 & 3 they may be grouped with other students to work in pairs on the installation.
*   You may print out the Example Lesson part to use it as handouts or send it out as a PDF file to keep it green and preserve the links used throughout the document.
*   This lesson is meant to serve as an introduction to using WooCommerce and does not aspire to fully cover its functionality. At the end of the lesson feel free to refer your students to the WooCommerce documentation to help them fine-tune their shops. It will be helpful to demonstrate what the documentation looks like and how to use it.


## Have You Thought About...?

* What if the participant doesn't have the correct version of WordPress and plugin?
* What if the participant's user role doesn't allow to install plugin and theme?
* What if the participant's site is hosted on WordPress.com and doesn't have the access to install plugin and theme?


## Lesson Overview

* Introduction to WooCommerce and its usage
* Installing WooCommerce plugin and setting up the store
* Adding and managing products
* Understanding WooCommerce menu items
* Practice exercises to have participants install the plugin and setup their own e-commerce store


## Exercises

**Add new product**

Practice to add a new product. Participants can use the Karelian forest picture attached in this lesson or other images of the liking.

*   Go to **Products > Add New**
*   Set the attributes of the product to have 3 different sizes: 27x39", 18x11" and 36x54''
*   Set different prices for each of the sizes of the posters

**Change currency**

Practice to change the currency to be accepted by the store.

* Go to **WooCommerce > Settings**.
* At the **General > Currency options**, change the currency to **Malaysian Ringgit (RM)**.

**Add new shipping method**

Practice to add a new shipping method for local pickup.

*   Go to **WooCommerce > Settings > Shipping zones** and click **Edit**
*   Add shipping method for Local pickup
*   Add another shipping method if desired



## Assessment

**Which of the following is NOT a part of WooCommerce core functionality?**

1.  SEO
2.  Reports on sales volume
3.  Coupons management
4.  Orders management

**Answer:** 1\. SEO 

**Which of the following describes a WooCommerce variable product?**

1.  A set of variations on a product, with a random option chosen
2.  A product listed and described at a website but sold from a third-party website
3.  A product that doesn’t require shipping
4.  A set of variations on a product, with control over prices, stock, image, etc.

**Answer:** 4. A set of variations on a product, with control over prices, stock, image, etc 

**Why would you choose to use attributes instead of product categories to categorize items? (select as many options as apply)**

1.  To allow users to search for several parameters simultaneously.
2.  To ensure better SEO
3.  To define some extra pieces of technical information about the product like color, size, weight, etc
4.  To simplify adding new products
5.  To be able to create coupons to provide discounts to the customers based on their geographical location

**Answer:** 1\. To allow users to search for several parameters simultaneously. & 3. To define some extra pieces of technical information about the product like color, size, weight, etc


## Additional Resources

* [WooCommerce blog](https://woocommerce.com/blog/)  is a nice resource to follow for advice
* WooCommerce also offers extensive [documentation](https://docs.woocommerce.com/)  - among the many topics you may want to pay attention to the [Getting started](https://docs.woocommerce.com/documentation/plugins/woocommerce/getting-started/) section



## Example Lesson

### Introduction: What is WooCommerce for?

WooCommerce is an e-commerce plugin for small to large-sized online merchants using WordPress. Some of its important benefits are:

*   The plugin itself is free.
*   It is very flexible, offering a wide range of product options for selling. 
*   It has over 300 free and paid extensions to choose from.
*   The customer data is independent of any third party software platform.
*   WooCommerce is 100% open source. (This allows you to benefit from an active and growing community of contributors.)

During the flow of the lesson, we will be working for an imaginary company called YayWP! which sells large sized photo prints that you might want to use to decorate your home. You will install the WooCommerce plugin, set up the new e-shop, add products to the store, and review the menu options and reports. You will also learn about resources you can study to continue refining your e-shop to suit your needs.

### Setting up the shop

#### Preparation

First, you need to have WordPress (version 4.7 and above) installed. The second step will be to select a theme for the shop look & feel. Generally, it’s best if the theme is built and optimized for WooCommerce (here is [a guide](https://docs.woocommerce.com/document/choosing-the-right-theme/) you can use).

In this lesson, you'll use the [Storefront](https://wordpress.org/themes/storefront/) theme. This is from WooThemes, the creators of WooCommerce. It is designed to build e-commerce websites. Install and activate the theme before you proceed.

> ![(https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)Storefront is the theme WooThemes recommends for use with WooCommerce (it's their theme, after all!). There are plenty of other free and commercial themes optimized WooCommerce. If you don't use a theme designed for WooCommerce, you'll probably have to add code and other modifications to make your store work.

#### WooCommerce Installation

>![(https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)For training purposes, it’s okay to use a local installation of WordPress. For a real-life scenario, you need to be running WordPress on a self-hosted site. It's important to review server requirements before installation. Otherwise, you may encounter issues when using WooCommerce.

1\. You will now perform an automatic install of WooCommerce plugin. Log into your WordPress Dashboard and go to **Plugins > Add New**. In the search field, type “WooCommerce” and click Search Plugins. 

[![Installing WooCommerce](/images/installingwoocommerce.png)](/images/installingwoocommerce.png)

Install the newly found plugin by clicking **Install Now** and activate a plugin when prompted by clicking **Activate**.

2\. Once the plugin is activated you'll see the WooCommerce setup screen. 


#### Onboarding Wizard

An on-boarding wizard will guide you through the installation steps to configure WooCommerce.

1\. **Store Setup**: Enter your store's location, currency accepted and the types of products you plan to sell.

[![Store Setup](/images/storesetup.png)](/images/storesetup.png)

2\. **Payment**: Setup the payment methods used by your shop.

There are two online payment options available, Stripe and PayPal. You must register with your chosen payment method before you can accept payments using their services. To simplify the configuration here, you won't configure the online payment options. Deselect Stripe and PayPal options.

Expand the **Offline Payments** section. Select the **Cash on Delivery** option. Click **Continue.**

[![Payment Options](/images/paymentoptions.png)](/images/paymentoptions.png)

3\. **Shipping**: Set your shipping options. You can include weight and dimension units used to ship your products.

For this demo, we're going to use *Flat Rate* as our shipping method at $5. Turn off the option of *Location not covered by your other zones*. Leave the **Weight unit** and **Dimension unit** configuration as default. Click **Continue** to proceed.

[![Shipping](/images/shipping.png)](/images/shipping.png)

4\. **Recommended**: Shows you the recommended features to be installed for your WooCommerce store. For this demo, we'll select only the **Storefront Theme** option. Click **Continue** to proceed.

[![Shipping](/images/shipping.png)](/images/shipping.png)

5\. Your store is now setup and ready to add your first product! Click **Create a product** button to add a product to your store.

[![Wizard Complete](/images/wizardcomplete.png)](/images/wizardcomplete.png)


### Adding a new product

#### Shop Organization: Categories, product tags, and attributes

Recall that your imaginary client YayWP! is selling large posters. Presumably, YayWP! customers are interested in the thematics and the size of the picture. You will use Product Categories to indicate the thematic. You will also have to manage the sizes available for sale.

**Product categories and tags** are similar to regular post categories and tags. Use product categories for grouping and product tags for details. There are two reasons why you should organize your products by category:

*   The larger the print, the more expensive. So you'll want to be able to set different prices for different sizes. You should use a category for you product and tags to list the different sizes and pricing. This means your picture and all its sizes will be listed as one item. This will make it easier for your customers to find and order the product.
*   A user might want to include both size and thematics as their search parameters simultaneously.

**Variable products** are a product type in WooCommerce. They let you offer a set of variations on a product. You can control prices, stock, image, and more for each variation.

**Attributes** are pieces of data. Use them to add more technical information to a product. This helps users to refine your catalog while browsing/searching. Additionally, attributes are a key component of authoring variable products. 

[![Attributes](/images/attributes.png)](/images/attributes.png)

Go to **WooCommerce > Products > Attributes** section. Add an attribute before you create different variations of the picture. Type in “size” for the attribute name, and click **Add Attribute**.

#### Managing a new variable product

1\. Go to: **Products > Add New**. Adding a product feels like writing a regular post in WordPress, so the view of the form should be familiar.

[![Add new product](/images/addnewproduct.png)](/images/addnewproduct.png)
Fill in the basic data first: name of the product, description, and  product categories as shown in the image above.

2\. Add a product image using the Product Image form (under product tags). You may use a sample picture provided to “sell” it or use some other picture of your liking. This is how an added image appears once you add it: 

[![Add product image](/images/addproductimage.png)](/images/addproductimage.png) 

3\. Now, make the product variable. Select **Variable product** option in the Product Data dropdown list.

>![(https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)Here is a bit more detail about some of the other product options:
>*   A **Simple** product type describes the physical off-line product which requires shipping. A book or a laptop, which do not require variation, are simple products.
>*   A **Virtual** product is a product that doesn’t require shipping. For example, online tarot reading.
>*   A **Downloadable** product is similar to a virtual product. In this instance, the customer is given a file to download. This could be an indie video game.

At the moment, virtual and downloadable products are not present in our list. These aren't included because we have no digital payment method configured.

4\. Click through the first tabs of Product data meta box: **Inventory**, **Shipping**, and **Linked products**. This is where you can add some important data for your products. At the moment, you will skip through them and go straight to setting the product attributes and variations. Open the **Attributes** section. 

[![Set attributes](/images/setattributes.png)](/images/setattributes.png)

5\. Select "size" from the select box, and click **Add**.
>![(https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)By choosing ‘Custom product attribute’ from the select box, you can apply a custom product-level. This will not be available in layered navigation or other products. 

6\. Once you have chosen an attribute and added it, apply the terms attached to that attribute to the product. You can hide the attribute on the frontend of your site by leaving the **Visible on the product page** checkbox unchecked. 

Check both of the checkboxes and click **Add new** to add the values to the poster's available sizes. 

7\. Type in 27x39" and click **OK**. Repeat adding with 18x11" size. 

[![Size attributes](/images/sizeattribute.png)](/images/sizeattribute.png)

8\. Save the entered attributes data by clicking **Save attributes**.

9\. Switch to the **Variations** tab. Make sure **Create variations from all attributes** option is selected and click **Go**. Then click **OK** on the confirmation message pop-up.

10\. You now have two variations for your product. Next, you'll set up how they should be distinguished on your product page. 

[![Variations](/images/variations.png)](/images/variations.png)

Click each of the variation panels. For each combination enter price - $15 for the larger poster and $10 for the smaller one. 

[![Variation prices](/images/variationprices.png)](/images/variationprices.pn)
 
11\. Click **Save changes** when you are finished.

12\. Try to save the product now. Click **Publish** to publish the product. 

### Shop Overview

You now have an operational shop. Take a look by going to the **Shop** page of your site. 

[![Shop overview](/images/shopoverview.png)](/images/shopoverview.png) 

The look is not polished, but the foundation for a great WordPress-based shop is there for you to refine. For example, you can improve your shop by creating custom menus. Once created, you can place them in your theme’s menu areas or in a widgetized area (use the menus widget). 

### WooCommerce menu items

#### Dashboard

The WordPress customizable dashboard is normally the first thing you see when you log in to the site.  After being activated, WooCommerce adds two dashboard widgets you can use for an overview of your store:

*   The **WooCommerce recent reviews** widget displays your store’s most recent reviews.
*   The **WooCommerce Status** widget gives you a quick overview of your store, alerting you if you have a processing order or an order on-hold, or a product is running low on stock. It also displays sales statistics.


[![Dashboard](/images/dashboard.png)](/images/dashboard.png)


#### WooCommerce Menu

Take a look at the other menu sections. 

1\. Use the **Orders** section to view and manage orders. The orders placed by the customers at your shop will be displayed here.

[![Orders](/images/orders.png)](/images/orders.png)

2\. The **Coupons** section allows giving discounts by creating coupons that can be applied by customers on the checkout page. 

[![Coupons](/images/coupons.png)](/images/coupons.png)

3\. In the **Reports** section, you can view data on the store activity and export it as a .csv file. 

[![Reports](/images/reports.png)](/images/reports.png)

4\. The **Settings** section contains all the settings that you briefly explored when setting up the shop: general store settings, products settings, shipping, payments and more.

[![Settings](/images/settings.png)](/images/settings.png)

5\. **Status** provides an overall snapshot of your setup, as well as potential conflicts, and is mostly used for troubleshooting on your own or when contacting support. 

[![Status](/images/status.png)](/images/status.png)

6\. The **Extensions** section is where you can browse for additional plugins and extensions to extend the functionality and features of your store.

[![Extensions](/images/extensions.png)](/images/extensions.png)

#### Products Menu

 This top-level menu has sections relating to managing products. This lesson used the **Products** and **Attributes** sections earlier. There are additional sections to modify, add, and delete product **Categories** and **Tags.** 
 
[![Products](/images/products.png)](/images/products.png)

>![(https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png)Click on the star in the product listing to make the product "featured".


### Lesson Wrap Up

![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) Follow with the Exercises and Assessment outlined above.










