---
layout: default
title: Dictionary of Terms
nav_order: 1
has_toc: false
parent: Frequently asked questions (FAQ)
permalink: /frequently-asked-questions-faq/dictionary-of-terms
---

# Dictionary of Terms
{: .no_toc }

---

- <span class="text-red-200">**delivery order**</span> - orders created on the principle of delivering food to a customer at a specific address by courier
- <span class="text-red-200">**collection order**</span> - orders were created by the customer, who is going to pick up cooked+prepared food on the store
- <span class="text-red-200">**store order**</span> - a customer eats food in the restaurant
- <span class="text-red-200">**store/restaurant**</span> - the place/building, where is the food cooked/prepared for the customer
- <span class="text-red-200">**dark/cloud kitchen**</span> - the restaurant that has no physical space and no dine-in or takeaway facility as it does not exist as a restaurant of any sort. One restaurant could contain multiple brands (see below), which are creating a **cloud kitchen** functionality
- <span class="text-red-200">**brand**</span> - specific menu for the company, for instance. 
	- company (named "Sumo food") is preparing _sushi_ -> **Sumo food brand**
	- company (named "Burgerbrat") is preparing _meat food_ -> **Burgerbrat brand**
	- company (named "Meat.ly") is preparing _Mexican food_ -> **Meat.ly brand**
	- this 3. brands can coexist under one restaurant (principle of **Dark/Cloud kitchen**)
- <span class="text-red-200">**item**</span> - a general description of one or more meals, which are divided according to several types
	- <span class="text-red-200">**item category**</span> - a category that may contain any type (single or multiple) of the meal, deal, a meal with a variable price, etc.. A category may contain subcategories. The depth of this tree structure can be multiple times.
	- <span class="text-red-200">**meal**</span> - food that includes price, tax, quantity change, etc.
	- <span class="text-red-200">**meal with a variable price**</span> - food that differs from **meal** only in that it has a dynamically adjustable price depending on e.g. weight (eg ham, salami, fish, etc.).
	- <span class="text-red-200">**deal**</span> - the combination of one or more **meals**, **categories**, **pizzas** or **1/2 pizzas** in which it is not possible to change the quantity for its individual meals and the price of the resulting **deal** is calculated according to the set **pricing strategy**
	- <span class="text-red-200">**pizza**</span> - we can also call it "Make Your Own Pizza". The customer has the possibility to create the pizza in three steps, most often it is "Type of dough" (garlic, cheese), "Basis for pizza" (ketchup, cream) and specific "Type of pizza" (like Hawai, vegan). Subsequently, he can add **additions** or remove **ingredients**.
	- <span class="text-red-200">**pizza deal or 1/2 pizza**</span> - a type of item similar to **pizza**, but it is possible to make a half pizza of one type (like Hawai) and half pizza of another type (like Salami), where the final price of the pizza deal is calculated based on the **pricing strategy** setup on the pizza deal
	- <span class="text-red-200">**addition**</span> - topping that can be additionally added to an item of a certain type (**food**, **food with variable price**, **pizza**, **1/2 pizza**)
	- <span class="text-red-200">**ingredient**</span> - topping that is already on the food and can be removed after the customer's request. Depending on the type of food, the final price of the food decreases or remains the same (the price is calculated according to the **pricing strategy**)
- <span class="text-red-200">**driver, courier**</span> - a person delivering an order with a prepared meal to a customer
- <span class="text-red-200">**cooked state for food**</span> - once when the food is cooked and ready for the packaging/final preparation process 
- <span class="text-red-200">**prepared state for food**</span> - the moment when the food is packaged and ready for handover to the customer at the point of delivery or at the store
- <span class="text-red-200">**tag**</span> - a user in our system can create tags, these tags can be set up on one or more items. It is also possible to set these tags to the **category** to which these **items** are assigned, then all **items** in this **category** will inherit these **tags** from the **category**. These tags are useful in the Kitchen application logic, where the chef can filter certain foods through these tags. For example, a tag called **Hamburgers** has been created that has been set to the **category** in which each burger is offered, or to each burger separately. Consequently, if this tag is set to filter, only the orders and individual meals to which this tag belongs will be displayed.
- <span class="text-red-200">**"Kitchen hide" tag**</span> - This special type of tag is used to hide items that a cook doesn't need to see in a kitchen application. For example, the chef does not need to prepare "Drinks" or "Packs" dishes, so this tag will be set to these "Items" in the menu and will not be displayed in the Kitchen application [(if this setting is enabled)]({{site.baseurl}}{% link docs/list-of-settings/data-section/hide-items-with-kitchen-hide-tag.md %}). At the same time, these items are set in the system that they have been cooked and also prepared.
- <span class="text-red-200">**partner system ID**</span> - a unique text identifier created in our system that is transferable to external integration
- <span class="text-red-200">**public system ID**</span> - a unique external text identifier that was created in an external integration
- <span class="text-red-200">**creator of the order**</span> - the system in which the order was created. E.g. in the case of **"System"** as the creator, it means that the order was created in the Orderlord Android cashier system or via a web dashboard. Else the creator is an external integration.
- <span class="text-red-200">**receipt**</span> - printed paper that is handed over to the customer and contains information about the restaurant, the customer, individual items, the total price of the order with additional pricing information, a list of taxes applied to each item, etc.
- <span class="text-red-200">**kitchen receipt**</span> - printed paper, which, unlike a traditional **receipt**, contains only simplified order information and a list of individual meals. This block is mostly used for kitchen purposes if the cook needs to see the order information in printed form, respectively. for the purpose of reviewing the content of the order
- <span class="text-red-200">**label**</span> - a special type of paper that is attached to individual packs of food. These labels contain information about the items from the order, with each item being printed separately on **one label**.
- <span class="text-red-200">**prepare order**</span> - each **item** in the order will be flagged as being **cooked** and/or **prepared** [(depending on the station profile settings)]({{site.baseurl}}{% link docs/list-of-settings/data-section/station-profile.md %}).
- <span class="text-red-200">**finish order/collect order**</span> - if the order was handed over to the customer by courier, at the store, or the customer has completed the order for a restaurant order, the order is **finished** (**collected**)
- <span class="text-red-200">**cancel the order**</span> - if the order could not be delivered to the customer (eg, the customer was not enough, canceled by the customer, test order, etc.), the order can be canceled.
- <span class="text-red-200">**account settings**</span> - each account in the system has settings associated with it. These settings customize each option, allow functionality in applications as well as use applications themselves, enable integrations, etc.
- <span class="text-red-200">**menu**</span> - a menu associated with a restaurant that may contain **items** of different types.
- <span class="text-red-200">**user settings**</span> - if the user has assigned the **"kitchen manager"** permission, he can set which settings in the Kitchen application will generally be disabled for editing by other users without this permission and persists the value of this setting in the Kitchen application for every user. This way, you can prevent certain settings from being changed by a user who does not have application settings.
- <span class="text-red-200">**time slot**</span> - during order creation it is possible to assign orders to so-called **"time slots"**. These **slots** can have a fixed start time when the section begins, the end time of cooking in the kitchen, and the subsequent end time of delivery of the order or handover of the order to the customer in the restaurant. It is also possible to set the maximum number of orders that can be assigned to given **slots**. These **time slots** can also be used to filter orders in a Kitchen application [(as a setting)]({{site.baseurl}}{% link docs/list-of-settings/data-section/group-by-time-slots.md %})
- <span class="text-red-200">**item description**</span> - additional information for the item, mostly describing raw materials or the recipe of the meal
- <span class="text-red-200">**item cook time**</span> - information preparation time, which is used for [the auto-preparation logic]({{site.baseurl}}{% link docs/list-of-settings/data-section/auto-prepare-orders.md %})
- <span class="text-red-200">**"Cook" permission**</span> -  the user needs to have enabled this permission for using the Kitchen application
- <span class="text-red-200">**"Kitchen manager" permission**</span> - if the user wanted to share the same settings with the another users, then he needs to have enabled this permission
- <span class="text-red-200">**default delivery time**</span> - the interval of delivery orders, from which the orders will be visible
- <span class="text-red-200">**default collection time**</span> - the interval of collection orders, from which the orders will be visible
- <span class="text-red-200">**default store time**</span> - the interval of store orders, from which the orders will be visible
- <span class="text-red-200">**order deadline buffer**</span> - is the extra time for the cook that is added for every order of the type {% include icon.html name="motorcycle" %} delivery (collection and store orders has 0 mins.)