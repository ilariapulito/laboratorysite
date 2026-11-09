---
title: ''
summary: ''
type: landing

sections:
  - block: hero
    design:
      size: tall
      background:
        image:
          filename: Arm_NEW.jpg
          filters:
            brightness: 0.5
        text_color_light: true
    content:
      title: Neural Engineering Laboratory
      text: Neuroengineering motor control and personalized rehabilitation

  - block: cta-image-paragraph
    content:
      items:
        - title: Wearable Closed-Loop Neuromodulation
          text: We develop wearable systems that combine sensing and stimulation in a single, non-invasive device. High-density EMG and inertial sensors continuously monitor motor activity, while peripheral electrical stimulation is delivered only when and how it is needed. Designed for people with movement disorders such as essential tremor and Parkinson’s disease, these devices aim to make therapy personalised, unobtrusive and usable in everyday life.
          image: wereable.jpg
        - title: AI-driven Adaptive Therapies
          text: Tremor changes over time, between patients and even within a single day. We use artificial intelligence to learn from wearable accelerometer data and anticipate how a patient’s tremor will evolve, so that stimulation can be adjusted following the tremor pattern. These data-driven strategies pave the way for therapies that adapt automatically to each individual, improving effectiveness while reducing unnecessary stimulation.
          image: ai.jpg
        - title: EMG-driven Exoskeletons
          text: Recovering the ability to walk is a major priority for people with neurological injuries. We design exoskeletons that are controlled directly by the user’s muscle activity, so that assistance follows the person’s own motor intention. This approach promotes active participation and aims to make gait rehabilitation more effective and more personalised.
          image: exoscheletons.jpg

  - block: markdown
    design:
      columns: '1'
    content:
      title: Our Laboratory
      text: |-
        <div style="display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 20px; margin-top: 30px; width: 100%;">
          <img src="uploads/setup.jpeg" alt="Experimental setup" style="display: block; width: 100%; height: 280px; object-fit: contain; border-radius: 10px;">
          <img src="uploads/laboratory.png" alt="Laboratory prototyping" style="display: block; width: 100%; height: 280px; object-fit: contain; border-radius: 10px;">
          <img src="uploads/laboratory2.png" alt="Signal acquisition" style="display: block; width: 100%; height: 280px; object-fit: contain; border-radius: 10px;">
        </div>
        
  - block: collection
    design:
      columns: '1'
      view: citation
    content:
      title: Selected Publications
      subtitle: Recent high-impact research outputs
      text: ''
      filters:
        folders:
          - publications
        featured_only: true
        count: 5
      link:
        text: "View all publications"
        url: "publications"

  - block: markdown
    design:
      columns: '1' # Estende il blocco a tutta la larghezza
    content:
      title: Where We Are
      text: |-
        <div style="display: flex; gap: 20px; align-items: center; flex-wrap: wrap; margin-top: 20px; width: 100%;">
          <div style="flex: 1; min-width: 280px;">
            <img src="uploads/ci2a.png" alt="Cajal Neuroscience Center" style="width: 100%; height: 350px; object-fit: cover; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
          </div>
          <div style="flex: 1; min-width: 280px;">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3033.2368793847886!2d-3.350135023594038!3d40.51425504969724!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd424b7975ff2ecd%3A0x4283ca428f21c213!2sCi2A!5e0!3m2!1sit!2snl!4v1793113323437!5m2!1sit!2snl" width="100%" height="350" style="border:0; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
          </div>
        </div>

  - block: markdown
    id: contact
    design:
      columns: '1'
    content:
      title: Connect
      text: |-
        Interested in our research, open positions (Master / PhD / Postdoc), or potential academic collaborations? Feel free to reach out to us or connect across our platforms.

        <div style="margin-top: 20px; display: flex; gap: 15px; flex-wrap: wrap; align-items: center;">
          <a href="mailto:filipe.barroso@cajal.csic.es" style="padding: 10px 20px; background-color: #0d9488; color: white; border-radius: 6px; text-decoration: none; font-weight: 600;">📧 Send an Email</a>
          <a href="https://www.linkedin.com/company/centro-de-neurociencias-cajal-csic/posts/" target="_blank" rel="noopener" style="padding: 10px 20px; border: 1px solid #0d9488; color: #0d9488; border-radius: 6px; text-decoration: none; font-weight: 600;">LinkedIn Page</a>
        </div>
---
