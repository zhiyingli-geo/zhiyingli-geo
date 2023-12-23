---
widget: pages
widget_id: " "
headless: true
weight: 50
title: People
subtitle: ""
active: false
content:
  page_type: publication
  count: 0
  filters:
    author: ""
    category: ""
    publication_type: ""
    tag: ""
  order: desc
design:
  view: 3
  columns: "1"

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Graduate Research Assistant
 #         - Grad Students
  #        - Administration
   #       - Visitors
   #       - Alumni
   
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---
