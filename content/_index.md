---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

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
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am a final-year Ph.D. candidate at Ghent University, passionate about bridging the gap between state-of-the-art AI research and high-impact, real-world applications. My doctoral research focuses on developing robust deep learning models for computer vision, specifically for multimodal audio and video analysis. The results of this work have been published in respected international journals, including IEEE Pervasive Computing.
        
        Beyond my technical research, I have consistently sought opportunities to develop practical leadership and mentorship skills. As a frequent teaching assistant for "Applied Machine Learning," I have enjoyed guiding both undergraduate and Master's students, challenging them to work with real-world tools from Airbnb datasets to industry hardware like Sony's depth cameras. Concurrently, as President of the Taiwanese Student Association in Ghent, I served as the community's main contact and initiated a city-wide mentor-mentee program to support students and residents through the challenges of the pandemic.
        
        I am now seeking a role that blends deep research with practical leadership, where I can contribute to technical direction and mentor team members. While I am excited to tackle complex technical problems across any industry, I hold a strong personal interest in the potential for AI to address critical challenges in fields like humanitarian aid, medical innovation, and environmental protection.
        
        I'm always open to discussing new challenges and opportunities, feel free to reach out to collaborate.
    design:
      columns: '1'
  - block: markdown
    content:
      title: '📚 My Research Philosophy'
      subtitle: ''
      text: |-      
        Scientific progress is the collective achievement of countless researchers, each passing the torch to the next. In that spirit, I believe my role is not to provide definitive solutions, but rather to build a solid foundation of practical and ethically grounded approaches for deploying intelligent systems in the complexity of real-world environments. My work focuses on contributing frameworks that emphasize adaptability, privacy, and contextual awareness, with the hope that they may serve as concrete tools for future innovation. 

        I believe the true impact of technology lies not only in what is built, but in what it may enable. I aim to contribute to the field not only by informing the design of intelligent systems, but by inspiring continued progress toward making technology truly serve its intended role: improving the safety, equity, and quality of human life. 

        Furthermore, I see a profound need to extend these technologies beyond urban convenience and into the domain of humanitarian aid. The same frameworks developed for analyzing complex scenes could be adapted to assist first responders in disaster relief scenarios, such as in the aftermath of a major earthquake, helping to categorize needs when resources are critically limited. They could also provide tools for humanitarian organizations to document events in other crisis zones in a secure and verifiable manner. 

        Ultimately, I believe it is our collective responsibility as technologists to not only build powerful tools, but to actively envision and advocate for their use in service of human dignity and safety. Meaning lies not in the possession of results, but in the integrity of participation. My ultimate goal is to see deep learning prove valuable in addressing the practical needs of our most vulnerable populations in their most difficult moments.
    design:
      columns: 1
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        page_type: publication
        featured_only: true
        tag: "Featured" 
    design:
      view: article-grid
      columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       page_type: publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
  <!-- - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

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
        css_style: "" -->