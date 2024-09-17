---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: ''
      background:
        color: ''
        image:
          # Add your image background to `assets/media/`.
          filename: ''
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      css_class: ''
      background:
        dark-color: '#272935'
        light-color: '#606480'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: markdown
    id: dissertationphd
    content:
      title: 'Dissertation'
      subtitle: 'Divided over Democracy - The effects of Affective Polarization on the Democratic Support of citizens in
Europe'
      text: |-
        My dissertation titled **'Divided over Democracy: The effects of Affective Polarization on Citizens' Democratic Support'** is funded by the [Research Foundation Flanders (FWO)](https://www.fwo.be/en/) under a four-year fundamental research fellowship (2023-2027). Read the abstract of the dissertation below. 

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

        Scholars warn that affective polarization – the tendency of partisans to dislike or even loathe supporters of opposing political parties – undermines citizens’ commitments to principles and norms on which democracies are founded (i.e., democratic support). Within the academic literature, speculation about the potential political consequences of affective polarization on democratic support is rife, but empirical evidence is inconsistent and mixed at best. In this project, I aim to address this gap by comprehensively studying the extent to which affective polarization erodes citizens’ democratic support in Europe. This project translates the concerns about the political consequences of affective polarization into a theoretical and empirical research agenda by (1) studying how affective polarization and democratic support relate to each other across countries and electoral contexts, (2) developing and testing a causal mechanism between affective polarization and democratic support, and by (3) examining the conditionality of the consequences of affective polarization on the losers and winners of salient political decisions. Methodologically, I employ crossnational survey data as well as survey experiments. This project offers innovative theoretical and empirical insights into a pressing question in contemporary scholarly discourse: To what extent does affective polarization threaten the quality and stability of democracies?
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        My dissertation titled **'Divided over Democracy: The effects of Affective Polarization on Citizens' Democratic Support'** is funded by the Research Foundation Flanders (FWO) under a four-year fundamental research fellowship. Read the abstract of the dissertation below. 

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
