---
layout: default
title: How to use the kitchen screen
nav_order: 3
has_children: false
has_toc: false
parent: Getting Started
permalink: /getting-started/how-to-use-the-kitchen-screen
---

# How to use the kitchen screen
{: .no_toc }

1. TOC
{:toc}

---

## Description of the Kitchen screen
Once the user is logged into the application, the **Kitchen section** is displayed. Here is the description of the screen:
1. **Menu icon** - opening the menu with all application sections
1. **Name of the section** - Kitchen section is the default one, but you could select another section through **Menu icon**
1. **Internet connection indicator** - <span class="text-green-200">**the green circle**</span> is indicating, that the network is stable and the application is successfully connected to the server. <span class="text-red-200">**The red circle**</span> will display, once the internet is not available.
1. **User email** - email of the logged user
1. **Number of items in the list** - Meals are calculated from the list of displayed meals, depending on the number of individual meals
1. **Total orders** - number of total orders, even the late and future orders
1. **Late orders** - the order will be late when the order preparation time exceeds the current device time
1. **Future orders** - the order is in the future state when his preparation (finishes) time is higher the restaurant's interval time for delivery/collection or store orders
1. **Delivery orders** - {% include icon.html name="motorcycle" %} amount of delivery orders in the list
1. **Collection orders** - {% include icon.html name="room_service" %} amount of collection orders in the list
1. **Store orders** - {% include icon.html name="store" %} amount of store orders in the list
1. **Fastscroller** - By long-click down on the fast scroller, the cook can reach the orders more quickly. At the same time, the order ID that is currently displayed is displayed as preview information.
1. **Unfinished order/orders above/below** - this <span class="text-blue-100">**blue button**</span>, which is displaying on the top/bottom off the screen is informing, that below in the list is already started order in the cooking/preparing status, but not finished.
1. **Device time** - current time of the device (clock time)
1. **Last update** - information about last updated time of deliveries and orders from the server

{% include img.html name="view_list_4.png" %}

{% include img.html name="how_to_use_kitchen_screen_1.png" %}

## Description of the information in the list
1. **New orders/Table number/Specific delivery** - header informing about a group of orders which belong to the specific delivery, under the same table or aren't assigned.
1. **Finishing order's time** - time, when the order should be finished (delivered to the customer), handed over the customer in the store once he will arrive or finished the order for the customer in the store.
1. **Order type icon** - determining if the order is **delivery order** {% include icon.html name="motorcycle" %}, **collection order** {% include icon.html name="room_service" %} or **store order** {% include icon.html name="store" %}
1. **Order counter** - internal counter of the order in the system. The counter is starting from **001** from the beginning of the day. Every other order has increased counter.
1. **Timed order** - red indicator <span class="text-red-200">**!**</span>, which is used for the purposes, if the customer wants his order to be delivered/finished in the specific time.
1. **Name of the item** - the item could be **a meal**, **a meal with variable price** or **pizza**
1. **Quantity of the item** - how many pieces of this item are ordered
1. **Cooked/prepared quantity** - how many pieces of this item are <span class="text-orange-200">**cooked**</span>/<span class="text-green-200">**prepared**</span> depending on the colored circle
1. **Cooked/prepared indicator** - <span class="text-orange-200">**cooked**</span> or <span class="text-green-200">**prepared**</span> indicator
1. **Item note** - additional note added to the item
1. **Item's additions** - additional additions added to the item also with the added quantity
1. **Item's ingredients** - additional ingredients removed from the item
1. **Cooked label** - <span class="text-orange-200">**this orange label**</span> indicated, that the specific meal was cooked in the kitchen
1. **Prepared label** - <span class="text-green-200">**this green label**</span> indicated, that the specific meal was prepared in the kitchen

{% include img.html name="how_to_use_kitchen_screen_1_v2.png" %}

{% include img.html name="how_to_use_kitchen_screen_2.png" %}

{% include img.html name="how_to_use_kitchen_screen_3.png" %}

## How to use the Kitchen screen
1. Once the orders with food, which need to be cooked/prepared, is displayed in the list, the user could start to cook/prepare the food. At this moment, you don't need to click on anything. At the moment when you, as the user in charge of cooking food (in this case **"Chicken"**), have the food <span class="text-orange-200">**cooked**</span>, you can click on the row with that food. If you have <span class="text-orange-200">**cooked**</span> all the quantity of this food (in this case **"Chicken"**, for instance, if there is **0/3**), then you could click as many times on the row, as you have <span class="text-orange-200">**cooked**</span> this specific food (let's say **3x**). The status of this item will be set as it is <span class="text-orange-200">**cooked**</span> and the orange label will display on the right side.

1. Once the meal is <span class="text-orange-200">**cooked**</span>, the user could start to <span class="text-green-200">**prepare**</span> the meal (packed it for the customer, prepare to serve the customer). The same principle as for <span class="text-orange-200">**cooked**</span>, click on the row as many times, as the meal has quantity.

1. You could this <span class="text-orange-200">**cooked**</span>/<span class="text-green-200">**prepared**</span> status do for multiple foods simultaneously. If you have <span class="text-orange-200">**cooked**</span>/<span class="text-green-200">**prepared**</span> the whole quantity of the item (in this case **"Chicken"**), you don't need to click on the row as many times as it has the quantity (for instance, for 6 pieces of **"Chicken"**, you'll need to click on the row 6 times.). You could do it by only **one click** - the only thing you need, is to click on the right side with the icon {% include icon.html name="skip_next" %}. Once you click on this _right block of the row_, the meal (in this case **"Chicken"**) is set up as <span class="text-orange-200">**cooked**</span>, when you click on this _block_ second time, the meal will be set up as <span class="text-green-200">**prepared**</span>.

1. When are all meals for the order <span class="text-orange-200">**cooked**</span>/<span class="text-green-200">**prepared**</span>, the whole order is hidden, and set up as ready for the manager or courier. If you need to set up the triggering of printing labels, [check this section]({{site.baseurl}}{% link docs/printers/label-printer/label-printer.md %}).

1. If there is a need to go back a step back in the preparation of food, there are two options:
	- click on the _left block of the row_
	- **or** _long click_ on the whole row
	- the new dialog with the options will be displayed. On this dialog you are able to:
		- {% include icon.html name="restore" %} **Reset food state to cooked** - setup the meal as cooked, removed prepared status
		- {% include icon.html name="restore" %} **Reset food state** - setup the meal as not touched, removed cooked and prepared status
		- {% include icon.html name="settings_backup_restore" %} **Reset order** - the status of all meals for this orders will be set as not touched (zero state) + ready status of the order will be removed. This row is displaying <span class="text-red-200">only if this action is enabled for the account in the account settings (handled by the administrator of the account).</span>
		- {% include icon.html name="cancel" %} **Cancel order** - the order will be canceled, and will be dismissed from the application. This row is displaying only if this action is enabled for the account in the account settings (handled by administrator of the account).
		- {% include icon.html name="label" %} **Print label** - communication with the label printer will be created and try to print the **label** (single or multiple by the quantity of the meal, [depending on the setting]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/label-quantity.md %}). This option is displayed only if the label printer is set up in the settings section and depending on the meal cooked/prepared status.
		- {% include icon.html name="receipt" %} **Print receipt** - communication with the receipt printer will be created and try to print the **receipt** and **kitchen receipt**. This option is displayed only if the receipt printer is set up in the settings section.
		- {% include icon.html name="visibility" %} **Preview receipt** - a new screen will be displayed with the preview of the receipt, which should be printed. The look of the resulting receipt is only approximate, depending on the specific vendor and model of the receipt.
		- {% include icon.html name="visibility" %} **Preview kitchen receipt** - same as the **Preview receipt**, but will display kitchen receipt.

{% include img.html name="how_to_use_kitchen_screen_1_v3.png" %}

{% include img.html name="how_to_use_kitchen_screen_2_v3.png" %}

{% include img.html name="how_to_use_kitchen_screen_3_v3.png" %}

{% include img.html name="view_list_9.png" %}

{% include img.html name="view_list_10.png" %}

{% include img.html name="view_list_11.png" %}

{% include img.html name="view_list_5.png" %}