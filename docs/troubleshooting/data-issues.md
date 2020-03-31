---
layout: default
title: Data issues
nav_order: 4
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/data-issues
---

# Data issues
{: .no_toc }

1. TOC
{:toc}

---

## No orders
Check if any of these options are causing this issue:
- [Limit for old orders]({{site.baseurl}}{% link docs/list-of-settings/data-section/limit-for-old-orders.md %})
- [Limit for future orders]({{site.baseurl}}{% link docs/list-of-settings/data-section/limit-for-future-orders.md %})
- [Station profile]({{site.baseurl}}{% link docs/list-of-settings/data-section/station-profile.md %})
- [Order types]({{site.baseurl}}{% link docs/list-of-settings/data-section/order-types.md %})
- [Tags filter]({{site.baseurl}}{% link docs/list-of-settings/data-section/tags-filter.md %})
- [Brands filter]({{site.baseurl}}{% link docs/list-of-settings/data-section/brands-filter.md %})
- [Hide items with Kitchen hide tag]({{site.baseurl}}{% link docs/list-of-settings/data-section/hide-items-with-kitchen-hide-tag.md %})

If either after this check you think, that the setup of settings in the application is correct, and you are still not receiving any orders, check the other options below or contact [the support](mailto:support@orderlord.com).

## No data in the Orders history section
<span class="text-red-200">If the user doesn't see any results even for the time intervals when orders were created and stored in the system, this is because the user doesn't have the permission. **Ask the administrator of the account for this permission.**</span>

## Past events in the Timeline section
Once the user needs to check the history of the events, that he performed during working with the application, he could use the {% include icon.html name="timeline" %} [**Timeline**]({{site.baseurl}}{% link docs/timeline-section/timeline-section.md %}) section. <span class="text-red-200">But be aware, the number of events logged for the timeline is limited, depending on the device. Once the application was uninstalled, or the cache of the application was deleted (through device Settings), **the timeline data will be deleted**. The application is also storing the only limited value of Timeline data, approximately for the last 7 days.</span>

## Tags aren't working
If the user selects meals with specific tags to be visible only, and he isn't seeing them, it's because of the wrong menu setup. Follow the steps to reproduce the problem:
- first of all, he needs to be sure, that in the Kitchen application is the order, where should be these meals with the tags setup. He could do that by unticking all selected tags so that he will be sure to see everything (every order). Once he will do that, he needs to check if the order with the selected tags is displaying. If not, then this order wasn't received by the Kitchen application
- if yes, then revert back selected tags (as previously selected ones). Then check the menu in the DMS website, if tags are correctly setup on the:
	- items itself
	- category, where these items belong. Once you setup the tag on the category, every item in this category will acquire this tag also
- if you are sure, that the menu is set up right, return to the Kitchen application and [update the menu and tags]({{site.baseurl}}{% link docs/getting-started/update-the-data.md %})
- if nothing from the above didn't help, contact [the support](mailto:support@orderlord.com)

## Wrong name of the items/additions/ingredients, etc.
When the cook received a new order into the Kitchen application, he could notice, that the order is containing items with wrong naming. This could be caused by multiple issues:
- you haven't updated latest menu for the Kitchen application ([follow the steps]({{site.baseurl}}{% link docs/getting-started/update-the-data.md %}))
- the order came from the integration and we weren't able to pair items with the items on our menu. In that case, contact [the support](mailto:support@orderlord.com) with the details or [send the report]({{site.baseurl}}{% link docs/troubleshooting/report-your-problem.md %})
- the menu is wrongly setup or the name is misspelled, need to be fixed in the Dashboard website (DMS)

## Can't mark the food as cooked or prepared
You aren't able to click on the food to increase his status for cooked/prepared status. This three reasons could be the reason:
- the application is blocking you from doing anything right after you finish the scrolling of the list. This measure was necessary, because for some low-end devices it happened, that during the scrolling they unwillingly increased the cooked/prepared status of the item. That's why we added **0,5 seconds** block delay for any action after scrolling.
- you are in the {% include icon.html name="access_time" %} [**Kitchen history**]({{site.baseurl}}{% link docs/getting-started/how-to-use-the-kitchen-screen.md %}) section, where you aren't able to perform any actions like increasing the food status, prepare/cancel/finish the order, reverting the food status, etc..

## Kitchen screen isn't refreshing automatically
This case could occur, if the cook made a lot of actions in the short period of the time. In that case, a lot of updates (like _"update food status"_, _"prepare order"_, _"finish order"_, _"cancel order"_, etc.) are buffered and prepared for a batch sending to the server. Once this sending is started, the update mechanism is postponed until all these requests are in the buffer prepared. This process should take maximum 10 seconds, depending on the number of requests. Once the buffer of requests for sending is empty, the update mechanism will be triggered and update the Kitchen application with the latest data. 
<span class="text-red-200">If this update mechanism will be not triggered automatically, you could start it by [manually updating mechanism.]({{site.baseurl}}{%  link docs/getting-started/update-the-data.md %})</span>

## The order disappeared from the screen
If the cook notices, that the order, which was in the list of orders, disappeared from the Kitchen application, he should follow the steps:
- check if the delivery time of the order wasn't changed, if yes, then he could find him in the "Future orders" part. He could also find it in the [Order's history section]({{site.baseurl}}{%  link docs/orders-history-section/orders-history-section.md %})
- the order was cooked/prepared by another cook from another device, so the order hasn't a reason to be visible anymore in the list of orders
- the order was prepared, canceled or finished by another user, even from the KDS, POS, DMS or another application
- you aren't able to see the items depending on the cooked/prepared status. That means, that if the item is in the preparation stage, and you are able to see the items only from zero <-> cooked status, then you will not see this item.

## The item disappeared from the order
If the item will disappear from the order, this could be caused by editing the order. If another user will edit the order from the DMS or POS, it's possible, that he removed some items from this order.

## Drinks are displaying even that they shouldn't
This issue could occur, if the user hasn't checked the option [Hide items with ‘Kitchen hide’ tag]({{site.baseurl}}{%  link docs/list-of-settings/data-section/hide-items-with-kitchen-hide-tag.md %}). If the user enables this setting, and the drinks are still displaying, it's because the menu wasn't set up properly. The **"Kitchen hide"** tag needs to be set up on the specific items or on the parent category, where these items belong (be aware, that then all items in this category will be hidden, if you'll set up the tag on the category itself). Once you'll do that (or the user, who set up the menu, or our [support team](mailto:support@orderlord.com)), [update the menu and tags by the guide.]({{site.baseurl}}{% link docs/getting-started/update-the-data.md %})

## Can't synchronize any orders
This issue could be caused by multiple issues. The most probable one is, that the Android device isn't connected to the network. In such case, [check this section.]({{site.baseurl}}{%  link docs/troubleshooting/network-issues.md %})

## Insufficient permission for the restaurant
<span class="text-red-200">If the user is not receiving the orders, it could be because of that the user hasn't permission to work the restaurant. Ask the manager to add the correct restaurants, which he could work with.</span>

## Settings are locked
<span class="text-red-200">Your account was adjusted for the purposes of locked settings for the kitchen staff.</span> The user, who has the **"KDS manager"** permission, has option to setup which setting is locked and which is enabled for the other kitchen staff to change that by themself. Your user hasn't this permission, so he is forcing to use only some settings and can't change these blocked settings.