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

## List of settings
1. [**Printer language**]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/printer-language.md %}) - you could set up the different language for text for the label in comparison the application language
1. [**Speed of printing**]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/speed-of-printing.md %}) - slow or fast printing. The difference between these two options is, that when you have selected slow printing, every time during creating the connection with the label, series of checks will be carried out, for instance, "paper amount", "temperature of the printer", "data overload" and others. If every check will pass, the printer is prepared for printing the label. These series of checks may take from 5 to 10 seconds. But if you select fast printing, this series will be skipped, and the printer will try to print labels immediately. This second option is faster but more prone to errors.
1. [**Label quantity**]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/label-quantity.md %}) - depending on the vendor and model of the printer, you need to set up the number of characters per line. The default value is 42 characters but you need to check that depending on the setup of your printer.
1. [**Offset on the X-axis**]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/offset-and-width-setup.md %}) - set the number of pixels to indent the text on the label on the X-axis from left. Default value is 25px.
1. [**Offset on the Y-axis**]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/offset-and-width-setup.md %}) - set the number of pixels to indent the text on the label on the Y-axis from top. Default value is 40px.
1. [**Maximum label width in pixels**]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/offset-and-width-setup.md %}) - specify the maximum text length on the X-axis in pixels. Default value is 728px.

{% include img.html name="label_printer_additional_settings_1.png" %}

{% include img.html name="label_printer_additional_settings_2.png" %}

{% include img.html name="label_printer_additional_settings_3.png" %}

{% include img.html name="label_printer_additional_settings_4.png" %}

{% include img.html name="label_printer_additional_settings_5.png" %}