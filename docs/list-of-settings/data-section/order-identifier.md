---
layout: default
title: Order identifier
nav_order: 21
parent: Data section
grand_parent: List of Settings
has_toc: false
permalink: /list-of-settings/data-section/order-identifier
---

# Order identifier
{: .no_toc }

1. TOC
{:toc}

---

## Description
Set what type of ID to show for each order

## Where to find the option
{% include locate_option.html category_icon="label" category_name="Data" option_icon="text_fields" option_name="Order identifier" %}

## List of options
1. **Order number** - called order counter, internal counter of the order in the system. The counter is starting from **001** from the beginning of the day. Every other order has increased counter.
1. **Partner system ID** - a unique text identifier created in our system that is transferable to external integration
1. **Public system ID** - a unique external text identifier that was created in an external integration. If the <span class="text-red-200">ID is red color</span>, means that the order hasn't assigned public ID, and only 5 last digits of **Partner system ID** are showing

{% include img_tablet.html name="settings_order_identifier_1.png" %}

{% include img_tablet.html name="settings_order_identifier_2.png" %}

{% include img_tablet.html name="settings_order_identifier_3.png" %}

{% include img_tablet.html name="settings_order_identifier_4.png" %}

{% include img_tablet.html name="settings_order_identifier_5.png" %}
