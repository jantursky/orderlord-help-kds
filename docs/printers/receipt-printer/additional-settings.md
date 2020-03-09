---
layout: default
title: Additional settings
nav_order: 5
has_children: false
grand_parent: Printers
parent: Receipt printer
permalink: /printers/receipt-printer/additional-settings
---

# Additional settings
{: .no_toc }

---

### List of settings:
1. **Receipt reprints** - determine how many of receipts should be printed for every order
1. **Kitchen reprints** - determine how many of kitchen receipts should be printed for every order
1. **Characters per line** - depending on the vendor and model of the printer, you need to setup number of characters per line. Default value is 42 characters but you need to check that depending on the setup of your printer.
1. **Empty lines at the start** - how many empty lines should be printed before start to print the first line
1. **Empty lines at the end** - how many empty lines should be printed after last printed line on the end
1. **Autoprint functionality** - after enabling this functionality, when a new order will come to the application (even if it's a future order), the application will try to create a connection with a setup printer and print receipts and kitchen receipts depending on the count setup in the configuration

{% include img.html name="receipt_printer_additional_settings_1.png" %}

{% include img.html name="receipt_printer_additional_settings_2.png" %}