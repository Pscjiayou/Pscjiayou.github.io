---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download my academic CV (PDF)]({{ '/files/Shicheng_CV_academy.pdf' | relative_url }})

## Education

- **University of Michigan, Ann Arbor** — M.S. in Robotics and M.S. in Applied Statistics (Dual Degree), August 2024–May 2027 (expected). GPA: 4.0/4.0.
- **The Chinese University of Hong Kong, Shenzhen** — B.S. in Financial Engineering, September 2020–May 2024. GPA: 3.8/4.0 (top 5%).

## Research experience

**Research Assistant, ROAHM Lab, University of Michigan** — November 2025–present. Advisor: Prof. Ram Vasudevan.

- Ambiguity-Aware Garment Perception for Active Manipulation — September 2026–present.
- DiffADMM: Differentiable Cloth Simulation — May 2026–present.
- DEFT: Modeling and Simulation of Branched Deformable Linear Objects — November 2025–May 2026.

See the PDF above for project details and contributions.

## Publications and manuscripts

{% for post in site.publications reversed %}
<p>{{ post.citation }}</p>
{% endfor %}

## Teaching experience

{% for post in site.teaching reversed %}
<p><strong>{{ post.title }}</strong><br>{{ post.type }}, {{ post.venue }}, {{ post.date | date: "%Y" }}.</p>
{% endfor %}

## Honors and awards

At The Chinese University of Hong Kong, Shenzhen:

- Tier 1 Academic Performance Scholarship, highest annual GPA in cohort — 2023.
- Dean's List, awarded three times — 2021–2024.
- Programming Contest, Third Prize — 2024.

## Technical skills

- **Programming:** Python, C++, R, MATLAB, Bash.
- **Robotics and machine learning:** PyTorch, Pinocchio, Open3D, Isaac Sim.
- **Development tools:** Linux, Git, Docker.
