---
title: Grav CMS Pro the best solution to design professional websites
menu: Home
metadata:
  description: Grav CMS Pro is the best solution to design professional websites. It is built on top of Grav open source Content Management System and Materialize framework
  author: Grav CMS Pro

dictionaries:
  - home
  - shared

content:
    items: @self.modular
    order:
        b\y: default
        dir: asc
        custom:
            - _gravcmspro
            - _centre
            - _features
            - _interlude_1
            - _example
            - _requirements
            - _screencast
            - _prices
            - _contact
            - _interlude_2
---

<| SHARED.NAVBAR |>


[m-component component="jumbotron-no-scrolldown" folder="jumbotron" M_PATH="images" M_IMAGE="home.jpg" M_BLURRED_IMAGE=""  M_HEIGHT="three-quarters" M_BACKGROUND_ATTACHED="true" M_CONTAINER="true" M_ATTRIBUTES="class:s12 m7 l6 padding-medium"]  
  D_HEADER_JUMBOTRON
[/m-component]

[m-grid container="false"]
  [m-grid-row attributes="class:box-bg-primary-dark box-tiny text-full-white link-accent-2"]
    [m-grid-col attributes="class:s12 m12 l4 padding-left-right-large padding-top-small"]
      D_INTRO_1
    [/m-grid-col]
    [m-grid-col attributes="class:s12 m12 l4 padding-left-right-large padding-top-small"]
      D_INTRO_2
    [/m-grid-col]
    [m-grid-col attributes="class:s12 m12 l4 padding-left-right-large padding-top-small"]
      D_INTRO_3
    [/m-grid-col]
  [/m-grid-row]
[/m-grid]

[m-tag tag="main" attributes="id:main"]
  [m-modular-collection][/m-modular-collection]
[/m-tag]

<| SHARED.FOOTER |>
<| SHARED.VENDOR_SCRIPTS |>
