+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Welcome!"
  content = " "
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/head1.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.15  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Start here"
  cta_url = "https://krhayes.com/authors/admin/"
  cta_icon_pack = "fas"
  cta_icon = "leaf"

[[item]]
  title = "Landscape & Disturbance Ecologist"
  content = ""
  align = "right"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/head2.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.
  


[[item]]
  title = "CV"
  content = " "
  align = "left"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "headers/head3.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.
  
  cta_label = "Link here"
  cta_url = "http://127.0.0.1:4321/files/cv.pdf"
  cta_icon_pack = "fas"
  cta_icon = "leaf"
+++
