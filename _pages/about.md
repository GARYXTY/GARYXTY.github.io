---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About

<div class="section-card">
<div class="pi-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ site.photo }}" class="pi-photo" alt="{{ site.name }}" loading="lazy">
<div>
<h3 class="pi-name">{{ site.name }}</h3>
<p style="font-style: italic; color: var(--text-secondary);">{{ site.title }}, {{ site.institution }}</p>
<div class="pi-links">
{% if site.email %}<a href="mailto:{{ site.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>{% endif %}
{% if site.links.cv and site.links.cv != "" %}<a href="{{ site.url }}{{ site.baseurl }}/{{ site.links.cv }}" class="icon-link" title="CV"><i class="ai ai-cv"></i></a>{% endif %}
{% if site.links.google_scholar and site.links.google_scholar != "" %}<a href="{{ site.links.google_scholar }}" class="icon-link" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>{% endif %}
{% if site.links.github and site.links.github != "" %}<a href="{{ site.links.github }}" class="icon-link" title="GitHub"><i class="fa-brands fa-github"></i></a>{% endif %}
{% if site.links.researchgate and site.links.researchgate != "" %}<a href="{{ site.links.researchgate }}" class="icon-link" title="ResearchGate"><i class="ai ai-researchgate"></i></a>{% endif %}
{% if site.links.linkedin and site.links.linkedin != "" %}<a href="{{ site.links.linkedin }}" class="icon-link" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>{% endif %}
{% if site.links.twitter and site.links.twitter != "" %}<a href="{{ site.links.twitter }}" class="icon-link" title="X"><i class="fa-brands fa-x-twitter"></i></a>{% endif %}
</div>
{% if site.data.pi[0].education %}
<ul style="margin-top: var(--space-4);">
{% for education in site.data.pi[0].education %}
<li>{{ education | replace: "-","&#8211;" }}</li>
{% endfor %}
</ul>
{% endif %}
</div>
</div>
</div>

<div class="section-card">
<h3>Biography</h3>
<p>I am currently a postdoctoral researcher at the <a href="https://sites.psu.edu/nml1/">Penn State Neuromechanics Laboratory</a>, The Pennsylvania State University, at University Park, working with the laboratory’s principal investigator, Prof. <a href="https://hhd.psu.edu/contact/xiaogang-hu">Xiaogang Hu</a>. My postdoctoral work lies at the intersection of neuromechanics, neural interfaces, machine learning, and rehabilitation robotics.</p>
<p>I received my Ph.D. in Pattern Recognition and Intelligent Systems from the Institute of Automation, Chinese Academy of Sciences in June 2026, under the supervision of Prof. <a href="https://people.ucas.ac.cn/~houzengguang">Zengguang Hou</a> and Prof. <a href="https://people.ucas.edu.cn/~xhz">Xiaohu Zhou</a>. My doctoral research connects multimodal human manipulation modeling with brain-inspired robot learning. I study how high-level brain planning and low-level muscular execution interact, how manipulation can be represented across behavioral and neural scales, and how these representations can support efficient human–robot skill transfer. During my doctoral studies, I received the <strong>2026 Chinese Academy of Sciences President’s Special Award</strong>, the Academy’s highest honor for graduate students.</p>
<p>In November 2025, I was a visiting student at Victoria University of Wellington under the supervision of Prof. <a href="https://people.wgtn.ac.nz/bing.xue">Bing Xue</a>. Before my Ph.D., I received my B.S. in Automation from Tongji University (2017–2021), where I was named an <strong>Academic Star of Tongji University</strong>, the University’s highest honor for undergraduate students. I worked with Prof. <a href="https://ivcm.tongji.edu.cn/info/1100/1178.htm">Zhuping Wang</a> and Lingzhe Zhao on monocular depth estimation and visual odometry. I have also collaborated on bioinformatics research for cancer classification and prognosis prediction.</p>
<p>As of July 2026, I have published or received acceptance for 19 first/co-first-author papers, including six IEEE Transactions papers. I have served as lead drafter on five invention-patent applications, three of which have been granted.</p>
<p><strong>I welcome interdisciplinary research collaborations in neuromechanics, rehabilitation robotics, human–robot interaction, brain–computer interfaces, and brain-inspired robot learning.</strong></p>
</div>

<div class="section-card">
<h3>Doctoral Dissertation</h3>
<p><strong>Multimodal Representation of Human Manipulation Skills and Brain-Inspired Human–Robot Skill Transfer</strong><br>
<em>人类操作技能多模态表征与类脑人机技能迁移</em></p>
<p>The dissertation develops an end-to-end framework spanning cross-modal brain–muscle representation, multi-scale manipulation modeling, online EEG decoding, and bidirectional human–robot skill transfer under few- and sparse-demonstration settings.</p>
</div>

{% if site.data.grants %}
<div class="section-card">
<h3>Grants</h3>
<ul>
{% for grant in site.data.grants %}
<li>{{ grant.name }}</li>
{% endfor %}
</ul>
</div>
{% endif %}

{% if site.data.awards %}
<div class="section-card">
<h3>Awards</h3>
<ul>
{% for award in site.data.awards %}
<li>{{ award.name | replace: "-","&#8211;" }}</li>
{% endfor %}
</ul>
</div>
{% endif %}

<div class="section-card">
<h3>Teaching Experience</h3>
<p><strong>Teaching Assistant, Medical and Rehabilitation Robotics, University of Chinese Academy of Sciences, Spring 2026.</strong> Assisted with course instruction, class activities, and student learning.</p>
<p><strong>Research Mentor, University of Chinese Academy of Sciences, 2023–2026.</strong> Assisted faculty in supervising research projects for 15 undergraduate and master’s students; advised on project scoping, methodology, data analysis, and presentation.</p>
</div>

{% if site.data.funders %}
<div class="section-card">
<h4>Sponsors</h4>
<div class="sponsor-logos" style="display: flex; flex-wrap: wrap; align-items: center; justify-content: center; gap: var(--space-6);">
{% for funder in site.data.funders %}
<a href="{{ funder.url }}" target="_blank"><img src="{{ site.url }}{{ site.baseurl }}/images/{{ funder.image }}" alt="Funder logo" style="max-height: 80px; max-width: 200px; border-radius: 0;" loading="lazy"></a>
{% endfor %}
</div>
</div>
{% endif %}
