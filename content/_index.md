---
title: 'Colony Construction'
date: 2024-02-11
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Colony Construction <small>Building Dreams</small>
      text: |
        Remodels, New Home Construction, any size jobs in Bisbee, Arizona,<br />
        Cochise County and beyond
      primary_action:
        text: Schedule a Free Consultation
        url: mailto:ata5696@gmail.com
        icon: phone
      secondary_action:
        text: Get a Free Quote
        url: mailto:ata5696@gmail.com
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: landing.webp
          filters:
            brightness: 0.5
  - block: features
    id: features
    content:
      title: Comprehensive Construction Solutions Tailored to You
      items:
        - name: "Home Remodels"
          description: "Transform your existing space. Kitchens, Bathrooms, and more"
          icon: sparkles
        - name: "New Home Construction"
          icon: home
          description: "Bring your vision of a perfect home to life from the ground up."
        - name: "Custom Projects"
          icon: bug-ant
          description: "No job too big or small, we handle it all with precision and care."
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Meet Andrew Anderson
          text: Your Local Licensed Contractor
          feature_icon: bug-ant
          features:
            -  At Colony Construction, we pride ourselves on turning visions into reality. Andrew Anderson, with a keen eye for detail and a steadfast commitment to quality, offers top-notch construction services ranging from home remodels to grand new constructions. Based in Bisbee, AZ we extend our expertise across Cochise County and throughout the state of Arizona. No project is too big or small for us. Trust us to navigate the complexities of your construction needs with precision and care.
          # Upload image to `assets/media/` and reference the filename here
          image: andrew-anderson.jpg
          button:
            text: Schedule a Free Consultation
            url: mailto:ata5696@gmail.com
        - title: Why Colony Construction is the Right Choice for Your Project
          text: Tailored Craftsmanship for Every Project
          feature_icon: bug-ant
          features:
            - "Experience: we bring a wealth of knowledge to every project in Bisbee, Arizona and beyond"
            - "Trust: Licensed and authorized to undertake both residential and commercial projects."
            - "Personalized Service: Andrew personally oversees each project to ensure it meets our high standards and your personal needs."
          # Upload image to `assets/media/` and reference the filename here
          image: placeholder.jpg
          button:
            text: Schedule a Free Consultation
            url: mailto:ata5696@gmail.com
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    content:
      title: Your Project, Our Passion
      text: Discover How Colony Construction Can Transform Your Space
      button:
        text: Schedule a Free Consultation
        url: mailto:ata5696@gmail.com
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
