---
layout: default
title: Login issues
nav_order: 1
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/login-issues
---

# Login issues
{: .no_toc }

1. TOC
{:toc}

---

## First-time permissions
During the first-time login, the user will be prompt to accept the application's required permission - [for more information click here]({{site.baseurl}}{% link docs/frequently-asked-questions-faq/application-permissions.md %})

## Wrong format of Email
You need to be aware, that during typing the email address, you need to type the correct format of the address, like **"orderlord@gmail.com"**

## Unauthorized access/Incorrect credentials
If you typed the email and password correctly, but the application responds with **Unathorized access** message, then:
- <span class="text-red-200">check again, if the email and password is correct one</span>
- <span class="text-red-200">don't add empty spaces on the beginning or the end of the input</span>
- <span class="text-red-200">be sure that you are connected to the internet. Even if you think, that you are connected to the network, try to disconnect and connect the Wi-Fi again. It could happened that even that the icon {% include icon.html name="network_wifi" %} Wi-Fi is running, it could have a issue with initializing {% include icon.html name="perm_scan_wifi" %} the Wi-Fi module. You could double-check that in the Android device Web browser, where you try to open any website.</span>
- <span class="text-red-200">it could also happened, that the **user or the account is blocked**, so also contact [the support](mailto:support@orderlord.com)</span>

## Server issues
<span class="text-red-200">During logging into the application, it could happened, that the application is responding, that there are **server issues**. This could happened, that the application will be not available for a few minutes, because there right in that moment is updating source code to the latest version. If the problem persists, contact [the support](mailto:support@orderlord.com) with the description of the problem.</span>

## Bad gateway/SSL Certificate error
<span class="text-red-200">If you are based in the country or place, where is the network connection hierarchy restricted (mostly {% include icon.html name="network_wifi" %} Wi-Fi connection), it's hardly for us to solve the issue. Even if we are using the servers which should be allowed globally, we don't have the possibility to check that for every location separately.</span> This is the moment, where you as a user can help us. The only thing, that you need to do, is to install the Kitchen application on your Android smartphone (if you have one) and try to login through that device once you'll connect to the network through {% include icon.html name="network_cell" %} Cellular data (Mobile data). If you were able to logged into the account through smartphone, then you know, that your local Wi-Fi in the store is **blocking our servers**. Try to contact our [the support](mailto:support@orderlord.com) with the description of this specific issue.

## Timeout error
<span class="text-red-200">The application is trying to verify credentials and download data about deliveries, orders, drivers, menu catalog etc. It could happened, that during this process the server responds with **timeout error**. This is caused by long running of downloading of many data. Try to login again, the downloading should pass. If not, contact [the support](mailto:support@orderlord.com) with the description of the problem.</span>

## Other issues
For any other issues, which were mentioned above, please, contact [the support](mailto:support@orderlord.com) with the description of the problem.