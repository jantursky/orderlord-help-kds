---
layout: default
title: Printers
nav_order: 6
has_children: true
has_toc: false
permalink: /list-of-settings/printers
---

# Printers
{: .no_toc }

---

## Description
During working with the Kitchen application, the user has an option to let the application print **labels/receipts/kitchen receipts** _automatically_ or _manually_, depending on the setup. This functionality needs to have external printer hardware, in some cases also with the cables and connection to the network (depends on the communication). If the user needs to print manually, he could do that simple in the {% include icon.html name="format_list_bulleted" %} [**Kitchen**]({{site.baseurl}}{% link docs/getting-started/how-to-use-the-kitchen-screen.md %}) section:
- click on the _left block of the row_
- **or** _long click_ on the whole row
	- the new dialog with the options will be displayed. On this dialog you are able to:
		- {% include icon.html name="label" %} **Print label** - communication with the label printer will be created and try to print the **label** (single or multiple by the quantity of the meal, [depending on the setting]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/label-quantity.md %}). This option is displayed only if the label printer is set up in the settings section and depending on the meal cooked/prepared status.
		- {% include icon.html name="receipt" %} **Print receipt** - communication with the receipt printer will be created and try to print the **receipt** and **kitchen receipt**. This option is displayed only if the receipt printer is set up [in the settings section.]({{site.baseurl}}{% link docs/printers/receipt-printer/how-to-setup-receipt-printer-in-the-app.md %})

## Table of contents
- [Label printer]({{site.baseurl}}{% link docs/printers/label-printer/label-printer.md %})
- [Receipt printer]({{site.baseurl}}{% link docs/printers/receipt-printer/receipt-printer.md %})

{% include img.html name="printer_all_types_1.jpg" %}