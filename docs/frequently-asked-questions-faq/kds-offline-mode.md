---
layout: default
title: KDS offline mode
nav_order: 5
has_toc: false
parent: Frequently asked questions (FAQ)
permalink: /frequently-asked-questions-faq/kds-offline-mode
---

# KDS offline mode
{: .no_toc }

---

## Basic principle
When the internet is turned off, the device is not able to connect to the network, or **Wi-Fi module/LAN cable** is not working, the system is able to work in a **limited state**. The orders, which already came to the device till that break-down moment, could be cooked and prepared, this information is stored locally and when the internet connection will be restored, it started to send one by one. The system is able to print labels with the printer if the printer is connected with the KDS device through a [USB connection]({{site.baseurl}}{% link docs/printers/label-printer/how-to-setup-label-printer.md %})



| FUNCTIONALITY									| <span class="text-green-100">ENABLED</span>  | <span class="text-red-100">DISABLED</span> |
|:------------------------------------------------------|:------|:------|
| set food as cooked									| <span class="text-green-100">{% include icon.html name="check" %}</span>|  |
| set food as prepared									| <span class="text-green-100">{% include icon.html name="check" %}</span>|  |
| reset food to cooked state							| <span class="text-green-100">{% include icon.html name="check" %}</span>|  |
| reset food to empty state								| <span class="text-green-100">{% include icon.html name="check" %}</span>|  |
| reset order											|  | <span class="text-red-100">{% include icon.html name="close" %}</span>|
| finish order											|  | <span class="text-red-100">{% include icon.html name="close" %}</span>|
| cancel order											|  | <span class="text-red-100">{% include icon.html name="close" %}</span>|
| print receipts connected through {% include icon.html name="usb" %} USB or {% include icon.html name="bluetooth" %} Bluetooth		| <span class="text-green-100">{% include icon.html name="check" %}</span>|  |
| download the latest orders							|  |  |
| updating data from settings section					|  | <span class="text-red-100">{% include icon.html name="close" %}</span>|
| print labels connected through {% include icon.html name="usb" %} USB					| <span class="text-green-100">{% include icon.html name="check" %}</span>|  |
| print labels connected through {% include icon.html name="network_wifi" %} Wi-Fi					|  | <span class="text-red-100">{% include icon.html name="close" %}</span>|
| print receipts connected through {% include icon.html name="network_wifi" %} Wi-Fi				|  | <span class="text-red-100">{% include icon.html name="close" %}</span>|

<!-- ## Working functionality offline
- set food as cooked
- set food as prepared
- reset food to cooked state
- reset food to empty state
- print labels connected through USB
- print receipts connected through USB or Bluetooth

## Disabled functionality in offline mode
- reset order
- finish order
- cancel order
- download the latest orders
- updating data from settings section
- print labels connected through Wi-Fi
- print receipts connected through Wi-Fi -->

{% include img_tablet.html name="faq_kds_offline_mode.png" %}