---
title: Grav CMS Pro download
date: '01/01/2014 3:14pm'
publish_date: '01/23/2015 13:00e'
visible: false
metadata:
  description: Grav CMS Pro's Centre license

dictionaries:
  - gravcmspro-components
  - shared
---

<| SHARED.NAVBAR |>
<| SHARED.DOCUMENTATION_HEADER |>
<| SHARED.SIDENAV_CENTRE |>

[m-grid container="true"]
  [m-grid-row]
    [m-grid-col attributes="class:s12 m12 l12"]
      [m-mautic template="mautic/_preorder_subscribed.html.twig"][/m-mautic]
    [/m-grid-col]
  [/m-grid-row]
[/m-grid]

[m-help]
  Main component properties
  tag: the html tag to display. Accepts all html tags. Example tag="div"
  attributes: Adds html attributes to element. Example attributes="class: foo, rel=bar"
  image: The image name with the extension. Set a blank value for no image
  image-path: The image directory
[/m-help]
[m-tag tag="script" attributes="type:text/javascript"]document.getElementById('form-preorder').submit();
[/m-tag]

<| SHARED.FOOTER |>
<| SHARED.VENDOR_SCRIPTS |>
