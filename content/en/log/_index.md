---
title: 'AIML@K Logs'
type: landing

sections:

  - block: portfolio
    id: logs
    content:
      title: Logs
      subtitle: 'Peeking into AIML@K'
      # text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      filters:
        # Folders to display content from
        folders:
          - log
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        # kinds:
        #   - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: AI4Math
          tag: AI4Math
        - name: Math4AI
          tag: Math4AI
        - name: LM
          tag: LanguageModel
        - name: AI4Sci
          tag: AI4Science
        - name: Conj
          tag: conjecture
        - name: Diary
          tag: diary

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false


  # - block: collection
  #   # id: posts
  #   content:
  #     title: 'Logs'
  #     subtitle: 'Peeking into AIML@K'
  #     # text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 30
  #     # Filter on criteria
  #     filters:
  #       # The folders to display content from
  #       folders:
  #         - log
  #       author: ""
  #       category: ""
  #       tag: ""
  #       publication_type: ""
  #       featured_only: false
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #     # Choose how many pages you would like to offset by
  #     # Useful if you wish to show the first item in the Featured widget
  #     offset: 0
  #     # Field to sort by, such as Date or Title
  #     sort_by: 'Date'
  #     sort_ascending: false
  #   design:
  #     # Choose a listing view
  #     view: card
---
