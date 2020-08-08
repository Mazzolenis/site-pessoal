+++
widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

# ... Put Your Section Options Here (title etc.) ...
title = "Destaques"

[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "post",
  page_type = "publication",
  page_type = "talk"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 3
  
  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    exclude_featured = false
    exclude_past = false
    exclude_future = false
    
[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 3
+++
