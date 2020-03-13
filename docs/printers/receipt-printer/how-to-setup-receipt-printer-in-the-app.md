---
layout: default
title: How to setup receipt printer in the app
nav_order: 2
has_children: false
grand_parent: Printers
parent: Receipt printer
permalink: /printers/receipt-printer/how-to-setup-receipt-printer-in-the-app
---

# How to setup receipt printer in the app
{: .no_toc }

1. TOC
{:toc}

---

## Where is Receipt printer category
- Open the menu from the left side and find {% include icon.html name="settings" %} [**Settings**]({{site.baseurl}}{% link docs/list-of-settings/list-of-settings.md %}) section

{% include img.html name="receipt_printer_setup_1.png" %}

- After click on this section, the new screen with display. Click on the {% include icon.html name="settings" %} **Customization** category

{% include img.html name="receipt_printer_setup_2.png" %}

- The list of the settings under this category will be displayed, and you could see, what is the current path, where are you at the moment ({% include icon.html name="home" %} **HOME** {% include icon.html name="chevron_right" %} {% include icon.html name="settings" %} **CUSTOMIZATION**)
- Search in the list of categories {% include icon.html name="receipt" %} **Receipt printer** category and click on this row.

{% include img.html name="receipt_printer_setup_3.png" %}

- Click on the {% include icon.html name="print" %} **Enable receipt printing** option for {% include icon.html name="check_box" %}
- If you set up the receipt printer first time, the dialog with printer configuration will be displayed. If you already setup configuration for the printer, click on the {% include icon.html name="settings" %} **Printer customization** option. 
- The dialog with configuration will be displayed, follow the setup if the printer supports:
	- [Bluetooth communication](#bluetooth-communication)
	- [USB communication](#usb-communication)
	- [Wi-Fi communication](#wi-fi-communication)

## List of supported brands
- {% include icon.html name="print" %} **AURES** - USB
- {% include icon.html name="print" %} **STAR** - Wi-Fi, Bluetooth, LAN
- {% include icon.html name="print" %} **CASHINO** - Bluetooth, USB
- {% include icon.html name="print" %} **BLUETOOTH** - Bluetooth
- {% include icon.html name="print" %} **EPSON** - Wi-Fi, Bluetooth, USB
- {% include icon.html name="print" %} **USB** - USB

## Bluetooth communication
- on the Printer customization screen, select the correct vendor from the **Brand** options.
- once you select the vendor, list of **connection types** will be reloaded and will display available connections with the selected vendor that we supporting
- select {% include icon.html name="bluetooth" %} **BLUETOOTH** connection type
- click on the {% include icon.html name="search" %} **SEARCH** icon on the right side

- the Android device is trying to find all Bluetooth devices around, not just the paired one. Wait a while, until your receipt printer will be listed. Also be sure, that your printer is running + some printers need to be in discovery mode (check the attached guide for the printer). Once the printer is in the list, select that row:
	- if the printer wasn't paired before, after the click it will start to pair automatically. Once the printer is paired, click on the row
- the MAC address of the printer will be set up automatically in the **Address** line. After the setup, the rest of the [additional settings]({{site.baseurl}}{% link docs/printers/receipt-printer/additional-settings.md %}), click on the <span class="text-green-200">**SAVE**</span> button and **your printer is prepared for the use**

{% include img.html name="receipt_printer_setup_12.png" %}

## USB communication
- on the Printer customization screen, select the correct vendor from the **Brand** options.
- once you select the vendor, list of **connection types** will be reloaded and will display available connections with the selected vendor that we supporting
- select {% include icon.html name="usb" %} **USB** conection type
- click on the {% include icon.html name="search" %} **SEARCH** icon on the right side
- connect the receipt printer with the Android device with a USB cable.
- [popup for allowing access for the USB device]({{site.baseurl}}{% link assets/images/kds/receipt_printer_how_to_setup_receipt_printer_usb_3.jpg %}) will be displayed. Check if in the text is mentioned application **KDS**:
	1. if **YES**, select the additional option **Use by default for this USB device** and click on the <span class="text-green-200">**OK**</span> button
	1. if **NO**, click on the <span class="text-red-200">**CANCEL**</span> button. 
- <span class="text-red-200">If another popup is displayed with the same context but there is mentioned another name of the application, click on the **CANCEL** button.

{% include img.html name="receipt_printer_setup_9.png" %}

- once you confirm **access** for this USB device, the printer should be displayed in the list. Select that row.

{% include img.html name="receipt_printer_setup_10.png" %}

- the ID path for the USB device of the printer will be set up automatically in the **Address** line. After the setup, the rest of the [additional settings]({{site.baseurl}}{% link docs/printers/receipt-printer/additional-settings.md %}), click on the <span class="text-green-200">**SAVE**</span> button and **your printer is prepared for the use**

<span class="text-red-200">Warnings:</span>
- <span class="text-red-200">You need every time to allow access to the application with the receipt printer with a popup.</span>
- <span class="text-red-200">If the popup for allowing access wasn't displayed, try to attempt to rotate the cable to certain angles. It is possible the USB cable has faulty contacts and only communicates under a certain degree of connection.</span>
- <span class="text-red-200">It could happen, that even if you set up everything, the printer isn't able to print receipts. It's because that USB cable is a wrong type and is not supporting **Read/Write** feature</span>

## Wi-Fi communication
- on the Printer customization screen, select the correct vendor from the **Brand** options.
- once you select the vendor, list of **connection types** will be reloaded and will display available connections with the selected vendor that we supporting
- select {% include icon.html name="usb" %} **Wi-Fi** connection type
- in this moment you have two options on how to setup **IP address** (and **port**, if it's listed):
	- automatic way:
		- click on the {% include icon.html name="search" %} **SEARCH** icon on the right side
		- wait until your printer will be listed and select it
		- the **IP address** (and **port**, if it's listed) will be filled automatically. 
	- manual way (if it's enabled):
		- type the IP address of the printer in the line **IP address**
		- if the **Port** line is listed also, type there the port of the printer. If you don't know, what's the value, default is **9100**

- after the setup, the rest of the [additional settings]({{site.baseurl}}{% link docs/printers/receipt-printer/additional-settings.md %}), click on the <span class="text-green-200">**SAVE**</span> button and **your printer is prepared for the use**

{% include img.html name="receipt_printer_setup_6.png" %}

{% include img.html name="receipt_printer_setup_8.png" %}