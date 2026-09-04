---
layout: about
title: about
permalink: /
subtitle: <a href='https://scs.gatech.edu/'>School of Computer Science, Georgia Tech</a>

profile:
  align: right
  image:
  image_circular: false # crops the image to make it circular
  # more_info: >
  #   <p>555 your office number</p>
  #   <p>123 your address street</p>
  #   <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 3 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi, I am a first-year PhD student in Computer Science at `Georgia Tech`, advised by [Prof. Anand Iyer](https://www.anand-iyer.com/) in the [NEXS](https://nexs.scs.gatech.edu/) group. Before joining Georgia Tech, I received my B.S. in Computer Science (with a minor in Mathematics) from KAIST, where I was a research intern at the CASYS lab advised by [Prof. Youngjin Kwon](https://sites.google.com/view/yjkwon/home).

My research interests lie in computer systems for machine learning, with a focus on building efficient AI infrastructure — LLM serving systems, memory and KV cache management, and the runtime mechanisms that make them fast and dependable.

Previously, I have worked on research projects including:

- **Project S3**: a serving system that redesigns the KV caching stack to make sparse attention practical for long-context LLM serving. I focused on reducing CPU–GPU swap overhead when the KV cache is offloaded and reloaded.

- **Project DynoSpec**: a serving system for speculative decoding that accelerates LLM inference by dynamically colocating models.

- **Project TETRIS**: a serving system that enables dynamic parallel scaling for LLMs. It assigns adaptive scaling configurations using reinforcement learning.

- **Project BudAlloc**: One Time memory Allocator (OTA) that mitigates use-after-free (UAF) bugs by decoupling virtual address management from the kernel. It leverages eBPF to reduce the semantic gap.

If you’re interested in discussing research, or exploring collaboration opportunities, I’d love to connect — don’t hesitate to reach out to me at `wgwak3@gatech.edu` !

## education

- **Georgia Institute of Technology** <br>
  Ph.D. in Computer Science <br>
  *Aug 2026 – Present*

- **KAIST (Korea Advanced Institute of Science and Technology)** <br>
  B.S. in Computer Science, Minor in Mathematics <br>
  *Feb 2019 – Feb 2026* · Summa Cum Laude
