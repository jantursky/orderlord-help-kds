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
Check if any of this options are causing this issue:
- [Limit for old orders]({{site.baseurl}}{% link docs/list-of-settings/data-section/limit-for-old-orders.md %})
- [Limit for future orders]({{site.baseurl}}{% link docs/list-of-settings/data-section/limit-for-future-orders.md %})
- [Station profile]({{site.baseurl}}{% link docs/list-of-settings/data-section/station-profile.md %})
- [Order types]({{site.baseurl}}{% link docs/list-of-settings/data-section/order-types.md %})
- [Tags filter]({{site.baseurl}}{% link docs/list-of-settings/data-section/tags-filter.md %})
- [Brands filter]({{site.baseurl}}{% link docs/list-of-settings/data-section/brands-filter.md %})
- [Hide items with Kitchen hide tag]({{site.baseurl}}{% link docs/list-of-settings/data-section/hide-items-with-kitchen-hide-tag.md %})

If either after this check you think, that the setup of settings in the application is correct, and you are still not receiving any orders, check the other options below or contact [the support](mailto:support@orderlord.com).

## Wrong timezone
If the orders are showing wrong time, the issue could be with the wrong timezone, date or time. <span class="text-red-200">Be aware, that some manufacturer devices (mostly _Chinese brands_) contains a bug, which is causing that even if you setup correct timezone for your area, the device will (mostly after restart the Android device or synchronization with their website) change the timezone to the wrong timezone (for instance timezone of the manufacturer).</span> For better overview you could notice that through wrong date+time information on the **Kitchen screen** on the bottom. You just need to compare the device date and time with the real time. For a better final solving this bug, you could setup manually timezone of the device in {% include icon.html name="settings" %} _the Android device settings_.

## Wrong date or time
<span class="text-red-200">Same as the issue with the [wrong timezone issue](#wrong-timezone), check if the device date and time is the correct one.</span> You could also setup device date and time manually for better control of the device in {% include icon.html name="settings" %} _the Android device settings_.

## No data in Orders history section
<span class="text-red-200">If the user doesn't see any results even for the time intervals when orders were created and stored in the system, this is because the user doesn't have the permission. **Ask the administrator of the account for this permission.**</span>

## Past events in Timeline section
Once the user needs to check the history of the events, that he performed during working with the application, he could use the {% include icon.html name="timeline" %} [**Timeline**]({{site.baseurl}}{% link docs/timeline-section/timeline-section.md %}) section. <span class="text-red-200">But be aware, the number of events logged for the timeline is limited, depending on the device. Once the application was uninstalled, or the cache of the application was deleted (through device Settings), **the timeline data will be deleted**. The application is also storing only limited value of Timeline data, approximatelly for a last 7 days.</span>

## Insufficient permission for the restaurant
<span class="text-red-200">If the user is not receiving the orders, it could be because of that the user hasn't permission to work the restaurant. Ask the manager to add the correct restaurants, which he could work with.</span>

## Settings are locked
<span class="text-red-200">Your account was adjusted for the purposes of locked settings for the kitchen staff.</span> The user, who has the **"KDS manager"** permission, has option to setup which setting is locked and which is enabled for the other kitchen staff to change that by themself. Your user hasn't this permission, so he is forcing to use only some settings and can't change these blocked settings.