---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

**A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1CIc2FTHgTR_lL71W4ON3J01WVYgC51fxgsfYmn2pwtQ/edit?usp=sharing).**


{% for module in site.modules %}
{{ module }}
{% endfor %}
