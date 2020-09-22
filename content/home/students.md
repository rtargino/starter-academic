---
# An instance of the Blank widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 90

title: Students
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

{{< display_table_csv "static/students.csv" >}}
  <!-- <tr><th>Start</th><th>End</th><th>Name</th><th>Level</th><th>Institution</th><th>Project</th><th>Position</th> -->
{{< /display_table_csv >}}
(*) Second supervisor.
