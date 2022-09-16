---
widget: featured
title: LATEST ACTIVITIES
headless: true  # This file represents a page section.
weight: 50

# ... Put Your Section Options Here (title etc.) ...

content:
  columns: '1'
  # Page type to display. E.g. post, event, or publication.
  page_type: event
  # Choose how much pages you would like to display (0 = all pages)
  count: 1
  # Page order. Descending (desc) or ascending (asc) date.
  order: desc
  # Optionally filter posts by a taxonomy term.
  filters:
    tag: ''
    category: ''
    publication_type: ''
  archive:
    enable: true
    text: See all activities
    link: event/
design:
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view:  compact
  css_style: 
  css_class: 
  background:
    # Name of image in `assets/media/`.
    image: 
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.6
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on the desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: false

---