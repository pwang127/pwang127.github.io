---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: 'About Me'
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false

      spacing:
        padding: ['30px', '0', '40px', '0']

      name:
        size: md

      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        My research applies AI, computer science, and data science to address real-world challenges in healthcare. I use a combination of quantitative and qualitative methods to develop, implement, and evaluate clinical decision support and EHR-based technologies. My work focuses on helping healthcare providers and hospital administrators make better decisions, optimize clinical workflows and operations, and ultimately improve patient care.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
      count: 10
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]

  - block: More About Me
    id: more-about-me
    content:
      title: 'More About Me'
      subtitle: 'Music, Performing Arts & Volunteering'
      text: |-
        Music has been a lifelong passion of mine. I began my musical journey as a **childhood television performer and recording artist**, frequently appearing on television, recording children's songs in professional studios, and participating in public service advertisements. Growing up in front of the camera and behind the microphone sparked a love for music and performance that continues to this day.

        Beyond singing, I enjoy playing the **pipa (a traditional Chinese string instrument), cello, piano, and ukulele**, exploring everything from traditional Chinese music to Western classical and contemporary styles.

        **Giving back to the community is another important part of my life.** Over the years, I've volunteered in a variety of settings, from supporting patients in the Emergency Department at NewYork-Presbyterian Hospital and assisting with ophthalmic examinations and imaging to encouraging young girls to explore science through Columbia University's Girls' Science Day. These experiences have been incredibly meaningful to me and have strengthened my appreciation for compassion, education, and community engagement.

        Today, I also enjoy **hosting local charity events and supporting community initiatives**. Combining my love for performing with my passion for volunteering has been especially rewarding, and I'm always excited to contribute to causes that bring people together and make a positive difference.
    design:
      columns: '1'
---
