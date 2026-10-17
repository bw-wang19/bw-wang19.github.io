---
layout: about
title: home
permalink: /
subtitle: "Ph.D. Student at Tsinghua University · Large Language Models"

profile:
  align: right
  image: me.png
  image_circular: true
  more_info: >
    <p>Tsinghua University</p>
    <p>Tsinghua Shenzhen International Graduate School</p>

selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<p class="home-kicker">
  Model Merging & Distillation · Agentic RL · Self-Improving Agents
</p>

<p class="home-summary">
  I am a Ph.D. student in Electronic Science and Technology at
  <strong>Tsinghua University</strong>,
  Shenzhen International Graduate School.
  Previously, I received my bachelor's degree in Automation
  from Tsinghua University in 2023.
</p>

<p class="home-summary">
  My research interests include model merging and multi-teacher
  distillation, post-training and agentic reinforcement learning,
  and recursive self-improvement in agents.
</p>

<div class="home-actions" role="group" aria-label="Contact links">
  <a
    class="home-action home-action--primary"
    href="mailto:wangbw23@mails.tsinghua.edu.cn"
  >
    Email me
  </a>

<a
class="home-action home-action--secondary"
href="https://github.com/bw-wang19"
target="_blank"
rel="noopener noreferrer"

>

    GitHub

  </a>

<a
class="home-action home-action--secondary"
href="{{ '/assets/pdf/resume.pdf' | relative_url }}"
target="_blank"
rel="noopener noreferrer"

>

    CV

  </a>
</div>

<nav class="home-section-nav" aria-label="Page sections">
  <a href="#education-heading">Education</a>
  <a href="#research-heading">Research</a>
  <a href="#selected-work-heading">Publications</a>
  <a href="#experience-heading">Experience</a>
  <a href="#contact-heading">Contact</a>
</nav>

<section
  class="education-section experience-section"
  aria-labelledby="education-heading"
>
  <div class="experience-heading">
    <div>
      <h2 id="education-heading">Education</h2>
    </div>
  </div>

  <ol class="experience-list">
    <li class="experience-item">
      <p class="experience-period">
        <time datetime="2023-09">Sep 2023</time>
        <span aria-hidden="true">—</span>
        <span>Present</span>
      </p>

      <span class="experience-track" aria-hidden="true"></span>

      <article class="experience-details">
        <h3>Tsinghua University</h3>
        <p class="experience-role">
          Ph.D. student in Electronic Science and Technology
        </p>
        <p class="education-unit">
          Shenzhen International Graduate School
        </p>
      </article>
    </li>

    <li class="experience-item">
      <p class="experience-period">
        <time datetime="2019-08">Aug 2019</time>
        <span aria-hidden="true">—</span>
        <time datetime="2023-06">Jun 2023</time>
      </p>

      <span class="experience-track" aria-hidden="true"></span>

      <article class="experience-details">
        <h3>Tsinghua University</h3>
        <p class="experience-role">
          Bachelor's degree in Automation
        </p>
        <p class="education-unit">
          Department of Automation
        </p>
      </article>
    </li>

  </ol>
</section>

<section class="research-section" aria-labelledby="research-heading">
  <p class="research-eyebrow">Research</p>

  <div class="research-heading-row">
    <h2 id="research-heading">Research Interests</h2>
  </div>

  <div class="research-grid">
    <article class="research-card">
      <span class="research-card__number" aria-hidden="true">01</span>
      <h3>Model Merging &amp; Distillation</h3>
      <p>
        Integrating complementary capabilities from specialized models
        through parameter-space merging and multi-teacher
        on-policy distillation (MOPD).
      </p>
    </article>

    <article class="research-card">
      <span class="research-card__number" aria-hidden="true">02</span>
      <h3>Post-Training &amp; Agentic RL</h3>
      <p>
        Improving reasoning, tool use, and long-horizon decision-making
        through post-training and reinforcement learning
        in interactive environments.
      </p>
    </article>

    <article class="research-card">
      <span class="research-card__number" aria-hidden="true">03</span>
      <h3>Recursive Self-Improvement of Agents</h3>
      <p>
        Exploring recursive self-improvement (RSI), where agents
        iteratively refine their own code and workflows to improve
        subsequent rounds of learning and problem-solving.
      </p>
    </article>

  </div>
</section>

<section class="selected-work-section" aria-labelledby="selected-work-heading">
  <div class="selected-work-heading">
    <div>
      <p class="selected-work-eyebrow">Selected Work</p>
      <h2 id="selected-work-heading">Selected Publications</h2>
    </div>
  </div>

  <div class="selected-work-list">
    <article class="selected-work-item">
      <div class="selected-work-meta">
        <span class="selected-work-index">01</span>
        <span class="selected-work-venue">EMNLP 2025 · Main</span>
      </div>

      <div class="selected-work-content">
        <h3>
          RECALL: REpresentation-aligned Catastrophic-forgetting
          ALLeviation via Hierarchical Model Merging
        </h3>

        <p class="selected-work-authors">
          <strong>Bowen Wang</strong><sup>§</sup>,
          Haiyuan Wan<sup>§</sup>, Liwen Shi, Chen Yang,
          Peng He, Yue Ma, Haochen Han, Wenhao Li, Tiao Tan,
          Yongjian Li, Fangming Liu, Yifan Gong, Sheng Zhang
        </p>

        <p>
          Representation-aligned, layer-wise model merging that preserves
          knowledge across tasks without access to historical task data.
        </p>

        <p class="selected-work-note">§ Equal contribution.</p>

        <div class="selected-work-links">
          <a
            href="https://aclanthology.org/2025.emnlp-main.829/"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="RECALL paper (opens in a new tab)"
          >Paper</a>

          <a
            href="https://github.com/bw-wang19/RECALL"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="RECALL code (opens in a new tab)"
          >Code</a>
        </div>
      </div>
    </article>

    <article class="selected-work-item">
      <div class="selected-work-meta">
        <span class="selected-work-index">02</span>
        <span class="selected-work-venue">EMNLP 2026 · Oral</span>
      </div>

      <div class="selected-work-content">
        <h3>
          Self-Corrected Speech Reasoning: Diagnosing and Improving
          Condition Updating via PACER
        </h3>

        <p class="selected-work-authors">
          Zijie Zeng, Liwen Shi, Yunji, <strong>Bowen Wang</strong>,
          Nanjie Li, Xiaoyong Guo, Zeyu Chen, Xinzheng Sun,
          Xuyang Xiong, Haoyang Wu, Sheng Zhang
        </p>

        <p>
          Diagnoses condition-updating failures in speech reasoning.
          PACER reduces end-to-end errors by 39.8% on Qwen2.5-Omni-7B
          relative to the untrained baseline.
        </p>

        <p class="selected-work-note">
          Accepted · Paper link forthcoming.
        </p>
      </div>
    </article>

    <article class="selected-work-item">
      <div class="selected-work-meta">
        <span class="selected-work-index">03</span>
        <span class="selected-work-venue">EMNLP 2026 · Findings</span>
      </div>

      <div class="selected-work-content">
        <h3>
          GRAIL: Gradient-Reward Aligned Initialization for LoRA-based GRPO
        </h3>

        <p class="selected-work-authors">
          Liwen Shi, Zijie Zeng, <strong>Bowen Wang</strong>, Yunji,
          Zeyu Chen, Xinyu Shao, Xinzheng Sun, Xuyang Xiong,
          Haoyang Wu, Sheng Zhang
        </p>

        <p>
          Aligns LoRA initialization with reward-induced gradients to
          improve GRPO, without changing the training objective or
          adding trainable parameters.
        </p>

        <p class="selected-work-note">
          Accepted · Paper link forthcoming.
        </p>
      </div>
    </article>

  </div>
</section>

<section class="experience-section" aria-labelledby="experience-heading">
  <div class="experience-heading">
    <div>
      <p class="experience-eyebrow">Experience</p>
      <h2 id="experience-heading">Experience</h2>
    </div>
  </div>

  <ol class="experience-list">
    <li class="experience-item">
      <p class="experience-period">
        <time datetime="2025-11">Nov 2025</time>
        <span aria-hidden="true">—</span>
        <time datetime="2026-03">Mar 2026</time>
      </p>

      <span class="experience-track" aria-hidden="true"></span>

      <article
        class="experience-details"
        aria-labelledby="experience-tencent"
      >
        <header class="experience-details__header">
          <div>
            <h3 id="experience-tencent">Tencent · TiMi J1</h3>
            <p class="experience-role">
              Intern · Data Intelligence Team
            </p>
          </div>

          <p class="experience-location">Shenzhen, China</p>
        </header>

        <ul>
          <li>
            Contributed to the “Cheling”
            (<span lang="zh-CN">车灵</span>) LLM agent released in
            <span lang="zh-CN">QQ飞车手游</span>, developing
            post-training workflows for real-time game-state analysis,
            strategy suggestions, and persona-driven interaction.
          </li>

          <li>
            Built a dual-stream Qwen3-4B and CosyVoice3 LLM–TTS
            pipeline with vLLM streaming and WebSocket, reaching
            300–500 ms time to first response and approximately
            0.3 real-time factor.
          </li>
        </ul>
      </article>
    </li>

    <li class="experience-item">
      <p class="experience-period">
        <time datetime="2023-10">Oct 2023</time>
        <span aria-hidden="true">—</span>
        <time datetime="2025-09">Sep 2025</time>
      </p>

      <span class="experience-track" aria-hidden="true"></span>

      <article
        class="experience-details"
        aria-labelledby="experience-pcl"
      >
        <header class="experience-details__header">
          <div>
            <h3 id="experience-pcl">Peng Cheng Laboratory</h3>
            <p class="experience-role">
              Visiting Student · Intelligent Computing Research Department
            </p>
          </div>

          <p class="experience-location">Shenzhen, China</p>
        </header>

        <ul>
          <li>
            Developed RECALL, a representation-aligned hierarchical
            model-merging approach that uses layer-wise representation
            similarity to generate adaptive merging weights.
          </li>

          <li>
            Evaluated the method across five public NLP benchmarks in
            single-expert, multi-expert, and continual-learning settings.
          </li>
        </ul>
      </article>
    </li>

  </ol>
</section>

<section class="contact-cta" aria-labelledby="contact-heading">
  <div class="contact-cta__copy">
    <h2 id="contact-heading">Contact</h2>

    <p>
      Feel free to get in touch to discuss research
      or potential collaborations.
    </p>

  </div>

  <div class="contact-cta__actions">
    <a
      class="home-action contact-cta__primary"
      href="mailto:wangbw23@mails.tsinghua.edu.cn"
    >
      Email me
    </a>

    <a
      class="home-action contact-cta__secondary"
      href="{{ '/assets/pdf/resume.pdf' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="View CV (opens in a new tab)"
    >
      View CV
    </a>

  </div>
</section>
