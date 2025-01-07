---
layout: page
title: Calendar
permalink: /calendar/
description: Listing of course modules and topics.
nav_order: 4
---

# {{ page.title }}

{{ site.full_title }}

Homework and Lab links will launch directly into [Ohio University's JupyterHub](https://jupyterhub.academic.kube.ohio.edu).
If you do not have access to that, then you can see them in the [class public repository](https://github.com/data-ohio/MATH2530_Spring24-25).

Many things will fill in or be modified as we go along, so this calendar should always be considered a draft.

{% for module in site.modules %}
{{ module }}

{% endfor %}







