---
# An instance of the Blank widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 95

title: Teaching
subtitle:

design:
  columns: "1"
  background:
    image: headers/bubbles-wide.jpg
    image_darken: 0.6
    image_parallax: true
    image_position: center
    image_size: cover
    text_color_light: true
  spacing:
    padding: ["20px", "0", "20px", "0"]
---


{{< display_table_csv "static/teaching.csv" >}}
{{< /display_table_csv >}}
