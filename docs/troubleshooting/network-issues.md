---
layout: default
title: Network issues
nav_order: 2
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/network-issues
---

# Network issues
{: .no_toc }

1. TOC
{:toc}

---

## Red circle indicator
Circle indicator in the header of every section in the application next to the section name is indicating if the connection with the network is <span class="text-green-200">established and running by **green color**</span> or once the connection <span class="text-red-200">is disconnected by **red color** and blinking.</span>

## Unable to connect to the network
If you aren't able to connect to the network, follow these steps:
- **turn OFF and ON {% include icon.html name="network_wifi" %} the Wi-Fi** - check if it helps
- if not, check if is there {% include icon.html name="priority_high" %} **exclamation mark** right next to the connection icon, if it's {% include icon.html name="network_wifi" %} Wi-Fi or {% include icon.html name="network_cell" %} Cellular data. If yes, try to investigate, why the device isn't able to connect to the network - probably **wrong network credentials, the external device fault** (external devices like modem, router or switch is running but is not able to communicate with the server) or **something else**.
- if that doesn't help, try to **restart the device** and check the network again
- else contact [the support](mailto:support@orderlord.com) with the description of the problem

## Server issues
<span class="text-red-200">During working with the application, it could happen, that the application is responding, that there are **server issues**. This could happen, that the application will be not available for a few minutes, because there right at that moment is updating source code to the latest version. If the problem persists, contact [the support](mailto:support@orderlord.com) with the description of the problem.</span>