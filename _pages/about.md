---
layout: about
title: about
permalink: /
subtitle: Research Associate at <a href="https://www.tu.berlin/">TU Berlin</a>.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info:

selected_papers: false # publications are rendered below with an expandable list
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Research Associate at [Database System and Information Management (DIMA)](https://www.dima.tu-berlin.de/) group at TU Berlin. Currently, I am working in the area of stream processing, data processing on modern hardware, and big data system.

I graduated from the Erasmus Mundus Joint master’s degree (EMJMD) program in [Big Data Management and Analytics](https://bdma.ulb.ac.be/bdma/) (BDMA) with specialization in large scale data analytics. I worked on operator placement problem for IoT system for my master thesis. Prior to my master’s study, I graduated from the Computer Science bachelor program at [Universitas Gadjah Mada](https://ugm.ac.id) and worked as a Data Engineer.

<p><a href="{{ '/assets/pdf/resume-dwi-nugroho.pdf' | relative_url }}" download>Download my résumé (PDF)</a></p>

When I am away from the keyboard, I love to do sport, especially Cycling. Get in touch with me on [strava](https://www.strava.com/athletes/39303493).

<section class="mt-5" aria-label="Selected publications">
  <p class="text-muted small text-uppercase mb-2"><strong>Selected publications</strong></p>
  <div class="publications" style="font-size: 0.9rem; opacity: 0.82">
    {% bibliography --group_by none --query @*[selected=true]* %}
  </div>
  <details class="mt-2">
    <summary class="small">Browse 6 more publications</summary>
    <div class="publications mt-3" style="font-size: 0.9rem; opacity: 0.82">
      {% bibliography --group_by none --query @*[selected=false]* %}
    </div>
  </details>
</section>
