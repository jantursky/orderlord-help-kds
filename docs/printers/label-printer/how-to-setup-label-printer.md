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
- <span class="text-red-200">It could happened, that even if you setup everything, the printer isn't able to print labels. It's because that USB cable is a wrong type and is not supporting **Read/Write** feature</span>

{% include img.html name="label_printer_how_to_setup_label_printer_usb_2.jpg" %}

## Wi-Fi Communication
Communication with a Wi-Fi connection with Label printer is a bit harder for configuration. 

First of all, you need to know, if the label printer has available Wi-Fi (called Ethernet) connection. You could to be sure by two ways:
1. Check the back side of the label printer. Be sure, that there is a port for **LAN cable**.
1. Try to do **the test print** of that label printer. Follow the steps for test print:
	1. Make sure the media is properly loaded and the top cover of the printer is closed. Then, turn the printer power on if you have not already done so. When the status light is solid green, press and hold **the Feed button until the status light flashes once.**
	1. **Release the Feed button**. A configuration label will print.
	1. On this printer label configuration, there should be mentioned the line **"IP ADDRESS"** (or something similar describing IP address):
		1. If this line is mentioned there:
			1. and the IP address hasn't default value (mentioned in the 2. option) - the label printer should have already setup IP address
			1. and the IP address is in the format **255.255.255.255**, **192.168.254.254**, **192.168.192.168**, **0.0.0.0** or similar - then you need to setup a new IP address for this printer
		1. If you aren't able to find this line:
			1. The printer has disabled Wi-Fi (Ethernet) port, you know that this printer should have Wi-Fi working connection and you need to ask for the _service support_ to solve this issue
			1. The printer hasn't Wi-Fi working communication, even that there is a port - it's because companies are forcing the customer to buy **additional Wi-Fi hardware** for the printer

{% include img.html name="label_printer_how_to_setup_label_printer_wifi_1.jpg" %}

Once you know, that the label has enabled Wi-Fi port for communication, and you need to setup a new IP address of the Label printer, follow the steps:
- Install the [**Zebra setup utilities**](https://www.zebra.com/us/en/support-downloads/printer-software/printer-setup-utilities.html) into the PC.
- Connect the label printer with the PC - through the USB cable mostly or LAN cable (depends on the ports of the printer).
- Open the application **Zebra setup utilities**, there should be a empty list of added label printers

{% include img.html name="label_printer_how_to_setup_label_printer_wifi_2.png" %}

- Click on the **Install New Printer** button and follow the new screen for adding connected label printer. If the list already contains any printer (before or after installing new printer), select this printer (specific one, where you want to configure), and click on the **Configure Printer Connectivity** button.

{% include img.html name="label_printer_how_to_setup_label_printer_wifi_3.png" %}

- New dialog screen will be displayed, where select the option **Wireless**

{% include img.html name="label_printer_how_to_setup_label_printer_wifi_4.png" %}

- New dialog screen will be displayed, select the option **Static** and setup **IP Address**, **Subnet mask** and **Default gateway**. Type in the IP address that is free on the network, the subnet mask and the default gateway. Please note that if you need to set up more printers, each has to have a unique IP address.
	- To find out what IP address to set up, do the following:
		- on **Windows PC**:
			1. Open the command prompt (cmd) from Windows **Run**
			1. Type in **ipconfig** and hit **ENTER**. It will populate the data with all the necessary information: IP address, Subnet Mask and Default Gateway.
			1. Find the **Ethernet** or **Wi-Fi** adapter's block of text. There should be the mention **IP Address**, **Subnet Mask** and **Default Gateway** info. 
			1. Use the first 3 numbers from this IP address to set up the IP address of your printer, and add the 4th number as a unique ID between 1-255. For example, if the IP is _192.168.20.1_ on the PC, you may use _192.168.20.21_ for the printer. You just need to be sure, that this new assigned IP address is not assigned to another device in the network.

		- on **Mac PC**:
			1. open the **Network settings**, select **Wi-fi** and click on **Advanced**
			1. switch to **TCP/IP** tab and search for these data: **IPv4 address** = IP address of the PC. Use the first 3 numbers from this IP address to set up the IP address of your printer, and add the 4th number as a unique ID between 1-255. For example, if the IP is _192.168.20.1_ on the PC, you may use _192.168.20.21_ for the printer. **Subnet Mask** = Subnet Mask, **Router** = Default Gateway
- click on **Next** button without changing any other settings and on the last screen, click **Finish** button
- the printer should restart itself with a new assigned IP address. After the printer restarted, do a **Test print** and check if the printed test label with the configuration contains the new IP address.
	- <span class="text-green-100">{% include icon.html name="check" %}</span> if yes, **congratulations**, you setup the IP address for the label printer and you are able to use the label printer
	- <span class="text-red-200">{% include icon.html name="cancel" %}</span> if not, contact the [support with e-mail](mailto:support@orderlord.com), who will try to solve the issue

{% include img.html name="label_printer_how_to_setup_label_printer_wifi_5.png" %}

- once everything was setup properly, you could try to connect with the label printer. Go to the **Label printer** category ([guide](#where-is-label-printer-category))
- click on the {% include icon.html name="print" %} **Enable label printing** option for {% include icon.html name="check_box" %}

{% include img.html name="label_printer_setup_4.png" %}

- once this option is enabled, list of settings will be displayed. Click on the {% include icon.html name="phonelink_ring" %} **Connection type** option. 

{% include img.html name="label_printer_setup_5.png" %}

- select from the opened dialog option **Wi-Fi** and click on <span class="text-green-200">**SET SELECTED**</span> button

{% include img.html name="label_printer_setup_6.png" %}

- you have 2 options how to setup IP address and port of the label printer:
- **automatic** - click on the {% include icon.html name="search" %} **Automatic printer discovery** row, new dialog will be displayed and the application will try to find the Zebra printer in the same network as the Android device is connected. If the Zebra is listed in the list of founded devices, click on the device and IP address and port of the printer will be setup automatically

{% include img.html name="settings_label_printer_automatic_printer_discovery_3.png" %}

- **manual** - click on the {% include icon.html name="label" %} **The IP address of the printer** row, new dialog will be displayed, type there assigned IP of the printer (for example **"192.168.1.30"**) and click on <span class="text-green-200">**SET SELECTED**</span> button. Then click on the {% include icon.html name="label" %} **TCP port of the printer** row, another dialog will be displayed, type there port of the printer (the default is **"9100"** - try to use this value) and click on <span class="text-green-200">**SET SELECTED**</span> button.

{% include img.html name="label_printer_setup_8.png" %}

- **congratulations**, you have prepared the label printer for the use

## Bluetooth communication
Bluetooth communication with the printer is currently not supported. In this case, please [contact us by email.](mailto:support@orderlord.com)

## General warnings
- <span class="text-red-200">_always be sure, that the label printer has paper_</span>
- <span class="text-red-200">_if the printer is printing, but the paper is empty, the roll of paper in the printer is opposite_</span>
- <span class="text-red-200">_if the printer is connected to the network (**router/modem or switch**), be sure that you configured the IP address of the printer during connection on the same network_</span>