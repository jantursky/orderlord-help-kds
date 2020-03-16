---
layout: default
title: View type
nav_order: 2
parent: Design section
grand_parent: List of Settings
has_toc: false
permalink: /list-of-settings/design-section/view-type
---

# View type
{: .no_toc }

1. TOC
{:toc}

---

## Description
Adjust the design of the list. The orders and meals, that are displayed are displayed always the same for every view type. The difference could be only in the way, how this information are displayed (layout) or how they are grouped together. But the filters applied from another [setting section]({{site.baseurl}}{% link docs/list-of-settings/data-section/data-section.md %}), are used for every view type

## Where to find the option
{% include locate_option.html category_icon="palette" category_name="Design" option_icon="line_style" option_name="View type" %}

{% include img.html name="settings_view_type_1.png" %}

{% include img.html name="settings_view_type_2.png" %}

## The list of options
- **Vertical List View** - the list layout. Description of the design:
	{% include data_info/data_info_new_orders_table_number_specific_delivery.html %}
	{% include data_info/data_info_finishing_orders_time.html %}
	{% include data_info/data_info_order_type_icon.html %}
	{% include data_info/data_info_order_counter.html %}
	{% include data_info/data_info_timed_order.html %}
	{% include data_info/data_info_name_of_the_item.html %}
	{% include data_info/data_info_quantity_of_the_item.html %}
	{% include data_info/data_info_cooked_prepared_quantity.html %}
	{% include data_info/data_info_cooked_prepared_indicator.html %}
	{% include data_info/data_info_item_note.html %}
	{% include data_info/data_info_items_additions.html %}
	{% include data_info/data_info_items_ingredients.html %}
	{% include data_info/data_info_cooked_label.html %}
	{% include data_info/data_info_prepared_label.html %}

{% include img.html name="view_list_6_v2.png" %}

- **Vertical List View + Quick Collect Panel** - some descriptions are same as for [Vertical List View](#the-list-of-options). Description of the rest:
	{% include data_info/data_info_quick_collect_panel.html %}
	{% include data_info/data_info_show_in_pos.html %}
	{% include data_info/data_info_collect.html %}
	{% include data_info/data_info_revert_foods.html %}
	{% include data_info/data_info_highlight.html %}
	{% include data_info/data_info_orders_cooked_prepared_status.html %}

{% include img.html name="view_list_quick_collect_1.png" %}

- **Vertical List View + Food summary** - some descriptions are same as for [Vertical List View](#the-list-of-options). Description of the rest:
	{% include data_info/data_info_food_summary_panel.html %}
	{% include data_info/data_info_food_cooked_prepared_icon.html %}

{% include img.html name="view_list_food_summary_1.png" %} 

- **Food summary** - this view is displaying only the group of all meals for all orders, which will be displayed if the list on the right side will be displayed. Description of the design:
	{% include data_info/data_info_quantity_of_all_meals.html %}
	{% include data_info/data_info_name_of_the_meal.html %}
	{% include data_info/data_info_total_quantity_of_cooked_meals.html %}
	{% include data_info/data_info_total_quantity_of_prepared_meals.html %}

{% include img.html name="view_food_summary_1.png" %}

- **Grid View** - this view is displaying orders in the grid view. Every order is stacked from left to the right, once it reached the end of the line, jumps to the next row, again from left to right. If the order has more item than is the height of the grid **block**, then the rest items are displaying in the next block on the right. Description of the design:
	{% include data_info/data_info_finishing_orders_time.html %}
	{% include data_info/data_info_order_type_icon.html %}
	{% include data_info/data_info_order_counter.html %}
	{% include data_info/data_info_name_of_the_item.html %}
	{% include data_info/data_info_quantity_of_the_item.html %}
	{% include data_info/data_info_cooked_prepared_quantity.html %}
	{% include data_info/data_info_cooked_prepared_indicator.html %}
	{% include data_info/data_info_cooked_label.html %}
	{% include data_info/data_info_prepared_label.html %}
	{% include data_info/data_info_continuous_information.html %}

{% include img.html name="view_gridview_1.png" %}

- **Columns View** - the design is almost the same as for **Grid View** (also for the description). The only difference is in the continuity of the next order. For this view, every order is not displayed in the next _block_, but in the same column, right under the last order. Once the next order reach the end of the column, it will be automatically displayed in the next column on the right side. 

{% include img.html name="view_columns_1.png" %}

- **Grid View with Categories** - the meals are grouped by the category from the menu, where this item belongs. Once the meal is the same from multiple orders, this meal will be grouped into one meal, but with increased <span class="text-orange-200">**cooked**</span>/<span class="text-green-200">**prepared**</span> status. Description of the design:
	{% include data_info/data_info_name_of_the_menu_category.html %}	
	{% include data_info/data_info_name_of_the_item.html %}
	{% include data_info/data_info_quantity_of_the_item.html %}
	{% include data_info/data_info_cooked_prepared_quantity.html %}
	{% include data_info/data_info_cooked_prepared_indicator.html %}
	{% include data_info/data_info_cooked_label.html %}
	{% include data_info/data_info_prepared_label.html %}

{% include img.html name="view_gridview_with_categories_1.png" %}

