---
layout: default
title: PIN functionality
nav_order: 13
parent: Data section
grand_parent: List of Settings
has_toc: false
permalink: /list-of-settings/data-section/pin-functionality
---

# PIN functionality
{: .no_toc }

1. TOC
{:toc}

---

## Description
How to organize deliveries and orders in the list

## Where to find the option
{% include locate_option.html category_icon="label" category_name="Data" option_icon="move_to_inbox" option_name="PIN functionality" %}

## List of options
1. **Disabled** - ordered by:
	1. **priority of the order**
	1. else by **deadline of the order**
1. **By orders** - ordered by:
	1. **orders, where was started cooking/prepared process**
	1. else by **priority of the order**
	1. else by **deadline of the order**
1. **By deliveries + time** - ordered by:
	1. **orders, where deliveries aren't unassigned or is store order**
	1. else by **delivery was started because at least one order has started cooking/prepared process**
	1. else by **lowest deadline of the orders per delivery**
	1. else by **everything else except unassigned orders**
	1. else by **priority of the order**
	1. else by **deadline of the order**
1. **By deliveries + position of the order in delivery** - ordered by:
	1. **orders, where deliveries aren't unassigned or is store order**
	1. else by **delivery was started because at least one order has started cooking/prepared process**
	1. else by **lowest deadline of the orders per delivery**
	1. else by **everything else except unassigned orders**
	1. else by **ordering of the orders in the delivery**
	1. else by **priority of the order**
	1. else by **deadline of the order**
1. **By deliveries + unique delivery id + position of the order in delivery** - ordered by:
	1. **orders, where deliveries aren't unassigned or is store order**
	1. else by **delivery was started because at least one order has started cooking/prepared process**
	1. else by **lowest deadline of the orders per delivery**
	1. else by **everything else except unassigned orders**
	1. else by **delivery ID**
	1. else by **ordering of the orders in the delivery**
	1. else by **priority of the order**
	1. else by **deadline of the order**

{% include img_tablet.html name="settings_pin_functionality_1.png" %}

{% include img_tablet.html name="settings_pin_functionality_2.png" %}
