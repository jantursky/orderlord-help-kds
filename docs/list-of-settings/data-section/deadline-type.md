---
layout: default
title: Deadline type
nav_order: 4
parent: Data section
grand_parent: List of Settings
has_toc: false
permalink: /list-of-settings/data-section/deadline-type
---

# Deadline type
{: .no_toc }

1. TOC
{:toc}

---

## Description
Select the time format for each order in the list

## Where to find the option
{% include locate_option.html category_icon="label" category_name="Data" option_icon="timer" option_name="Deadline type" %}

## List of options
- **Time** - the time of the order, when the order should be finished (e.g. delivered to the customer)
- **Cound Down** - the difference time between current time and the order deadline (finished) time. For a more simple understanding, let's say that:
	- **current time** is **12:05**
	- **order deadline time** is **13:30**
	- the formula will be **(12:05 - 13:30) = +85 mins.** will be displayed. **+ plus** sign is because the current time is lower that order deadline time, else will be **- minus** sign.
- **Count Up** - formula is **((current time + deadline restaurant time - additional time for the kitchen) - order deadline time)**. For a more simple understanding, let's say that:
	- **current time** is **12:05**
	- **deadline restaurant time** is 45 minutes for {% include icon.html name="motorcycle" %} delivery orders, 30 mins. for {% include icon.html name="room_service" %} collection orders and 55 mins. for {% include icon.html name="store" %} store orders. In this case, the order is **delivery type**, so **45 mins.**
	- **additional time for the kitchen** is the extra time for the cook that is added for every order of the type {% include icon.html name="motorcycle" %} delivery (collection and store orders has 0 mins.), to cook and prepare the meal in time. In this case, the additional time is **15 mins.**
	- **order deadline time** is **13:30**
	- the formula will be **((12:05 + 45 mins. - 15 mins.) - 13:30) = 12:35 - 13:30 = -55 mins.** will be displayed

{% include img.html name="settings_deadline_type_1.png" %}

{% include img.html name="settings_deadline_type_2.png" %}

{% include img.html name="settings_deadline_type_3.png" %}

{% include img.html name="settings_deadline_type_4.png" %}

{% include img.html name="settings_deadline_type_5.png" %}
