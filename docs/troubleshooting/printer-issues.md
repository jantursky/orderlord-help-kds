---
layout: default
title: Printer issues
nav_order: 6
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/printer-issues
---

# Printer issues
{: .no_toc }

1. TOC
{:toc}

---

## USB issues
- <span class="text-red-200">You need every time to allow access to the application with the label printer with the popup.</span>
- <span class="text-red-200">If the popup for allowing access wasn't displayed, try to attempt to rotate the cable to certain angles. It is possible that the USB cable has faulty contacts and only communicates under a certain degree of connection.</span>
- <span class="text-red-200">It could happened, that even if you setup everything, the printer isn't able to print labels. It's because that USB cable is a wrong type and is not supporting **Read/Write** feature</span>

## Receipt printer prints blank receipts
- <span class="text-red-200">paper is not thermal</span> - ensure you have a thermal paper loaded properly. If it is thermal paper, a scratch with a thumbnail or the edge of a coin will leave a black mark
- <span class="text-red-200">paper is put in backwards</span> - ensure that the paper is inserted in the printer where it feeds form underneath the roll towards the front
- <span class="text-red-200">bad thermal heads</span>
- <span class="text-red-200">bad printer installation</span>

## Receipt printer cuts before it finishes printing
You need to increase [empty lines at the end.]({{site.baseurl}}{% link docs/list-of-settings/receipt-printer-section/empty-lines-at-the-start-end.md %})

## The printer is printing small font
Increase the text size in the [label customization]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/label-customization.md %}), [receipt design]({{site.baseurl}}{% link docs/list-of-settings/receipt-printer-section/receipt-design.md %}) or [kitchen reprint design]({{site.baseurl}}{% link docs/list-of-settings/receipt-printer-section/kitchen-reprint-design.md %}).

## Factory reset the printer
Turn the printer off. Use a paper clip or tip of a pen to press and hold the reset on the back of the printer for a 5 seconds. While holding the reset button, turn the printer on. Continue to hold the reset button. After 5 seconds, a warning will print out or the printer will reset with a sound. Release the reset button.

{% include img.html name="troubleshooting_printer_issues_factory_reset_1.jpg" %}

## Tickets are very lightly
<span class="text-red-200">If tickets suddenly begin printing lighter than usual, it means the printer is running low on ink.</span> Load a new ink ribbon into the printer.

## Tickets are printing in red ink
Tickets normally print in black ink. <span class="text-red-200">If your tickets begin printing only in red ink, it means, that the paper is at the end of the roll.</span>

## Labels are printing very slowly
You could increase the speed of printing with [this setting]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/speed-of-printing.md %}). <span class="text-red-200">But you need to be aware, that it could increase the error rate.</span>

## Data of the order aren't printing
If some of the data from the order aren't printing, even if you're are sure, that the order is containing this information, make sure, that you enabled printing of that information for the [label printer]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/label-customization.md %}) or [receipt printer]({{site.baseurl}}{% link docs/list-of-settings/receipt-printer-section/receipt-design.md %}).

## Duplicate tickets are printing
It could be caused of wrong [receipt customization]({{site.baseurl}}{% link docs/printers/receipt-printer/additional-settings.md %}) of [label customization]({{site.baseurl}}{% link docs/list-of-settings/label-printer-section/label-quantity.md %}).

## General issues
- <span class="text-red-200">_always be sure, that the label printer has paper_</span>
- <span class="text-red-200">_if the printer is printing, but the paper is empty, the roll of paper in the printer is opposite_</span>
- <span class="text-red-200">_if the printer is connected to the network (**router/modem or switch**), be sure that you configured the IP address of the printer during connection on the same network_</span>