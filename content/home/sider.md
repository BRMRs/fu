---
widget: slider
headless: true  # This file represents a page section.
weight: 25
# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 330px


item:
  - title: 'Looking for interns and full-time research engineers'
    content: 'My team can request hundreds of A100 GPUs anytime :yum:'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#666'  # An HTML color value.
    overlay_img: wide.jpg  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.9  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Contact me for details
    cta_url: 'https://bigaidream.github.io/contact'
    cta_icon_pack: fas
    cta_icon: comment
  # - title: Left
  #   content: 'I am left aligned 😄'
  #   align: left
  #   overlay_color: '#555'
  #   overlay_img: ''
  #   overlay_filter: 0.8
  # - title: Right
  #   content: 'I am right aligned 😄'
  #   align: right
  #   overlay_color: '#333'
  #   overlay_img: ''
  #   overlay_filter: 0.5

---