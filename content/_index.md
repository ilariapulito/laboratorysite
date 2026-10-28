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
      columns: '1' # Forzatura della larghezza completa del layout
    content:
      title: Our Laboratory
      text: |-
        <div style="display: flex; gap: 20px; width: 100%; margin-top: 20px; flex-wrap: wrap;">
          <img src="uploads/setup.jpeg" alt="Experimental setup" style="flex: 1; min-width: 280px; height: 380px; object-fit: cover; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
          <img src="uploads/setup_no_hd32prolong.jpeg" alt="Wearable device" style="flex: 1; min-width: 280px; height: 380px; object-fit: cover; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
        </div>

  - block: collection
    content:
      title: Selected Publications
      subtitle: Recent high-impact research outputs
      text: ''
      filters:
        folders:
          - publication
        featured_only: true
        count: 5
    design:
      columns: '1'
      view: citation

  - block: markdown
    design:
      columns: '1' # Forzatura della larghezza completa del layout
    content:
      title: Where We Are
      text: |-
        <div style="display: flex; gap: 20px; align-items: center; flex-wrap: wrap; margin-top: 20px;">
          <div style="flex: 1; min-width: 280px;">
            <img src="uploads/ci2a.png" alt="Cajal Neuroscience Center" style="width: 100%; height: 350px; object-fit: cover; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
          </div>
          <div style="flex: 1; min-width: 280px;">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3033.2368793847886!2d-3.350135023594038!3d40.51425504969724!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd424b7975ff2ecd%3A0x4283ca428f21c213!2sCi2A!5e0!3m2!1sit!2snl!4v1793113323437!5m2!1sit!2snl" width="100%" height="350" style="border:0; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
          </div>
        </div>

  - block: contact-info
    content:
      title: Connect
      text: |
        <div style="font-size: 1.05rem; line-height: 1.6;">
          <p style="margin-bottom: 12px;">
            <i class="fas fa-paper-plane" style="color: #6366f1; margin-right: 8px;"></i>
            <strong>Get in Touch</strong>
          </p>
          <p>
            Interested in our research, open positions (Master / PhD / Postdoc), or potential academic collaborations? Feel free to reach out or connect across our platforms.
          </p>
          <div style="margin-top: 15px;">
            <a href="mailto:tuamail@cajal.csic.es" style="display: inline-block; padding: 8px 16px; background-color: #4f46e5; color: white; border-radius: 6px; font-weight: 500; text-decoration: none; font-size: 0.9rem;">
              <i class="fas fa-envelope" style="margin-right: 6px;"></i> Send an Email
            </a>
          </div>
        </div>

  - block: markdown
    design:
      columns: '1'
    content:
      title: Connect & Collaborate
      text: |-
        <div style="background: linear-gradient(135deg, #f8fafc 0%, #eef2ff 100%); border: 1px solid #e0e7ff; border-radius: 12px; padding: 30px; display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 20px; box-shadow: 0 4px 15px rgba(0,0,0,0.03);">
          <div style="flex: 2; min-width: 280px;">
            <h3 style="margin-top: 0; color: #1e1b4b; display: flex; align-items: center; gap: 10px;">
              <i class="fas fa-flask" style="color: #4f46e5;"></i> Join or Collaborate With Us
            </h3>
            <p style="color: #475569; margin-bottom: 0;">
              We are open to joint research projects, Master/PhD supervision, and postdoctoral applications in neuroengineering and motor rehabilitation.
            </p>
          </div>
          <div style="flex: 1; min-width: 220px; display: flex; flex-direction: column; align-items: flex-start; gap: 10px;">
            <a href="mailto:tuamail@cajal.csic.es" style="width: 100%; text-align: center; padding: 10px 18px; background-color: #4f46e5; color: white; border-radius: 8px; font-weight: 600; text-decoration: none; box-shadow: 0 2px 8px rgba(79, 70, 229, 0.25);">
              <i class="fas fa-envelope" style="margin-right: 8px;"></i> Email Us
            </a>
            <a href="https://www.linkedin.com/in/tuoprofilo" target="_blank" style="width: 100%; text-align: center; padding: 10px 18px; background-color: #ffffff; color: #0077b5; border: 1px solid #cbd5e1; border-radius: 8px; font-weight: 600; text-decoration: none;">
              <i class="fab fa-linkedin" style="margin-right: 8px;"></i> LinkedIn Profile
            </a>
          </div>
        </div>
---
