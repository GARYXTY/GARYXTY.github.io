---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

## Research

<div class="banner-frame" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/summary.jpg" alt="Research overview connecting human manipulation modeling to robot learning" loading="lazy">
<div class="banner-caption">My doctoral research connects multimodal manipulation representation, online neural decoding, and brain-inspired human–robot skill transfer.</div>
</div>

My long-term goal is to enable robots to acquire human-level manipulation skills. My doctoral dissertation addresses two connected questions: **How do humans perform manipulation?** and **How can robots learn those skills?** The resulting framework moves from multimodal human modeling to online intent decoding and sample-efficient robot learning.

<div class="research-grid">

<div class="research-card">
<div class="research-body">
<h4 class="research-title">Cross-modal brain–muscle modulation</h4>
<p class="research-desc">A Siamese and contrastive-learning framework aligns EEG and EMG in a shared space, while conditional generation models the mapping from brain activity to muscular response. Generated and real signals achieve a maximum mean discrepancy below 0.04, enabling temporal, spatial, and frequency-domain modulation analysis.</p>
</div>
</div>

<div class="research-card">
<div class="research-body">
<h4 class="research-title">Multi-scale motor modeling</h4>
<p class="research-desc">Complementary modalities describe manipulation from coarse to fine: monocular video for sequence-level kinematics (Pearson correlation &gt; 0.75), EEG for primitive-level brain activity (accuracy &gt; 80%), and EMG for action segmentation and rhythm modeling (accuracy &gt; 90%; Pearson correlation &gt; 0.8).</p>
</div>
</div>

<div class="research-card">
<div class="research-body">
<h4 class="research-title">Online skill decoding</h4>
<p class="research-desc">An “external-data pretraining → local denoising → individual adaptation” pipeline addresses limited samples, low signal-to-noise ratio, and inter-subject variability. Cross-dataset alignment improves accuracy by more than 10%, task-oriented denoising raises SNR by 0.82 dB, and online adaptation improves motor-imagery decoding by 3.6%.</p>
</div>
</div>

<div class="research-card">
<div class="research-body">
<h4 class="research-title">Multi-system human–robot skill transfer</h4>
<p class="research-desc">Inspired by memory-, reward-, and error-driven learning in the cortex, basal ganglia, and cerebellum, I combine self-supervised pretraining, reinforcement-learning post-training, and supervised human–robot collaboration. Relative to pure imitation learning, task success improves by 23% and operation steps fall by 36%.</p>
</div>
</div>

</div>

<div class="section-card">
<h3>Part I · Representing how humans manipulate</h3>
<p>Human manipulation is a hierarchical control process in which high-level planning in the brain is translated into low-level muscular execution. My work makes this implicit structure measurable through cross-modal EEG–EMG representation and generation, then uses video, EEG, and EMG to model behavior at the sequence, primitive, and action-command levels. This work has appeared in <em>IEEE Transactions on Cybernetics</em>, <em>IEEE Transactions on Industrial Informatics</em>, <em>IEEE Transactions on Emerging Topics in Computational Intelligence</em>, <em>IEEE Transactions on Medical Robotics and Bionics</em>, ACM Multimedia, and IJCNN.</p>
</div>

<div class="section-card">
<h3>Part II · Transferring how robots learn</h3>
<p>Human–robot skill transfer requires both robust intent decoding and efficient learning from scarce supervision. I first stabilize online EEG decoding through cross-dataset source alignment, reference-free denoising, and unsupervised adaptation. I then combine pretrained vision–language–action models with action-chunked policy optimization and sparse expert collaboration. Under sparse demonstrations, collaboration increases task success by 13.6%, while the collected expert interventions improve the robot policy by a further 3.8%.</p>
</div>

<div class="section-card">
<h3>Future directions</h3>
<ul>
<li><strong>Modeling human skill acquisition:</strong> characterize how behavioral and neural representations evolve from novice to expert.</li>
<li><strong>Multimodal online decoding:</strong> combine EEG with EMG, eye tracking, and other wearable signals for more reliable intent transfer.</li>
<li><strong>Process-level alignment:</strong> align human and robot learning trajectories, error-correction patterns, and convergence behavior—not only final task performance.</li>
</ul>
</div>
