---
layout: default
title: How to use
nav_order: 1
has_children: true
has_toc: false
parent: Stock Management section
permalink: /stock-management-section/how-to-use
---

# How to use
{: .no_toc }

1. TOC
{:toc}

---

## How to use the screen
The whole screen contained from the header, filtering and the list of the items. The user can filter the items with filtering options in the <span class="text-grey-dk-100">**grey boxes**</span>. Under the filtering options is the option to filter the items by direct input of the phrase. The list of results is displayed under this direct input. On the right side of every item is displayed the button with the option to set the item as <span class="text-green-200">**"IN STOCK"**</span> or <span class="text-red-200">**"OUT OF STOCK"**</span>. The user can scroll faster on the list with the **fast scroller**.

To set the availability of the item, the user can do that by clicking on the button:
- if <span class="text-green-200">**"SET ITEM AS IN STOCK"**</span> button is displayed, by clicking on it, the dialog with the list of options will be displayed:
	- {% include icon.html name="call_made" %} **"Set item as out of stock"** - the application will contact the server and set that that **item is not available** and can't be used during creating of the new order
	- {% include icon.html name="access_time" %} **"Set item as out of stock + time"** - a new dialog will be prompted, where the user needs to set up the **date** and **time** till when the item will be **not available**
- if <span class="text-red-200">**"SET OUT AS OUT OF STOCK"**</span> button is displayed - click on this button will contact the server and set that that **item is available** for the ordering purposes

## Description of the Stock management screen
Here is the description of the screen:
1. **Menu icon** - opening the menu with all application sections
1. **Name of the section** - Kitchen section is the default one, but you could select another section through **Menu icon**
1. **Internet connection indicator** - <span class="text-green-200">**the green circle**</span> is indicating, that the network is stable and the application is successfully connected to the server. <span class="text-red-200">**The red circle**</span> will display, once the internet is not available.
1. **Number of results** - the amount of items, which are displaying in the list
1. **Filter options** - **CHANGES**, **ITEM TYPES**, **SELECTED STORE** or **SELECTED BRAND**
1. **Fastscroller** - By long-click down on the fastscroller, the cook can reach the items more quickly. At the same time, the name of the item that is currently displayed is displayed as preview information.
1. **Icon for availability status of the item**
1. **Name of the item**
1. **Restaurant name** - the name of the restaurant, where this item is setup. The item by itself could belong to multiple stores, but changing stock status will change only under the specifically mentioned restaurant
1. **Brand name** - the name of the brand, under which the item is setup. If the item belongs under multiple brands, changing the stock status will change it only for this brand
1. **Item type** - the item could be one of the types: **meals**, **deals**, **meals with variable price**, **pizzas**, **pizza deals** or **additions**
1. **Price of the item**
1. **Button for changing availability status** - usage as mentioned [above](#how-to-use-the-screen)

{% include img.html name="section_stock_management_2.png" %}

{% include img.html name="section_stock_management_5.png" %}

{% include img.html name="section_stock_management_7.png" %}

{% include img.html name="section_stock_management_8.png" %}

{% include img.html name="section_stock_management_9.png" %}

{% include img.html name="section_stock_management_10.png" %}
