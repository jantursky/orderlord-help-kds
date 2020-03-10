---
layout: default
title: Filtering the orders by brands
nav_order: 10
has_children: false
has_toc: false
parent: Getting Started
permalink: /getting-started/filtering-the-orders-by-brands
---

# Filtering the orders by brands
{: .no_toc }

1. TOC
{:toc}

---

## Description
The cook could work in the contept of **dark/cloud kitchen**. In this case, he is working under one roof with another cooks, who are focusing on the orders only for his brand. This **kitchen** combine multiple brands, where the cook/cooks from this brand company is cooking meals only for his brand. For example, the restaurant is called **"Test store"** which combine these 3 brands:
- company (named "Sumo food") is preparing _sushi_ -> **Sumo food brand** - cook **1.**
- company (named "Burgerbrat") is preparing _meat food_ -> **Burgerbrat brand** - cook **2.**
- company (named "Meat.ly") is preparing _mexican food_ -> **Meat.ly brand** - cook **3.**

So even if the cook **1.** belongs to the restaurant **"Test store"**, he is going to cook the meal for orders only for **Sumo food brand**.

## How to do that?
- setup the menu, setup multiple brands (in this case 3) and attach this 3 brands to the store **"Test store"**
- in the kitchen application, **update the menu** and **brands** to the latest in [**the settings section**]({{site.baseurl}}{% link docs/getting-started/update-the-data.md %})
- find [**Brands filtering setting**]({{site.baseurl}}{% link docs/list-of-settings/data-section/tags-filter.md %}) in the settings section
- select the brands, that the cook should see only. You could select also combination of multiple brands.
- in the **Kitchen screen** section should be visible only orders that belongs to the selected brand/brands

{% include img.html name="getting_started_filtering_the_orders_by_brands_1.png" %}

{% include img.html name="getting_started_filtering_the_orders_by_brands_2.png" %}
