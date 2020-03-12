---
layout: default
title: Filtering the orders by tags
nav_order: 9
has_children: false
has_toc: false
parent: Getting Started
permalink: /getting-started/filtering-the-orders-by-tags
---

# Filtering the orders by tags
{: .no_toc }

1. TOC
{:toc}

---

## Description
If the user needs to see only the meals of specific types, then he needs to use tags filtering functionality. We have in our menu 5 categories:
1. _pizza category_ - Margherita, Hawai, Vegan
1. _pasta category_ - Carbonara, Lasagne, Ravioli
1. _pastry category_ - Pie, Strudel, Pretzel
1. _sushi category_ - Maki, Sake, Hamachi
1. _drinks category_ - Cola, Juice, Wine, Coffee

Let's say, that he makes **pizza**, **pasta** and **pastry** meal types. These 3 tags will be created and set up on the menu. That means, that the specific tag (for instance **pizza**) will be applied on every _pizza_ (Margherita, Hawai, Vegan) under the _pizza category_. But this procedure could take a while, so for this purpose, setup this tag on the _pizza category_ by itself will speed up this process. The same process for the **pasta** and **pastry** tag applied to the _pasta category_ and _pastry category_. Once the menu is set up, these tags could be filtered in the kitchen application.

## How to do that?
- setup the menu appropriate for your purposes
- in the kitchen application, **update the menu** to the latest in [**the settings section**]({{site.baseurl}}{% link docs/getting-started/update-the-data.md %})
- find [**Tags filtering setting**]({{site.baseurl}}{% link docs/list-of-settings/data-section/tags-filter.md %}) in the settings section
- select the tags, that the cook should see only. You could select also a combination of multiple tags.
- in the **Kitchen screen** section should be visible only meals that have added this tag/tags.


## Warning
Order status **ready** for the whole order isn't set up automatically, because it could happen, that you don't have to see all meals for the order. This **ready** status is indicating the manager in the **Web Dashboard** or in the **Point of Sale Android Application** that all meals are <span class="text-orange-200">**cooked**</span> + <span class="text-green-200">**prepared**</span> and could be delivered (it has just an informative purpose). With the combination of multiple devices with kitchen application, you could achieve, that the order with all meals will be _processed_ properly by cooks.

{% include img.html name="getting_started_filtering_the_orders_by_tags_1.png" %}

{% include img.html name="getting_started_filtering_the_orders_by_tags_2.png" %}