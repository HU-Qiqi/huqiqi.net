---
layout: page
permalink: /cn/index.html
title: 主页中文版
---

<style>
  .hero-section h1 {
    color: #2c3e50;
  }
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
    <h1>你好，我是{{ site.owner.name_cn }} </h1>
    <ul class="styled-list" style="margin-top: 20px;">
      <li><i data-lucide="graduation-cap" class="icon-rigorous"></i> 清华大学深圳国际研究生院硕士在读</li>
      <li><i data-lucide="flask-conical" class="icon-rigorous"></i> <strong>研究领域：</strong> 能源AI、锂离子电池热安全建模、扩散模型、鲁棒机器学习</li>
      <li><i data-lucide="wrench" class="icon-rigorous"></i> <strong>技术栈：</strong> PyTorch、科学机器学习、优化算法、热建模与多物理场仿真</li>
      <li><i data-lucide="target" class="icon-rigorous"></i> <strong>寻求（2027年秋季）博士机会</strong>，目标方向：能源AI、电池安全与热建模、物理系统科学机器学习与生成式模型</li>
      <li><i data-lucide="mail" class="icon-rigorous"></i> <strong>邮箱：</strong> chelseyhu111@gmail.com</li>
    </ul>
    <div class="meta-container" style="margin-top: 25px;">
      <span class="chip chip-journal"><i data-lucide="flask-conical" class="icon-rigorous" style="margin-right: 4px; width: 14px; height: 14px; color: inherit;"></i> AI for Energy Systems & Storage Safety</span>
      <span class="chip chip-if"><i data-lucide="target" class="icon-rigorous" style="margin-right: 4px; width: 14px; height: 14px; color: inherit;"></i> 目标申请 2027 Fall PhD</span>
    </div>
  </div>
</div>

### 个人介绍

<img src="/images/2.jpg" alt="Profile Picture" class="about-me-photo">

我是胡齐齐，2002年生，目前就读于**{{ site.owner.university_cn }}{{ site.owner.department_cn }}**，攻读环境科学与新能源技术专业硕士学位，师从[**{{ site.owner.advisor_cn }}**]({{ site.owner.advisor_url }})，在**{{ site.owner.lab_cn }}**开展研究。我目前的研究聚焦于**人工智能与储能的交叉领域（AI for Energy Storage）**，探索利用数据驱动与优化方法推动低碳能源技术创新。  

此前，我曾在南方科技大学[**郑锋教授**](https://faculty.sustech.edu.cn/?tagid=fengzheng&iscss=1&snapid=1&orderby=date&go=2)领导的视觉智能与感知课题组访问交流，研究可信扩散模型与AIGC内容安全。 本科毕业于青岛大学计算机科学技术学院信息安全专业，在[**张翰林教授**](https://cst.qdu.edu.cn/info/1072/7423.htm)指导下从事隐私保护与物联网安全研究。 张教授师从[**Wei Yu 教授**](https://www.towson.edu/fcsm/departments/computerinfosci/facultystaff/wyu.html)（NSF CAREER Award获得者）。 这段经历为我奠定了扎实的算法与安全研究基础，也激发了我将**人工智能方法应用于能源科学与低碳系统建模**的兴趣。

欢迎通过[**邮件**](mailto:{{ site.owner.email }})与我联系，无论是科研合作还是学术讨论。

---

### <i data-lucide="book-open" class="icon-rigorous"></i> 教育背景

<div class="timeline">
  <div class="timeline-item">
    <span class="timeline-date">2023 — 至今</span>
    <div class="timeline-content">
      <strong>工学硕士</strong><br>
      清华大学深圳国际研究生院，环境科学与新能源技术专业
    </div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2024 — 2025</span>
    <div class="timeline-content">
      <strong>访问学生</strong><br>
      南方科技大学，工学院计算机科学与工程系
    </div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2019 — 2023</span>
    <div class="timeline-content">
      <strong>工学学士</strong><br>
      青岛大学计算机科学技术学院，信息安全专业
    </div>
  </div>
</div>

---

### <i data-lucide="target" class="icon-rigorous"></i> 研究愿景
我希望结合**人工智能、优化与能源科学**，构建面向低碳与可持续能源系统的智能决策与建模方法，以**数据驱动、可解释且鲁棒的AI框架**，连接材料热机理、系统运行与**能源安全控制**。

---

<div class="research-grid">
  <div class="research-card">
    <h3><i data-lucide="zap" class="icon-rigorous" style="width:1.3em;height:1.3em;"></i> 能源AI</h3>
    <p>聚焦电池储能系统的<strong>数据驱动建模</strong>、安全预警与智能优化，探索物理过程的科学机器学习与生成式模型。</p>
  </div>
  <div class="research-card">
    <h3><i data-lucide="thermometer" class="icon-rigorous" style="width:1.3em;height:1.3em;"></i> 电池热管理与能源安全</h3>
    <p>研究锂离子电池热失控抑制机制、高倍率放电热行为PCM耦合等冷却策略，利用<strong>多物理场仿真</strong>提升能源安全。</p>
  </div>
  <div class="research-card">
    <h3><i data-lucide="shield-check" class="icon-rigorous" style="width:1.3em;height:1.3em;"></i> 鲁棒优化</h3>
    <p>曾经研究 AIGC 内容安全（Diffusion模型水印/对抗防御）及物联网隐私保护，未来希望将<strong>鲁棒优化</strong>应用于数字能源系统。</p>
  </div>
</div>

---

### <i data-lucide="megaphone" class="icon-rigorous"></i> 最新动态

<div class="timeline">
  <div class="timeline-item">
    <span class="timeline-date">2026.03</span>
    <div class="timeline-content">一作论文关于锂离子电池热失控预警的研究被 <strong>Process Safety and Environmental Protection</strong> 接收（<a href="https://doi.org/10.1016/j.psep.2026.108830">DOI</a>）</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2026.03</span>
    <div class="timeline-content">一作论文关于无人机电池热管理优化的研究被 <strong>Applied Thermal Engineering</strong> 接收（<a href="https://doi.org/10.1016/j.applthermaleng.2026.130845">DOI</a>）</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2026.03</span>
    <div class="timeline-content">成功更新了基于AI工具的数字化研究工作流（详见<a href="https://huqiqi.net/blogs/2026_Mar">博客</a>）。</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2026.02</span>
    <div class="timeline-content">开始“锂离子电池相变材料热管理的系统性综述”研究</div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2025.11</span>
    <div class="timeline-content">开始“基于人工智能的锂离子电池热失控预警”研究</div>
  </div>
</div>

---

### <i data-lucide="user-check" class="icon-rigorous"></i> 学术服务
- *Journal of Computer Security (CCF-B)* 审稿人  

---

### <i data-lucide="history" class="icon-rigorous"></i> 研究经历

<div class="timeline">
  <div class="timeline-item">
    <span class="timeline-date">2024.01 – 2024.12</span>
    <div class="timeline-content">
      <strong>访问研究生</strong><br>
      南方科技大学计算机系，可信扩散模型与AIGC内容安全
    </div>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">2021.01 – 2021.11</span>
    <div class="timeline-content">
      <strong>本科科研实习</strong><br>
      青岛大学计算机学院，隐私保护与安全外包计算
    </div>
  </div>
</div>

---

### <i data-lucide="code-2" class="icon-rigorous"></i> 技能与科研工具

<div class="skill-group">
  <span class="skill-title">编程语言</span>
  <div class="skill-tag-container">
    <span class="skill-tag">Python</span>
    <span class="skill-tag">MATLAB</span>
    <span class="skill-tag">C</span>
    <span class="skill-tag">LaTeX</span>
  </div>
</div>

<div class="skill-group">
  <span class="skill-title">框架与库</span>
  <div class="skill-tag-container">
    <span class="skill-tag">PyTorch</span>
    <span class="skill-tag">TensorFlow</span>
    <span class="skill-tag">scikit-learn</span>
  </div>
</div>

<div class="skill-group">
  <span class="skill-title">科研与仿真工具</span>
  <div class="skill-tag-container">
    <span class="skill-tag">Linux</span>
    <span class="skill-tag">Git</span>
    <span class="skill-tag">VSCode</span>
    <span class="skill-tag">Anaconda</span>
    <span class="skill-tag">COMSOL</span>
  </div>
</div>

<div class="skill-group">
  <span class="skill-title">语言能力</span>
  <div class="skill-tag-container">
    <span class="skill-tag">中文（母语）</span>
    <span class="skill-tag">英语（流利）</span>
  </div>
</div>

