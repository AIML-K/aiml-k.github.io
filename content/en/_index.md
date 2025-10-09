---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero # see https://bootstrap.hugoblox.com/blocks/hero/
    content:
      title: |
        AI+Math Lab @ Korea
      image:
        # Reference an image in your `assets/media/` folder
        filename: 20230922_140739_yes.jpg
      text: |
        <br>
        
        In AIML@K, we expand the frontier of artificial intelligence with mathematics through researching, teaching, and outreaching for the human race.
        <!--Custom spacing-->
        <div class="mb-3"></div>
      cta:
        label: Meet the AIMLers
        url: ./people/
        icon_pack: fas
        icon: wand-sparkles
      # # Optionally, add an alternative CTA link
      # cta_alt:
      #   label: Ask a question
      #   url: https://discord.gg/z8wNYzb
      # # Optionally, add a note under the Call-To-Action button
      # cta_note:
      #   label: >-
      #     <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>          
  
  - block: collection
    content:
      title: Select Publications
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        featured_only: true # set "featured: true" in pub frontmatter
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: compact
      columns: '1'

  - block: logos
    content:
      title: Research Partners
      # subtitle: Section Subtitle
      # Path to the logo images within the `assets/media/` folder
      logo_folder: logos
    design:
      columns: '1'  
      padding: ['20px', '0', '20px', '0']


  - block: portfolio
    id: latest
    content:
      title: Latest
      # subtitle: My subtitle
      # text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      filters:
        # Folders to display content from
        folders:
          - news
          - event
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
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: masonry
      # For Showcase view, flip alternate rows?
      # flip_alt_rows: false

  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 6
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: news
  #   design:
  #     view: card
  #     columns: '1'


  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: ASB_lobby_2022.jpg
          filters:
            brightness: 0.8
          parallax: true
          position: center
#  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the AIMLers →" %}}
  #   design:
  #     columns: '1'
---