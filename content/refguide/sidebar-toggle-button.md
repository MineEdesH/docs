---
title: "Sidebar Toggle"
parent: "layout-widgets"
menu_order: 30
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---


The sidebar toggle is a button that when pressed will make a region of a [scroll container](scroll-container) appear or disappear. This makes it possible to create sidebars, for instance a menu on a mobile phone that is hidden by default and can be shown by clicking the button. See the picture for an example layout that used the sidebar toggle. 

![](attachments/pages/sidebar-toggle-button.png)

## Button properties

{{% snippet file="refguide/caption-property.md" %}}

{{% snippet file="refguide/image-property.md" %}}

{{% snippet file="refguide/render-mode-property.md" %}}

{{% snippet file="refguide/button-style-property.md" %}}

## Common properties

{{% snippet file="refguide/name-property.md" %}}

{{% snippet file="refguide/class-property.md" %}}

{{% snippet file="refguide/style-property.md" %}}

{{% snippet file="refguide/tab-index-property.md" %}}

## General properties

### Region

Choose the region that should be collapsed/expanded by clicking this button.

| Region | Effect |
| --- | --- |
| Left | The left region of the layout container will be toggled. |
| Right | The right region of the layout container will be toggled. |

{{% alert type="info" %}}

The sidebar toggle is right-to-left-aware (RTL) which means that in RTL languages the sidebar will slide in from the right if you choose 'Left'.}

{{% /alert %}}

_Default value:_ Left

### Mode

Determines how the region will be toggled.

| Mode | Effect |
| --- | --- |
| Push content aside | The sidebar moves the rest of the content off-screen. |
| Slide over content | The sidebar moves over the content. |
| Shrink content | The content shrinks to make space for the sidebar. |

### Initially open

Only applicable if the mode is "Shrink content".

## Visibility properties

{{% snippet file="refguide/visibility-property.md" %}}

{{% snippet file="refguide/visibility-property-with-module-roles-extended.md" %}}
