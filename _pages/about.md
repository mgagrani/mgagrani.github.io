---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: profile.jpg
  image_circular: false # crops the image to make it circular
  more_info: >

selected_papers: false # includes a list of papers marked as "selected={true}"
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

I am a staff research sceintist at [Qualcomm AI research](https://www.qualcomm.com/research/artificial-intelligence/ai-research). My research currently focuses on the efficiency of Large Langugage Models (LLMs), specifically developing cutting edge solutions for edge inference. Key areas of my recent research include:

- **Speculative Decoding (SPD)** - [Tree based SPD](https://arxiv.org/pdf/2402.14160), Pioneered application of SPD to multimodal models [Spotlight paper CVPR workshop 2024](https://arxiv.org/pdf/2404.08856), [Vocabulary trimming for efficient drafting](https://arxiv.org/pdf/2506.22694)

- [KV cache compression](https://arxiv.org/pdf/2504.14051) and [FFN sparsity](https://arxiv.org/pdf/2602.00397) for efficient LLM inference
 
Before shifting focus to LLM efficiency, I worked on Machine Learning for Combinatorial Optimization, where I developed neural architectures like [Topoformer](https://openreview.net/pdf?id=EvtEGQmXe3) for computation graph scheduling in ML compilers. I worked on Reinforcement Learning and stochastic control during my PhD, particularly developing [Thompson sampling for unknown Markov Decision Processes](https://proceedings.neurips.cc/paper_files/paper/2017/file/51ef186e18dc00c2d31982567235c559-Paper.pdf) and [Linear Systems](https://arxiv.org/pdf/1709.04047). 

I obtained my PhD in Electrical & Computer Engineering from University of Southern California (USC) in 2020 under the supervision of [Dr. Ashutosh Nayyar](https://sites.google.com/usc.edu/ashutosh) and [Dr. Rahul Jain](https://www.rahuljain.net/). Before that, I finished my undergrad in Electrical Engineering from [IIT Kanpur](https://www.iitk.ac.in) in 2013.

## selected publications

### Efficient LLMs
{% bibliography --query @*[selected=true][area = "Efficient LLMs"]* %}

### ML for Combinatorial Optimization
{% bibliography --query @*[selected=true][area = "ML for Combinatorial Optimization"]* %}

### Online/Reinforcement Learning
{% bibliography --query @*[selected=true][area = "Online Learning"]* %}

<!-- ### Stochastic Control and Communications
{% bibliography --query @*[selected=true][area = "Stochastic Control and Communications"]* %} -->


