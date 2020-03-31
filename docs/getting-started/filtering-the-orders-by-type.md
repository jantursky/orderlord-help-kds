---
layout: default
title: Filtering the orders by type
nav_order: 8
has_children: false
has_toc: false
parent: Getting Started
permalink: /getting-started/filtering-the-orders-by-type
---

# Filtering the orders by type
{: .no_toc }

1. TOC
{:toc}

---

## Description
The cook has the option to dynamically filter the orders by order type, if it's {% include icon.html name="motorcycle" %} delivery orders, {% include icon.html name="room_service" %} collections orders or {% include icon.html name="store" %} store orders.

## How to do that?
- by clicking on the specific order type, will trigger a dynamic filter for orders
- if the order type has <span class="text-grey-dk-400">**black color**</span>, that means that this type of orders will be displayed
- <span class="text-grey-dk-000">**grey color**</span> means skipping orders of those specific types, and they will be not displayed
- the cook can't disable all order types, because they will be not displayed any results 

## Warning
Depending on the allowed order types from [**the settings section**]({{site.baseurl}}{% link docs/list-of-settings/data-section/order-types.md %}), specific order types will be displayed at all.

{% include img_tablet.html name="view_list_6_v3.png" %}

{% include img_tablet.html name="view_list_8_v2.png" %}
