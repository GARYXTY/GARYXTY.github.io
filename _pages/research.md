---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

## Research

<div class="banner-frame" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/summary.png" alt="Research overview connecting human manipulation modeling to robot learning" loading="lazy">
<div class="banner-caption">My research connects human sensorimotor modeling, online skill decoding, and human-inspired robot learning.</div>
</div>

My overall goal is to enable robots to perform and learn manipulation tasks using insights from human motor learning. I first model the hierarchical structure of human manipulation—from high-level brain planning to low-level muscular execution—and then transfer those representations and learning mechanisms to robots.

<div class="research-grid">

<div class="research-card">
<div class="research-body">
<h4 class="research-title">Cross-modal brain–muscle modulation</h4>
<p class="research-desc">I align EEG and EMG signals in a shared representation space through proxy cross-modal generation and motor classification. The resulting models make abstract cortical–muscular control measurable and provide interpretable accounts consistent with cognitive neuroscience findings.</p>
</div>
</div>

<div class="research-card">
<div class="research-body">
<h4 class="research-title">Multi-scale motor modeling</h4>
<p class="research-desc">To reflect the hierarchy of manipulation, I use complementary modalities at multiple scales: video for sequence-level analysis, EEG for primitive-level decoding, and EMG for action-level segmentation and rhythm modeling.</p>
</div>
</div>

<div class="research-card">
<div class="research-body">
<h4 class="research-title">Online skill decoding</h4>
<p class="research-desc">My skill-decoding pipeline combines source-imaging-based cross-electrode alignment, task-driven signal denoising, and adaptive data- and representation-level alignment. Online updates support rapid calibration despite limited, noisy, and variable biosignal data.</p>
</div>
</div>

<div class="research-card">
<div class="research-body">
<h4 class="research-title">Multi-module robot learning</h4>
<p class="research-desc">Inspired by the complementary roles of the cerebellum, basal ganglia, and cortex, I study collaborative imitation, reward-driven policy optimization, and memory-driven self-learning for sample-efficient transfer and zero-shot skill acquisition.</p>
</div>
</div>

</div>

<div class="section-card">
<h3>Stage 1 · Human manipulation modeling</h3>
<p>Human manipulation has a hierarchical organization: high-level planning in the brain and low-level execution through the muscular system. My work makes this implicit sensorimotor structure explicit through cross-modal brain–muscle representations and multi-scale video, EEG, and EMG models. Results have appeared in <em>IEEE Transactions on Cybernetics</em>, <em>IEEE Transactions on Medical Robotics and Bionics</em>, <em>IEEE Transactions on Emerging Topics in Computational Intelligence</em>, <em>IEEE Transactions on Industrial Informatics</em>, ACM Multimedia, and IJCNN.</p>
</div>

<div class="section-card">
<h3>Stage 2 · Human–machine skill transfer</h3>
<p>Transferring human skills to robots requires robust decoding from limited, low-SNR data and learning systems that can improve from sparse demonstrations. I combine online skill decoding with collaborative imitation, policy optimization, and generative self-refinement to form a practical basis for bidirectional human–robot learning.</p>
</div>
