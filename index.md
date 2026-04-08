---
layout: page
---
<style>
  .styled-list {
    list-style: disc !important;
    padding-left: 20px !important;
  }
  .styled-list li {
    padding-left: 0 !important;
    color: #333332 !important;
  }
  .styled-list li::before {
    display: none !important;
  }
  /* About Me 图片响应式 */
  .about-me-photo {
    float: right;
    width: 300px;
    margin: 0 0 20px 30px;
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    opacity: 0.95;
    filter: brightness(0.98);
  }
  @media (max-width: 600px) {
    .about-me-photo {
      width: 30% !important;
      margin: 0 0 10px 15px !important;
    }
  }
</style>
<div class="hero-section">
  <div class="hero-content">
    <h1>Hi, I'm {{ site.owner.name }} </h1>
    <ul class="styled-list" style="margin-top: 20px;">
      <li><i data-lucide="graduation-cap" class="icon-rigorous"></i> Master’s student at Tsinghua University (SIGS), working on AI for Energy & Sustainability</li>
      <li><i data-lucide="flask-conical" class="icon-rigorous"></i> <strong>Research:</strong> thermal safety modeling, AI-accelerated low-carbon energy systems, diffusion models, trustworthy machine learning</li>
      <li><i data-lucide="wrench" class="icon-rigorous"></i> <strong>Technical strengths:</strong> PyTorch, scientific ML, optimization, thermal modeling and multiphysics simulation</li>
      <li><i data-lucide="target" class="icon-rigorous"></i> <strong>Seeking PhD (Fall 2027)</strong> in Energy-AI, Battery Safety & Thermal Modeling, Scientific ML for Multiphysics Systems, and Physical Generative Models</li>
      <li><i data-lucide="mail" class="icon-rigorous"></i> <strong>Email:</strong> chelseyhu111@gmail.com</li>
    </ul>
    <div class="meta-container" style="margin-top: 25px;">
      <span class="chip chip-journal"><i data-lucide="flask-conical" class="icon-rigorous" style="margin-right: 4px; width: 14px; height: 14px; color: inherit;"></i> AI-accelerated Energy Systems</span>
      <span class="chip chip-if"><i data-lucide="target" class="icon-rigorous" style="margin-right: 4px; width: 14px; height: 14px; color: inherit;"></i> Seeking PhD (Fall 2027)</span>
    </div>
  </div>
</div>

# About Me

<img src="/images/2.jpg" alt="Profile Picture" class="about-me-photo">

I am currently a **Master’s student at {{ site.owner.university }}**, working in the {{ site.owner.lab }} at the {{ site.owner.department }}, supervised by [**{{ site.owner.advisor }}**]({{ site.owner.advisor_url }}).
Previously, I was a visiting student at the Southern University of Science and Technology (SUSTech), advised by [**Prof. Feng Zheng**](https://faculty.sustech.edu.cn/?tagid=fengzheng&iscss=1&snapid=1&orderby=date&go=1&lang=en)(a recipient of the National Excellent Young Scientist Award), where I worked on trustworthy diffusion models and content security in AIGC. I received my Bachelor’s degree in Information Security from Qingdao University, where I conducted research under [**Prof. Hanlin Zhang**](https://cst.qdu.edu.cn/info/1072/7423.htm) — who completed his Ph.D. under [**Prof. Wei Yu**](https://www.towson.edu/fcsm/departments/computerinfosci/facultystaff/wyu.html), an NSF CAREER Awardee — focusing on privacy-preserving outsourcing computation and secure IoT systems. These experiences equipped me with solid research training in cybersecurity and trustworthy AI, providing a strong algorithmic foundation that now supports my interdisciplinary work in **AI for Energy and Sustainability**.

I am always open to discussions and collaborations — feel free to [**email me**](mailto:{{ site.owner.email }}).

---

## <i data-lucide="target" class="icon-rigorous"></i> Research Vision
My overarching goal is to harness **artificial intelligence and optimization** to accelerate innovation in **low-carbon and sustainable energy systems**.  
I aim to bridge the gap between *materials, systems, and decision-making* through **trustworthy, data-driven, and interpretable AI frameworks**.

---

<div class="research-grid">
  <div class="research-card">
    <h3><i data-lucide="thermometer" class="icon-rigorous" style="width:1.3em;height:1.3em;"></i> Thermal Safety & Safety</h3>
    <p>Investigating thermal runaway mechanisms and PCM-based hybrid cooling strategies using finite element modeling and multiphysics simulation for lithium-ion battery safety.</p>
  </div>
  <div class="research-card">
    <h3><i data-lucide="zap" class="icon-rigorous" style="width:1.3em;height:1.3em;"></i> AI for Energy Systems</h3>
    <p>Data-driven modeling for battery energy storage safety, intelligent optimization for low-carbon energy operations, and scientific ML for physical processes in energy devices.</p>
  </div>
  <div class="research-card">
    <h3><i data-lucide="shield-check" class="icon-rigorous" style="width:1.3em;height:1.3em;"></i> Trustworthy AI & AIGC</h3>
    <p>Content safety for AIGC using diffusion models, privacy-preserving in IoT/Cloud, and extending robust optimization toward digital low-carbon energy applications.</p>
  </div>
</div>

---

## <i data-lucide="graduation-cap" class="icon-rigorous"></i> Academic Background

<div class="timeline">
  <div class="timeline-item">
    <span class="timeline-date">2024.09 — Present </span>
    <div class="timeline-content">
      <strong>M.Eng. in Environmental Science and New Energy Technology</strong><br>
      Shenzhen International Graduate School, Tsinghua University
    </div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2024.03 — 2024.08 </span>
    <div class="timeline-content">
      <strong>Visiting Research Student</strong><br>
      Department of Computer Science and Engineering, SUSTech
    </div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2020.09 — 2024.06 </span>
    <div class="timeline-content">
      <strong>B.Eng. in Information Security</strong><br>
      School of Computer Science and Technology, Qingdao University
    </div>
  </div>
</div>

---

## <i data-lucide="megaphone" class="icon-rigorous"></i> News and Updates

<div class="timeline">
  <div class="timeline-item">
    <span class="timeline-date">2026.03</span>
    <div class="timeline-content">Our paper on interpretable prediction of lithium-ion battery thermal runaway severity was accepted by <strong>Process Safety and Environmental Protection</strong> (<a href="https://doi.org/10.1016/j.psep.2026.108830">DOI</a>)</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2026.03</span>
    <div class="timeline-content">Our paper on UAV battery thermal management optimization using PCM–air cooling was accepted by <strong>Applied Thermal Engineering</strong> (<a href="https://doi.org/10.1016/j.applthermaleng.2026.130845">DOI</a>)</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2026.03</span>
    <div class="timeline-content">Successfully updated my AI-powered digital research workflow (See <a href="https://huqiqi.net/blogs/2026_Mar">Blog post</a>)</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2026.02</span>
    <div class="timeline-content">Started preparing a comprehensive review on phase-change-material-based thermal management for lithium-ion batteries</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2025.11</span>
    <div class="timeline-content">Initiated research on AI-driven early warning of lithium-ion battery thermal runaway</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2025.09</span>
    <div class="timeline-content">Studied thermal management of lithium-ion batteries under high-rate discharge using coupled PCM and air cooling</div>
  </div>
</div>


---

## <i data-lucide="code-2" class="icon-rigorous"></i> Skills / Research Toolkit

<div class="skill-tag-container">
  <span class="skill-tag">Python</span>
  <span class="skill-tag">MATLAB</span>
  <span class="skill-tag">C</span>
  <span class="skill-tag">LaTeX</span>
  <span class="skill-tag">PyTorch</span>
  <span class="skill-tag">TensorFlow</span>
  <span class="skill-tag">scikit-learn</span>
  <span class="skill-tag">Linux</span>
  <span class="skill-tag">Git</span>
  <span class="skill-tag">VSCode</span>
  <span class="skill-tag">Anaconda</span>
  <span class="skill-tag">COMSOL</span>
  <span class="skill-tag">English (Fluent)</span>
</div>


<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=uv82N_7dV3rkBt0dfztE_3a8xjOEZQwsnE6OqptIpDE&cl=ffffff&w=a"></script>
