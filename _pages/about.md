---
layout: plain-home
permalink: /
title: "Jie Wang"
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap');

  :root {
    --text: #222;
    --muted: #666;
    --border: #ddd;
    --link: #DB7069;
    --bg: rgba(255, 255, 255, 0.5);
    --soft: rgba(255, 255, 255, 0.25);
  }

  html {
    background: var(--bg);
    color: var(--text);
    font-family: 'Inter', Arial, Helvetica, sans-serif;
    font-size: 16px;
    line-height: 1.55;
  }

  body {
    margin: 0;
  }

  .page {
    width: min(92vw, 920px);
    margin: 0 auto;
    padding: clamp(28px, 5vw, 48px) clamp(18px, 4vw, 32px) 64px;
  }

  a {
    color: var(--link);
    text-decoration: none;
  }

  a:hover {
    color: #e08680;
    text-decoration: underline;
  }

  header {
    display: grid;
    grid-template-columns: minmax(0, 1fr) clamp(190px, 24vw, 240px);
    gap: clamp(22px, 4vw, 40px);
    align-items: start;
    margin-bottom: 24px;
  }

  .portrait {
    width: clamp(185px, 23vw, 225px);
    height: clamp(185px, 23vw, 225px);
    object-fit: cover;
    border-radius: 50%;
    margin-left: -42px;
    margin-top: -18px;
  }

  h1 {
    font-size: 33px;
    line-height: 1.15;
    font-weight: 500;
    margin: 0 0 4px;
  }

  .pronunciation {
    font-size: 13.5px;
    color: var(--muted);
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    gap: 7px;
  }

  .contact {
    margin: 18px 0 0;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    column-gap: 22px;
    row-gap: 10px;
  }

  .contact-email {
    display: inline-block;
    color: var(--muted);
    font-size: 14px;
    letter-spacing: 0;
    white-space: nowrap;
  }

  .contact-links {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 14px;
    font-size: 13px;
    font-weight: 500;
    letter-spacing: 0;
    text-transform: none;
  }

  .contact-links a {
    color: var(--muted);
    opacity: 0.95;
  }

  .contact-links a:hover {
    color: var(--link);
    text-decoration: none;
  }

  nav {
    display: flex;
    gap: 28px;
    margin: 8px 0 30px;
    padding: 10px 0;
    border-top: 1px solid rgba(116, 106, 155, 0.22);
    border-bottom: 1px solid rgba(116, 106, 155, 0.22);
    font-size: 12px;
    letter-spacing: 0;
    text-transform: uppercase;
    font-weight: 600;
  }

  nav a {
    color: var(--link);
    transition: color 0.2s ease, opacity 0.2s ease;
  }

  nav a:hover {
    opacity: 0.7;
    text-decoration: none;
  }

  section {
    margin: 36px 0 40px;
  }

  .keywords {
    margin-top: 14px;
    color: var(--muted);
    font-size: 15px;
    letter-spacing: 0;
  }

  .joining-note,
  .awards-highlight {
    margin-top: 18px;
    padding: 12px 14px;
    border-left: 2px solid rgba(219, 112, 105, 0.32);
    background: rgba(219, 112, 105, 0.045);
    color: #4d4747;
    font-size: 14px;
    line-height: 1.7;
    border-radius: 0 8px 8px 0;
  }

  .awards-highlight {
    margin-bottom: 20px;
    max-width: 760px;
    border-left-color: rgba(219, 112, 105, 0.34);
    background: rgba(219, 112, 105, 0.05);
    font-size: 14.5px;
    line-height: 1.8;
    color: #444;
  }

  h2 {
    font-size: 16px;
    font-weight: 600;
    letter-spacing: 0;
    text-transform: uppercase;
    color: var(--link);
    margin: 0 0 14px;
  }

  h2::after {
    content: "";
    display: inline-block;
    width: 34px;
    height: 1px;
    background: var(--border);
    margin-left: 10px;
    vertical-align: middle;
  }

  h3 {
    font-size: 16px;
    font-weight: 600;
    margin: 18px 0 8px;
  }

  p {
    margin: 0 0 12px;
  }

  ul {
    margin: 8px 0 0 20px;
    padding: 0;
  }

  li {
    margin: 5px 0;
  }

  .news li {
    margin-bottom: 6px;
  }

  .pub {
    margin-bottom: 14px;
  }

  .pub-title {
    font-weight: 600;
  }

  .pub-meta,
  .note {
    color: var(--muted);
  }

  .photo-strip {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    margin-top: 20px;
  }

  .photo-strip img {
    width: 100%;
    aspect-ratio: 16 / 7;
    object-fit: cover;
    border-radius: 8px;
    opacity: 0.94;
    filter: saturate(0.92) contrast(0.97);
  }

  .photo-strip .photo-poster {
    object-position: 50% 38%;
  }

  footer {
    border-top: 1px solid var(--border);
    margin-top: 34px;
    padding-top: 12px;
    color: var(--muted);
    font-size: 13px;
  }

  @media (max-width: 640px) {
    .page {
      width: auto;
      padding: 28px 18px 46px;
    }

    header {
      grid-template-columns: 1fr;
      gap: 14px;
    }

    .portrait {
      width: 185px;
      height: 185px;
      margin-left: 0;
      margin-top: 0;
    }

    nav {
      flex-wrap: wrap;
      gap: 12px;
    }

    nav a {
      width: auto;
      margin: 0;
    }
  }
</style>

<main class="page">
  <header>
    <div>
      <h1>Jie Wang</h1>
      <div class="pronunciation">王颉 · Computer Science Undergraduate</div>
      <p>
        Fan-Gongxiu Honors College<br>
        College of Computer Science<br>
        Beijing University of Technology
      </p>

      <div class="contact">
        <a class="contact-email" href="mailto:wangjie@emails.bjut.edu.cn">wangjie@emails.bjut.edu.cn</a>
        <div class="contact-links">
          <a href="https://github.com/wangjie0326">GitHub</a>
          <a href="/publications/">Publications</a>
          <a href="/portfolio/">Projects</a>
          <a href="/cv/">CV</a>
        </div>
      </div>
    </div>
    <img class="portrait" src="/images/bio-graph.jpg" alt="Jie Wang">
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#research">Research</a>
    <a href="#publications">Publications</a>
    <a href="#education">Education</a>
    <a href="#awards">Awards</a>
    <a href="#photos">Photos</a>
  </nav>

  <section id="home">
    <p>
      I am a junior undergraduate student majoring in <strong>Computer Science and Technology</strong> at the <a href="https://cs.bjut.edu.cn">College of Computer Science</a> and <a href="https://fgx-hc.bjut.edu.cn">Fan-Gongxiu Honors College</a>, <a href="https://www.bjut.edu.cn">Beijing University of Technology</a>.
    </p>
    <p>
      I am currently a Research Assistant at the <a href="https://biai.bjut.edu.cn">Beijing Institute of Artificial Intelligence</a>, advised by <a href="https://duo67.github.io">Associate Researcher Jinduo Liu</a>. My research focuses on multimodal learning, large language model security, and reinforcement learning.
    </p>
    <p>
      In Summer 2025, I visited North Carolina State University as a Research Assistant under Dr. Muhammad Shahzad, where our work on WiFi-based gesture recognition won 1st Place in the Poster Symposium (1/50).
    </p>
    <p class="keywords">
      LLM security · multimodal learning · reinforcement learning · vision-tactile perception
    </p>
    <p class="joining-note" style="max-width: 760px;">
      I am interested in building AI systems that are safe, robust, and grounded across modalities, especially efficient safety evaluation for large language models and multimodal perception.
    </p>
  </section>

  <section id="research">
    <h2>Research</h2>
    <p>
      My current research studies safe and robust AI systems across language, vision, and tactile modalities.
    </p>
    <ul>
      <li>LLM security and red-teaming: evaluating and improving model robustness against policy-violating or adversarial behavior.</li>
      <li>Multimodal learning: studying cross-modal safety alignment and perception with vision and tactile signals.</li>
      <li>Reinforcement learning: decision-making optimization and knowledge graph reasoning.</li>
    </ul>
  </section>

  <section id="news">
    <h2>News</h2>
    <ul class="news">
      <li>[2026-07] Our paper <strong>EviGuard: Evidence-Guided Connector Intervention for Cross-Modal Safety Unlearning in Multimodal LLMs</strong> was accepted to <strong>ACM MM 2026</strong>.</li>
      <li>[2026-05] Paper <strong>BEACON: Budget-Efficient Discovery of Policy Violations in Large Language Models via Cognitive-Guided Monte Carlo Tree Search</strong> accepted to <strong>IJCAI 2026</strong>.</li>
      <li>[2026-03] Two papers on multimodal safety alignment and vision-tactile perception submitted to CCF-A conferences.</li>
      <li>[2026-01] Paper on efficient LLM safety evaluation is under review at a top-tier AI conference.</li>
      <li>[2025-11] Received Fan-Gongxiu Honors Scholarship and Xiaomi Entrepreneur Scholarship.</li>
      <li>[2025-08] Won 1st Place in Poster Symposium at U.S. GEARS Research Program @ NCSU for AttentiveCSI.</li>
      <li>[2025-08] Awarded National 2nd Prize in China Robot Competition and Artificial Intelligence Contest.</li>
      <li>[2025-02] Invention patent on intelligent vehicle decision-making passed preliminary examination.</li>
    </ul>
  </section>

  <section id="publications">
    <h2>Selected Publications</h2>
    <div class="pub">
      <span class="pub-title">BEACON: Budget-Efficient Discovery of Policy Violations in Large Language Models via Cognitive-Guided Monte Carlo Tree Search</span><br>
      <span>Xinyi Huang, <strong>Jie Wang</strong>, Pengrui Xiang, Jinduo Liu (Corresponding author)</span><br>
      <span class="pub-meta">IJCAI 2026</span>
    </div>
    <div class="pub">
      <span class="pub-title">EviGuard: Evidence-Guided Connector Intervention for Cross-Modal Safety Unlearning in Multimodal LLMs</span><br>
      <span>Xinyi Huang, Pengrui Xiang, <strong>Jie Wang</strong>, Jinduo Liu (Corresponding author)</span><br>
      <span class="pub-meta">ACM MM 2026</span>
    </div>
    <div class="pub">
      <span class="pub-title">A Multimodal Benchmark for Vision-Tactile Perception and Recognition</span><br>
      <span><strong>Jie Wang</strong>, et al.</span><br>
      <span class="pub-meta">Dataset Track · under review</span>
    </div>
    <p class="note" style="margin-top: 18px;">
      A more complete publication list is available on the <a href="/publications/">publications page</a>.
    </p>
  </section>

  <section id="education">
    <h2>Education</h2>
    <ul>
      <li><strong>Beijing University of Technology</strong>, B.Eng. in Computer Science and Technology, Sept 2023 - June 2027 (expected). GPA: 4.00 / 4.00; Rank: 1st / 60.</li>
      <li><strong>North Carolina State University</strong>, Visiting Research Assistant, June 2025 - August 2025. Supervised by Dr. Muhammad Shahzad.</li>
    </ul>
  </section>

  <section id="awards">
    <h2>Awards</h2>
    <div class="awards-highlight">
      Best Poster Award (1st Place), U.S. GEARS Research Program @ NCSU (2025) · Fan-Gongxiu Honors Scholarship (2025) · Xiaomi Entrepreneur Scholarship (2025) · Study Excellence Scholarship (2024, 2025) · National 2nd Prize, China Robot Competition and Artificial Intelligence Contest (2025) · Outstanding Student Honor, BJUT (2024)
    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <p>
      Python, C/C++, Java, MATLAB, Verilog HDL · PyTorch, TensorFlow, HuggingFace Transformers, Scikit-learn · Linux, Git/GitHub, Docker, LaTeX.
    </p>
    <p class="note">
      Languages: Chinese (native), English (IELTS 7.0; Reading & Writing 7.0).
    </p>
  </section>

  <section id="photos">
    <h2>Photos</h2>
    <div class="photo-strip">
      <img src="/images/IMG_5696.jpeg" alt="Jie Wang at Golden Gate Bridge" loading="lazy">
      <img class="photo-poster" src="/images/IMG_7335.jpeg" alt="Jie Wang presenting a research poster" loading="lazy">
      <img src="/images/IMG_7866.jpeg" alt="Jie Wang at a tennis court" loading="lazy">
    </div>
  </section>

  <footer>
    Last updated: July 2026.
  </footer>
</main>
