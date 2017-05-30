---
title: Grav CMS Pro Documentation - Parallax
slug: parallax
menu: Parallax
date: '03/30/2017 6:00am'
metadata:
  description: This shortcode implements a parallax element
  author: Grav CMS Pro

dictionaries:
  - shortcodes.big-images.parallax
  - shortcodes.base-elements-documentation
  - shared
---

<| SHARED.NAVBAR |>
<| SHARED.DOCUMENTATION_HEADER |>
<| SHARED.SIDENAV_SHORTCODES_BIG_IMAGES |>
[m-tag tag="main" attributes="id:main"]
  [m-grid attributes="class:margin-top-large"]
    [m-grid-row]  
      [m-grid-col attributes="class:s12 m12 l6"]
        [![](/images/dreamhost-banner-horizontal.gif "Web hosting"){.responsive-img}](https://www.dreamhost.com/r.cgi?356893)
      [/m-grid-col]
      [m-grid-col attributes="class:s12 m12 l6"]
        [m-google-adsense style="display:block" data-ad-client="ca-pub-1106540662686396" data-ad-slot="6507158489" data-ad-format="auto"][/m-google-adsense]
      [/m-grid-col]
    [/m-grid-row]
    [m-grid-row]
      [m-grid-col attributes="class:s12 m12 l12 margin-bottom-large"]
      D_SHORTCODE
      [/m-grid-col]
    [/m-grid-row]
  [/m-grid]

  [m-parallax image="image.jpg" image-title="Title" image-alt="Alt"]
    [m-tag tag="div"]
      ### Lorem ipsum dolor sit amet, consectetur adipiscing elit
    [/m-tag]
  [/m-parallax]

  [m-grid attributes="class:margin-top-large"]
    [m-grid-row]
      [m-grid-col attributes="class:s12 m12 l12 margin-bottom-large"]
        D_MAIN_CONTENT
      [/m-grid-col]
    [/m-grid-row]
  [/m-grid]
[/m-tag]

<| SHARED.FOOTER |>
