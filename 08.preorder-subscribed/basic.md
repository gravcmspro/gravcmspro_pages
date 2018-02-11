---
title: Centre preorder for subscribed users
date: '01/01/2014 3:14pm'
publish_date: '01/23/2015 13:00e'
visible: false
metadata:
  description: Grav CMS Pro's Centre preorder module for subscribed users

dictionaries:
  - gravcmspro-components
  - shared
---

<| SHARED.NAVBAR |>
<| SHARED.PREORDER_HEADER |>
<| SHARED.SIDENAV_CENTRE |>

[m-grid container="true"]
  [m-grid-row]
    [m-grid-col attributes="class:s12 m12 l12"]
      [m-mautic template="mautic/_preorder_subscribed.html.twig"][/m-mautic]
    [/m-grid-col]
  [/m-grid-row]
[/m-grid]

[m-tag tag="script" attributes="type:text/javascript"]document.getElementById('mauticform_preordersubscribed').submit();[/m-tag]

<| SHARED.FOOTER |>
<| SHARED.VENDOR_SCRIPTS |>
