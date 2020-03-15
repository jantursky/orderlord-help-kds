---
layout: default
title: How to use
nav_order: 1
parent: Date/time section
grand_parent: List of Settings
has_toc: false
permalink: /list-of-settings/date-time-section/how-to-use
---

# How to use
{: .no_toc }

1. TOC
{:toc}

---

## Description
The user could applied specificed date/time/date+time format for every time information in the application and on the printer receipt/kitchen receipt/label.

## Where to find the option
- Open the menu from the left side and find {% include icon.html name="settings" %} [**Settings**]({{site.baseurl}}{% link docs/list-of-settings/list-of-settings.md %}) section
- After clicking on this section, the new screen with be displayed. Click on the {% include icon.html name="settings" %} **Customization** category
- The list of the settings under this category will be displayed, and you could see, what is the current path, where are you at the moment ({% include icon.html name="home" %} **HOME** {% include icon.html name="chevron_right" %} {% include icon.html name="settings" %} **CUSTOMIZATION**)
- Search in the list of categories {% include icon.html name="event_note" %} **Date/time** category.

## How to use 
- Click on one of the options ([followed by guide](#where-to-find-the-option)):
	- {% include icon.html name="event_note" %} **Date + time - format** - formattting of the date and time depending on the format (like _{{ "now" | date: "%d.%m.%Y, %H:%M" }}_)
	- {% include icon.html name="event_note" %} **Date + time - long format** - formattting of the date and time depending on the format (like _{{ "now" | date: "%d.%m.%Y, %H.%M.%S" }}_)
	- {% include icon.html name="event_note" %} **Date - long format** - formattting of the date and time depending on the format (like _{{ "now" | date: "%d.%m.%Y" }}_)
	- {% include icon.html name="event_note" %} **Date - short format** - formattting of the date and time depending on the format (like _{{ "now" | date: "%d.%m" }}_)
	- {% include icon.html name="access_time" %} **Time - long format** - formattting of the time depending on the format (like _{{ "now" | date: "%H:%M:%S" }}_)
	- {% include icon.html name="access_time" %} **Time - short format** - formattting of the time depending on the format (like _{{ "now" | date: "%H:%M" }}_)
- The dialog with the list of formats will be displayed. Select the one, you want to use in the application. You could also use quick search functionality, which will search in the pattern's names or results.
- Select the pattern and click on the <span class="text-green-100">**SET**</span> button. The selected format will be applied everywhere in the application.

{% include img.html name="settings_date_time_section_how_to_use_1.png" %}

{% include img.html name="settings_date_time_section_how_to_use_2.png" %}

{% include img.html name="settings_date_time_section_how_to_use_3.png" %}

{% include img.html name="settings_date_time_section_how_to_use_4.png" %}