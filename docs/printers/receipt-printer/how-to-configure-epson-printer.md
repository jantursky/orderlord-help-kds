---
layout: default
title: How to configure Epson printer
nav_order: 1
has_children: false
grand_parent: Printers
parent: Receipt printer
permalink: /printers/receipt-printer/how-to-configure-epson-printer
---

# How to configure Epson printer
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

### Wi-Fi Epson printer

To set up a new Epson printer, first make sure that the printer is connected to the same network as your device (PC, tablet). Once connected, please print a **self-test page**. This can be easily done by holding the **FEED button** and turning the printer off and on. The part that you should check here is the IP Address. If it shows _192.168.192.168_, it means that the printer is not configured on the network.

To configure the printer on the network:
1. Connect the printer to the PC via Ethernet cable.
1. Download the **Epson Net Config app** at for the [Windows OS](https://download.epson-biz.com/modules/pos/index.php?page=single_soft&cid=6047&scat=43&pcat=3) or for [MacOS](https://download.epson-biz.com/modules/pos/index.php?page=single_soft&cid=6313&scat=43&pcat=3) to your PC connected to the network.
1. Run the app.
1. Once the app is opened, you could see on the bottom right side, that the app is trying to find Epson devices in the network or connected directly through _LAN_ or _USB cable_.
1. If even after a 30 sec. Epson device is not listed on that screen, connect the Epson device to the PC directly with the _LAN_ or _USB cable_. If this type of the cable wasn't attached to the printer in the box, you need to buy it (before that, check what type of ports your Epson printer has).
1. Click on the printer and go to **Configuration**. Select the category **Network interface**, and then the subcategory **TCP/IP**. Under this category, there should be the section **Basic**, **Basic (IPv4)** or **Basic (IPv6)**. Select one of them, where you should me able to setup manually IP address of this printer
1. Select here Manual IP and type in the IP address that is free on the network, the subnet mask and the default gateway. Please note that if you need to set up more printers, each has to have a unique IP address.

	- To find out what IP address to set up, do the following:
		- on **Windows PC**:
			1. Open the command prompt (cmd) from Windows **Run**
			1. Type in **ipconfig** and hit **ENTER**. It will populate the data with all the necessary information: IP address, Subnet Mask and Default Gateway.
			1. Find the **Ethernet** or **Wi-Fi** adapter's block of text. There should be the mention **IP Address**, **Subnet Mask** and **Default Gateway** info. 
			1. Use the first 3 numbers from this IP address to set up the IP address of your printer, and add the 4th number as a unique ID between 1-255. For example, if the IP is _192.168.20.1_ on the PC, you may use _192.168.20.21_ for the printer. You just need to be sure, that this new assigned IP address is not assigned to another device in the network.

		- on **Mac PC**:
			1. open the **Network settings**, select **Wi-fi** and click on **Advanced**
			1. switch to **TCP/IP** tab and search for these data: **IPv4 address** = IP address of the PC. Use the first 3 numbers from this IP address to set up the IP address of your printer, and add the 4th number as a unique ID between 1-255. For example, if the IP is _192.168.20.1_ on the PC, you may use _192.168.20.21_ for the printer. **Subnet Mask** = Subnet Mask, **Router** = Default Gateway

1. Once all the data is added to the printer in **Epson Net Config**, you can refresh in the tool and the IP address will be visible. Now you should be able to find the printer in POS app Epson Discovery. If it's not possible, try to type the newly assigned IP address of the printer directly on the configuration screen and try to do **Test print**. It's because your network could be designed that way, that the devices are not directly discoverable through Epson discovery, so you need to input the IP address directly and do **Test print**.