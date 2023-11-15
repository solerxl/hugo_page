---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['100px', '0', '60px', '0']
  - block: portfolio
    id: projects
    content:
      title: Selected Publications
      filters:
        folders:
          - project
      text: |-
        {{% callout note %}}
        For full publications, please refer to my [Google Scholar](https://scholar.google.com/citations?user=6l4c0oEAAAAJ).
        {{% /callout %}}
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Journal
          tag: Journal
        - name: Conference
          tag: Conference
        - name: Under Review
          tag: Manuscript
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['50px', '0', '50px', '0']
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_start: '2023-10-01'
          organization: Northwestern Polytechnical University
          title: Xiaomi Special Scholarship (Only 10 awardees in NWPU) 
        - date_start: '2022-10-01'
          organization: Northwestern Polytechnical University
          title: National Scholarship for Graduate Students (Rank 1/208)
        - date_start: '2018-10-01'
          organization: Nanjing University of Posts and Telecommunications
          title: National Scholarship for Graduate Students (Rank 2/159)
        - date_start: '2021-06-01'
          organization: Nanjing University of Posts and Telecommunications
          title: Outstanding Graduate
    design:
      columns: '2'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['50px', '0', '50px', '0']
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Teaching'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: '2023-01-01'
          date_start: '2022-03-01'
          description: ''
          icon: ''
          organization: Northwestern Polytechnical University
          organization_url: ''
          title: Teaching Assistant for Fundamentals of Machine Learning
          url: ''
        - date_end: '2019-06-01'
          date_start: '2018-06-01'
          description: ''
          icon: ''
          organization: Nanjing University of Posts and Telecommunications
          organization_url: ''
          title: Tutor at the Students' Association for Science and Technology
          url: ''
    design:
      columns: '2'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['50px', '0', '50px', '0']
---
