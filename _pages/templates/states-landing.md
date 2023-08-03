---
layout: template
categories: [templates, states]
type: [detail-page]
title: States Landing Page
permalink: /templates/states/landing
overview: This template is used for finding information by state or territory.
OUTDATED: please use the following link to find specs for the State Pageshttps://icfonline.sharepoint.com/:f:/r/sites/CWIGRedesign490/Shared%20Documents/Wireframes%20and%20Design/States%20Page?csf=1&web=1&e=FjZYtr&xsdata=MDV8MDF8fGE3Zjg0ZWE1YTU1OTQ0MWY4NTM4MDhkYjdkNjI5ZmUwfGNmOTBiOTdiYmU0NjRhMDA5NzAwODFjZTRmZjFiN2Y2fDB8MHw2MzgyNDE2MzQ3NDU3NzE5MjZ8VW5rbm93bnxWR1ZoYlhOVFpXTjFjbWwwZVZObGNuWnBZMlY4ZXlKV0lqb2lNQzR3TGpBd01EQWlMQ0pRSWpvaVYybHVNeklpTENKQlRpSTZJazkwYUdWeUlpd2lWMVFpT2pFeGZRPT18MXxMM1JsWVcxekx6RTVPbTV4TVcxa01rRXplVE5oWDIxR1dFcHJNM0ZIVW5oek1tRndWVFZETWpkNU9VVlZjRWRUT0RFNFVXOHhRSFJvY21WaFpDNTBZV04yTWk5amFHRnVibVZzY3k4eE9Ub3haV1V3TWpabE1qVXdNVFUwT1RJd09XVXlNemsxTTJVM01UYzROakV6TjBCMGFISmxZV1F1ZEdGamRqSXZiV1Z6YzJGblpYTXZNVFk0T0RVMk5qWTNNemc1TlE9PXw5N2I3MjlmNjgxMWI0MWE0ODUzODA4ZGI3ZDYyOWZlMHwyMjM3NzE3MDg4YWU0NjQwOThlMWIzOTQ4YzUxMWYwYQ%3D%3D&sdata=R0E3VUd6R3FnaDlFRkcxRFZObUwxNU5pTHNva1pMQ2d4VFczcnNpcjdWST0%3D


description:  The States Landing template houses various resources and information by state.


specs:
  - name: Title
    type: h1
    authored: no
    required: yes
    content: "Find information by State"
    searchable: yes
  - name: Summary
    type: usa-intro
    authored: yes
    required: yes
    content: 250 character max
    searchable: yes
  - name: hex map label
    type: text
    authored: no
    required: yes
    content: "Choose your state or territory below"
  - name: hex map
    type: interactive -- see below

prototype:
  - name: States Landing
    link: /prototype/states/landing

alert:
  content: Before developing page layout, please be sure to read about our <a class="usa-link" href="/styles/grids/">Grid System</a>
  type: warning
---
## Functionality Specifications

{% include patterns/alert/alert-no-icon-jk.md %}


## Hex map
_The prototype uses an image a representative of this experience_
The hex map usings an unordered list with css styling to layout the state/territory items.
- onHover/onHold - the hexagon grows and changes color
- onClick/onTap - the system goes to the appropriate linked page.

_see [SAMHDA](https://www.datafiles.samhsa.gov/) for an example of how to accomplish_
