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
          filename: neuromodulation.jpg
          filters:
            brightness: 0.5
        text_color_light: true
    content:
      title: Neural Engineering Laboratory
      text: Neurotechnology for movement disorders and motor rehabilitation

  - block: cta-image-paragraph
    content:
      items:
        - title: Wearable closed-loop neuromodulation
          text: We develop wearable devices that listen to the body and respond to it. By reading muscle activity with high-density EMG, our systems deliver peripheral electrical stimulation only when and how it is needed, with no surgery and no implants. We investigate how this EMG-guided therapy can quiet tremor in essential tremor and Parkinson’s disease, from the physiology behind its effects to devices people can wear in daily life.
          image: wereable.jpeg
        - title: AI-driven adaptive therapies
          text: No two tremors are alike, and no tremor stays the same. We use artificial intelligence to learn from each patient’s own data, so that therapy can adapt over time instead of following a fixed protocol. These data-driven strategies pave the way for treatments that tune themselves to each individual, improving effectiveness while reducing unnecessary stimulation.
          image: ai_driven.jpeg
        - title: Electrical stimulation at the cellular level
          text: Before a therapy reaches a patient, we want to understand how living tissue responds to it. We develop custom electrode platforms to stimulate and functionally assess muscle-like cells grown in vitro, bridging biomedical engineering, electrical stimulation and cell biology. This work helps us study how electrical signals shape muscle cells, and it brings a new perspective to the design of future neuromodulation therapies.
          image: cells.png

  - block: markdown
    design:
      columns: '1'
    content:
      title: Our laboratory
      text: |-
        <div class="not-prose" style="width: min(1100px, 100vw - 2rem); margin-left: 50%; transform: translateX(-50%); margin-top: 30px; display: flex; gap: 16px; overflow-x: auto; scroll-snap-type: x mandatory; padding-bottom: 12px;">
          <figure style="flex: 0 0 min(85%, 800px); scroll-snap-align: center; margin: 0;">
            <img src="uploads/setup.jpeg" alt="Experimental setup" style="width: 100%; aspect-ratio: 16/10; object-fit: cover; border-radius: 10px;">
            <figcaption style="margin-top: 8px; font-size: 0.9rem; text-align: center;">Experimental setup</figcaption>
          </figure>
          <figure style="flex: 0 0 min(85%, 800px); scroll-snap-align: center; margin: 0;">
            <img src="uploads/laboratory.png" alt="Laboratory prototyping" style="width: 100%; aspect-ratio: 16/10; object-fit: cover; border-radius: 10px;">
            <figcaption style="margin-top: 8px; font-size: 0.9rem; text-align: center;">Laboratory prototyping</figcaption>
          </figure>
          <figure style="flex: 0 0 min(85%, 800px); scroll-snap-align: center; margin: 0;">
            <img src="uploads/laboratory2.png" alt="Signal acquisition" style="width: 100%; aspect-ratio: 16/10; object-fit: cover; border-radius: 10px;">
            <figcaption style="margin-top: 8px; font-size: 0.9rem; text-align: center;">Signal acquisition</figcaption>
          </figure>
          <figure style="flex: 0 0 min(85%, 800px); scroll-snap-align: center; margin: 0;">
            <img src="uploads/acceleration.jpeg" alt="AI-based protocol" style="width: 100%; aspect-ratio: 16/10; object-fit: cover; border-radius: 10px;">
            <figcaption style="margin-top: 8px; font-size: 0.9rem; text-align: center;">AI-based protocol</figcaption>
          </figure>
          <figure style="flex: 0 0 min(85%, 800px); scroll-snap-align: center; margin: 0;">
            <img src="uploads/cell_M.png" alt="Cellular stimulation" style="width: 100%; aspect-ratio: 16/10; object-fit: cover; border-radius: 10px;">
            <figcaption style="margin-top: 8px; font-size: 0.9rem; text-align: center;">Cellular stimulation</figcaption>
          </figure>
          <figure style="flex: 0 0 min(85%, 800px); scroll-snap-align: center; margin: 0;">
            <img src="uploads/tremor.png" alt="Tremor research" style="width: 100%; aspect-ratio: 16/10; object-fit: cover; border-radius: 10px;">
            <figcaption style="margin-top: 8px; font-size: 0.9rem; text-align: center;">Tremor research</figcaption>
          </figure>
        </div>
        
  - block: collection
    design:
      columns: '1'
      view: citation
    content:
      title: Selected publications
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
      title: Where we are
      text: |-
        <div style="display: flex; gap: 20px; align-items: center; flex-wrap: wrap; margin-top: 20px; width: 100%;">
          <div style="flex: 1; min-width: 280px;">
            <img src="uploads/ci2a.png" alt="Cajal Neuroscience Center" style="width: 100%; height: 350px; object-fit: contain; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
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
