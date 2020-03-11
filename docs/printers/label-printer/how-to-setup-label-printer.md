---
layout: default
title: How to setup label printer
nav_order: 1
has_children: false
grand_parent: Printers
parent: Label printer
permalink: /printers/label-printer/how-to-setup-label-printer
---

# How to setup
{: .no_toc }

1. TOC
{:toc}

---

## Where is Label printer category
- Open the menu from the left side and find {% include icon.html name="settings" %} [**Settings**]({{site.baseurl}}{% link docs/list-of-settings/list-of-settings.md %}) section

{% include img.html name="label_printer_setup_1.png" %}

- After click on this section, the new screen with display. Click on the {% include icon.html name="settings" %} **Customization** category

{% include img.html name="label_printer_setup_2.png" %}

- The list of the settings under this category will be displayed, and you could see, what is the current path, where are you at the moment ({% include icon.html name="home" %} **HOME** {% include icon.html name="chevron_right" %} {% include icon.html name="settings" %} **CUSTOMIZATION**)
- Search in the list of categories {% include icon.html name="label" %} **Label printer** category and click on this row.

{% include img.html name="label_printer_setup_3.png" %}

## USB Communication
First of all, you need to check if your specific label printer has allowed USB communication and reading/writing feature:
- <span class="text-green-100">{% include icon.html name="check" %}</span> check if the label printer has {% include icon.html name="usb" %} USB port
- <span class="text-green-100">{% include icon.html name="check" %}</span> check if in the box of label printer was added also USB cable
- <span class="text-green-100">{% include icon.html name="check" %}</span> during connection the label printer with your Android device, the [popup for allowing access for the USB device]({{site.baseurl}}{% link assets/images/kds/label_printer_how_to_setup_label_printer_usb_3.jpg %}) will be displayed.

{% include img.html name="label_printer_how_to_setup_label_printer_usb_1.jpg" %}

{% include img.html name="label_printer_how_to_setup_label_printer_usb_3.jpg" %}

Once you know, that the label printer supports USB communication, follow these steps for setup:
1. Go to the **Label printer** category ([guide](#where-is-label-printer-category))
1. Click on the {% include icon.html name="print" %} **Enable label printing** option for {% include icon.html name="check_box" %}
1. Once this option is enabled, list of settings will be displayed. Click on the {% include icon.html name="phonelink_ring" %} **Connection type** option. 
1. Select from the opened dialog option **USB** and click on <span class="text-green-200">**SET SELECTED**</span> button
1. Connect the label printer with the Android device with USB cable.
1. [Popup for allowing access for the USB device]({{site.baseurl}}{% link assets/images/kds/label_printer_how_to_setup_label_printer_usb_3.jpg %}) will be displayed. Check if in the text is mentioned application **KDS**:
	1. if **YES**, select the additional option **Use by default for this USB device** and click on the <span class="text-green-200">**OK**</span> button
	1. if **NO**, click on the <span class="text-red-200">**CANCEL**</span> button. 
1. <span class="text-red-200">If another popup is displayed with the same context but there is mentioned another name of the application, click on the **CANCEL** button.
1. If you successfully setup the USB Label printer, click on the {% include icon.html name="receipt" %} **Test print** category. If everything works, the label printer should till 10 seconds print label with _test message_.

<span class="text-red-200">Warnings:</span>
- <span class="text-red-200">You need everytime to allow access the application with the label printer with popup.</span>
- <span class="text-red-200">If the popup for allowing access wasn't displayed, try to attempt to rotate the cable to certain angles. It is possible that the USB cable has faulty contacts and only communicates under a certain degree of connection.</span>
- <span class="text-red-200">It could happened, that even if you setup everything, the printer isn't able to print labels. It's because that that USB cable is a wrong type and is not supporting **Read/Write** feature</span>
- <span class="text-red-200">Warning</span>

{% include img.html name="label_printer_how_to_setup_label_printer_usb_2.jpg" %}


## Wi-Fi Communication

Description.

{% include img.html name="label_printer_setup_4.png" %}

{% include img.html name="label_printer_setup_5.png" %}

{% include img.html name="label_printer_setup_6.png" %}

{% include img.html name="label_printer_setup_7.png" %}

{% include img.html name="label_printer_setup_8.png" %}

## General warnings
- <span class="text-red-200">always be sure, that the label printer has paper</span>
- <span class="text-red-200">if the printer is printing, but the paper is empty, the roll of paper in the printer is opposite</span>
- <span class="text-red-200">if the printer is connected to the network (router/modem or switch), be sure that you configured the IP address of the printer during connection on the same network</span>