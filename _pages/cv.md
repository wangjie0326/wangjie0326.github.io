---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-section {
  margin: 30px 0;
}

.cv-section h2 {
  color: #2c3e50;
  font-size: 24px;
  font-weight: 700;
  border-bottom: 3px solid #3498db;
  padding-bottom: 10px;
  margin-bottom: 20px;
}

.cv-item {
  margin: 20px 0;
}

.cv-item h3 {
  color: #2c3e50;
  font-size: 18px;
  font-weight: 600;
  margin-bottom: 5px;
}

.cv-meta {
  color: #7f8c8d;
  font-size: 14px;
  margin-bottom: 10px;
}

.cv-details {
  margin-left: 20px;
}

.cv-details li {
  margin: 8px 0;
  color: #555;
}

.skill-tag {
  display: inline-block;
  background: #ecf0f1;
  color: #2c3e50;
  padding: 5px 12px;
  margin: 5px 5px 5px 0;
  border-radius: 4px;
  font-size: 14px;
}

.contact-info {
  text-align: center;
  margin: 20px 0;
  padding: 20px;
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  border-radius: 8px;
}

.contact-info p {
  margin: 5px 0;
  color: #2c3e50;
}
</style>

<div class="contact-info">
  <p><strong>📍 Location:</strong> Beijing, China</p>
  <p><strong>📞 Phone:</strong> (+86) 157-3835-4608</p>
  <p><strong>✉️ Email:</strong> wangjie@emails.bjut.edu.cn</p>
  <p><strong>🌐 Website:</strong> <a href="https://wangjie0326.github.io">wangjie0326.github.io</a></p>
</div>

---

<div class="cv-section">

## 🎓 Education

<div class="cv-item">
<h3>Beijing University of Technology (BJUT)</h3>
<div class="cv-meta">Bachelor of Engineering in Computer Science and Technology | Sept 2023 – June 2027 (Expected)</div>
<div class="cv-meta">Fan-Gongxiu Honors College | Beijing, China</div>
<ul class="cv-details">
  <li><strong>GPA:</strong> 4.00/4.00 | 95.72/100 | <strong>Rank: 1st/60</strong></li>
  <li><strong>Honors:</strong> Fan-Gongxiu Honors College (Top 40 selected from 3000+ students)</li>
  <li><strong>Major Courses:</strong> Advanced Mathematics (100), Probability and Statistics (98), Data Structures & Algorithms (98), High-level Programming Language (97), Set Theory & Graph Theory (99), Pattern Recognition (97), Computer Organization (97)</li>
</ul>
</div>

<div class="cv-item">
<h3>North Carolina State University (NCSU)</h3>
<div class="cv-meta">Visiting Research Assistant | June 2025 – August 2025</div>
<div class="cv-meta">Supervised by Dr. Muhammad Shahzad | Raleigh, NC, U.S.</div>
<ul class="cv-details">
  <li>Developed <strong>AttentiveCSI</strong>: a WiFi-based Channel State Information Gesture Recognition with Attention-Enhanced CNN-LSTM Network</li>
  <li>Awarded <strong>First Place in Poster Symposium</strong> (1/50 participants)</li>
</ul>
</div>

</div>

---

<div class="cv-section">

## 📝 Invention Patent & Publications

<div class="cv-item">
<h3>[1] BEACON: Budget-Efficient Discovery of Policy Violations in LLMs via Cognitive-Guided Monte Carlo Tree Search</h3>
<div class="cv-meta"><strong>Jie Wang</strong>, et al.</div>
<div class="cv-meta">CCF-A AI Conference, Under Review | January 2026</div>
</div>

<div class="cv-item">
<h3>[2] EviGuard: Evidence-Guided Connector Intervention for Cross-Modal Safety Unlearning in Multimodal LLMs</h3>
<div class="cv-meta"><strong>Jie Wang</strong>, et al.</div>
<div class="cv-meta">CCF-A Multimedia Conference, Under Review | March 2026</div>
</div>

<div class="cv-item">
<h3>[3] VidTouch: A Multimodal Benchmark Dataset for Dynamic Visuo-Tactile Fabric Recognition</h3>
<div class="cv-meta"><strong>Jie Wang</strong>, et al.</div>
<div class="cv-meta">CCF-A Multimedia Conference (Dataset Track), Under Review | March 2026</div>
</div>

<div class="cv-item">
<h3>[4] A Lane Change Decision-Making Method for Intelligent Vehicles in Foggy Days Based on Dynamic Game Theory</h3>
<div class="cv-meta"><strong>Jie Wang</strong> (First Author), et al.</div>
<div class="cv-meta">Invention Patent ID: 202510141836.1 | Passed Preliminary Examination | February 2025</div>
</div>

</div>

---

<div class="cv-section">

## 🔬 Project Experience

<div class="cv-item">
<h3>Cross-Modal Safety Unlearning in Multimodal LLMs (EviGuard)</h3>
<div class="cv-meta">Funded by the Honors Cornerstone Design Program | January 2026 – April 2026 | Beijing, China</div>
<ul class="cv-details">
  <li>Identified that cross-modal risk in multimodal LLMs concentrates in a low-rank subspace at the visual-language connector, motivating targeted intervention rather than uniform suppression</li>
  <li>Reduced over-refusal rate (SARR) from 30.3% to 22.3%; on OOD benchmark SIUO, achieved 9.8% ASR and 68.0% Safe & Effective rate vs. best baseline (81.2% / 8.0%)</li>
  <li><strong>Contributions:</strong> Experimental framework design, algorithm implementation, ablation analysis, manuscript writing</li>
</ul>
</div>

<div class="cv-item">
<h3>Budget-Constrained Safety Evaluation of LLMs (BEACON)</h3>
<div class="cv-meta">Funded by the Honors Keystone Design Program | November 2025 – January 2026 | Beijing, China</div>
<ul class="cv-details">
  <li>Reframed LLM safety evaluation as budget-constrained failure discovery; formalized efficiency-oriented metrics (k-FDQ, NDA, CCR, DV) capturing discovery timing and harm category diversity beyond traditional ASR</li>
  <li>Built Cognitive-Guided MCTS with defense persona profiling and diversity-aware selection; achieved 85.5–100% ASR across 6 frontier LLMs, discovering failures <strong>3.7× faster</strong> than strongest baseline (k-FDQ 26 vs. 95)</li>
  <li><strong>Contributions:</strong> Problem formulation, attack design, experimental analysis, manuscript preparation</li>
</ul>
</div>

<div class="cv-item">
<h3>Vision-based Tactile Perception via Multimodal Learning (VidTouch)</h3>
<div class="cv-meta">Funded by Chinese National College Students' Innovation Program | December 2024 – June 2025 | Beijing, China</div>
<ul class="cv-details">
  <li>Built VidTouch (145 fabric categories, 440 RGB images / 440 tactile videos), the first dynamic multimodal benchmark for fabric recognition; supports multi-label classification, cross-modal retrieval, and zero-shot generalization</li>
  <li>Designed X3D + EfficientNet + MLP fusion pipeline achieving <strong>98.6%</strong> in-category accuracy; revealed zero-shot generalization bottleneck (41.3%), positioning VidTouch as an open challenge benchmark</li>
  <li><strong>Contributions:</strong> Dataset construction, model training and optimization, and experimental validation</li>
</ul>
</div>

</div>

---

<div class="cv-section">

## 🏆 Selected Awards and Honors

<div class="cv-item">
<ul class="cv-details">
  <li><strong>Fan-Gongxiu Honors Scholarship</strong> (November 2025)</li>
  <li><strong>Xiaomi Entrepreneur Scholarship</strong> (November 2025)</li>
  <li><strong>Study Excellence Scholarship</strong> (September 2024 & 2025)</li>
  <li><strong>Outstanding Student Honor</strong> (April 2024)</li>
  <li><strong>National 2nd Prize</strong> - China Robot Competition and Artificial Intelligence Contest (August 2025)</li>
</ul>
</div>

</div>

---

<div class="cv-section">

## 💻 Technical Skills

<div style="margin: 20px 0;">
<div style="margin-bottom: 15px;">
  <strong>Programming Languages:</strong><br>
  <span class="skill-tag">Python</span>
  <span class="skill-tag">C/C++</span>
  <span class="skill-tag">Java</span>
  <span class="skill-tag">MATLAB</span>
  <span class="skill-tag">Verilog HDL</span>
</div>

<div style="margin-bottom: 15px;">
  <strong>AI/ML Frameworks:</strong><br>
  <span class="skill-tag">PyTorch</span>
  <span class="skill-tag">TensorFlow</span>
  <span class="skill-tag">HuggingFace Transformers</span>
  <span class="skill-tag">Scikit-learn</span>
</div>

<div style="margin-bottom: 15px;">
  <strong>Development Tools:</strong><br>
  <span class="skill-tag">Linux</span>
  <span class="skill-tag">Git/GitHub</span>
  <span class="skill-tag">Docker</span>
  <span class="skill-tag">Vibe Coding</span>
</div>

<div>
  <strong>Languages:</strong><br>
  <span class="skill-tag">English — IELTS 7.0 (Reading & Writing both 7.0)</span>
  <span class="skill-tag">Chinese — Native</span>
</div>
</div>

</div>

---

<p style="text-align: center; color: #7f8c8d; margin-top: 40px;">
  <em>Last updated: April 2026</em><br>
  <a href="/files/JieWang_CV.pdf" style="color: #3498db;">Download PDF Version</a>
</p>
