---
layout: default
title: Additional settings
nav_order: 4
has_children: false
grand_parent: Printers
parent: Label printer
permalink: /printers/label-printer/additional-settings
---

# Additional settings
{: .no_toc }

---

## List of settings:
1. **Printer language** - you could setup the different language for text for the label in comparison the application language
1. **Speed of printing** - slow or fast printing. Difference between this two options is, that when you have selected slow printing, every time during creating the connection with the label, series of checks will be carried out, for instance "paper amount", "temperature of the printer", "data overload" and others. If every check will pass, the printer is prepared for the printing the label. These series of checks may take from 5 to 10 seconds. But if you select fast printing, this series will be skipped, and printer will try to print label immediately. This second option is faster but more prone to errors.
1. **Label quantity** - depending on the vendor and model of the printer, you need to setup number of characters per line. Default value is 42 characters but you need to check that depending on the setup of your printer.
1. **Offset on the X-axis** - set the number of pixels to indent the text on the label on the X axis from left. Default value is 25px.
1. **Offset on the Y-axis** - set the number of pixels to indent the text on the label on the Y axis from top. Default value is 40px.
1. **Maximum label width in pixels** - specify the maximum text length on the X axis in pixels. Default value is 728px.

{% include img.html name="label_printer_additional_settings_1.png" %}

{% include img.html name="label_printer_additional_settings_2.png" %}

{% include img.html name="label_printer_additional_settings_3.png" %}

{% include img.html name="label_printer_additional_settings_4.png" %}

{% include img.html name="label_printer_additional_settings_5.png" %}