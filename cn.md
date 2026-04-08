---
layout: page
permalink: /cn/index.html
title: 主页中文版
---

<style>
  .hero-section, .hero-section * {
    color: #333332;
  }
  .hero-section {
    background: transparent !important;
    box-shadow: none !important;
    border: none !important;
    border-radius: 0 !important;
    padding: 0 !important;
    margin-bottom: 30px;
  }
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
  /* Professional Icon Styling */
  .icon-rigorous {
    width: 1.1em;
    height: 1.1em;
    vertical-align: -0.2em;
    margin-right: 0.5em;
    color: #4a5568; /* Slate grey for a rigorous look */
    stroke-width: 2;
  }
  h3 .icon-rigorous {
    width: 1.25em;
    height: 1.25em;
    vertical-align: -0.25em;
    color: #2c3e50;
    margin-right: 0.6em;
  }
</style>
<div class="hero-section">
  <div class="hero-content">
    <h1>你好，我是{{ site.owner.name_cn }} </h1>
    <ul class="styled-list" style="margin-top: 20px;">
      <li><i data-lucide="graduation-cap" class="icon-rigorous"></i> 清华大学深圳国际研究生院硕士在读，研究数字能源与低碳可持续方向</li>
      <li><i data-lucide="flask-conical" class="icon-rigorous"></i> <strong>研究领域：</strong> 电池热安全建模、AI赋能的低碳能源系统、扩散模型、可信机器学习</li>
      <li><i data-lucide="wrench" class="icon-rigorous"></i> <strong>技术栈：</strong> PyTorch、科学机器学习、优化算法、热建模与多物理场仿真</li>
      <li><i data-lucide="target" class="icon-rigorous"></i> <strong>寻求（2027年秋季）博士机会</strong>，目标方向：能源AI、电池安全与热建模、物理系统科学机器学习与生成式模型</li>
      <li><i data-lucide="mail" class="icon-rigorous"></i> <strong>邮箱：</strong> chelseyhu111@gmail.com</li>
    </ul>
    <div class="meta-container" style="margin-top: 25px;">
      <span class="chip chip-journal"><i data-lucide="flask-conical" class="icon-rigorous" style="margin-right: 4px; width: 14px; height: 14px; color: inherit;"></i> AI-accelerated Energy Systems</span>
      <span class="chip chip-if"><i data-lucide="target" class="icon-rigorous" style="margin-right: 4px; width: 14px; height: 14px; color: inherit;"></i> 目标申请 2027 Fall PhD</span>
    </div>
  </div>
</div>

### 个人介绍

<img src="/images/2.jpg" alt="Profile Picture" class="about-me-photo">

我是胡齐齐，2002年生，目前就读于**{{ site.owner.university_cn }}{{ site.owner.department_cn }}**，攻读环境科学与新能源技术专业硕士学位，师从[**{{ site.owner.advisor_cn }}**]({{ site.owner.advisor_url }})，在**{{ site.owner.lab_cn }}**开展研究。我目前的研究聚焦于**人工智能与可持续能源系统的交叉领域（AI for Energy Systems & Low-carbon Innovation）**，探索利用数据驱动与优化方法推动低碳能源技术创新。  

此前，我曾在南方科技大学[**郑锋教授**](https://faculty.sustech.edu.cn/?tagid=fengzheng&iscss=1&snapid=1&orderby=date&go=2)领导的视觉智能与感知课题组访问交流，研究可信扩散模型与AIGC内容安全。 本科毕业于青岛大学计算机科学技术学院信息安全专业，在[**张翰林教授**](https://cst.qdu.edu.cn/info/1072/7423.htm)指导下从事隐私保护与物联网安全研究。 张教授师从[**Wei Yu 教授**](https://www.towson.edu/fcsm/departments/computerinfosci/facultystaff/wyu.html)（NSF CAREER Award获得者）。 这段经历为我奠定了扎实的算法与安全研究基础，也激发了我将**人工智能方法应用于能源科学与低碳系统建模**的兴趣。

欢迎通过[**邮件**](mailto:{{ site.owner.email }})与我联系，无论是科研合作还是学术讨论。

---

### <i data-lucide="book-open" class="icon-rigorous"></i> 教育背景
- **2023 – 至今**  工学硕士，清华大学深圳国际研究生院，环境科学与新能源技术专业
- **2024 – 2025**  访问学生，南方科技大学，工学院计算机科学与工程系 
- **2019 – 2023**  工学学士，青岛大学计算机科学技术学院，信息安全专业  

---

### <i data-lucide="target" class="icon-rigorous"></i> 研究愿景
我希望结合**人工智能、优化与能源科学**，构建面向**低碳与可持续能源系统**的智能决策与建模方法， 以数据驱动和可解释的AI框架，连接能源材料、系统运行与碳减排决策。

---

### <i data-lucide="microscope" class="icon-rigorous"></i> 研究兴趣

- <i data-lucide="zap" class="icon-rigorous" style="width: 1em; height: 1em;"></i> **能源系统与储能电池的人工智能（AI for Energy Systems & Battery Storage）**  
  - 电池储能系统安全的**数据驱动建模**与**智能预测**
  - 面向低碳、安全与稳定运行的**能源系统智能优化**
  - 能源系统与多能网络的**机器学习**建模与优化
  - 能源器件**物理过程**的科学机器学习与**生成式模型**

- <i data-lucide="thermometer" class="icon-rigorous" style="width: 1em; height: 1em;"></i> **热管理与能源安全**  
  先前，我的研究聚焦于**锂离子电池热管理**，这也自然延伸出我对**AI驱动能源系统**的兴趣。  
  - 锂离子电池热失控抑制机制与相变材料（PCM）冷却策略  
  - 高倍率放电下的热行为分析与仿真  
  - 有限元建模与多物理场模拟  

- <i data-lucide="shield-check" class="icon-rigorous" style="width: 1em; height: 1em;"></i> **可信人工智能与生成模型安全**
  - 基于扩散模型的 AIGC 内容安全研究：利用 PGD 对抗攻击防御和数字水印方法  
  - 云计算与物联网中的隐私保护：包括云端辅助与物联网安全，采用矩阵变换方法实现图像去噪与分割  
  - 将可信机器学习与鲁棒性优化技术拓展应用于数字低碳能源系统

---

### <i data-lucide="megaphone" class="icon-rigorous"></i> 最新动态
- **2026.03**  一作论文关于锂离子电池热失控预警的研究被 *Process Safety and Environmental Protection* 接收（[DOI](https://doi.org/10.1016/j.psep.2026.108830)）
- **2026.03**  一作论文关于无人机电池热管理优化的研究被 *Applied Thermal Engineering* 接收（[DOI](https://doi.org/10.1016/j.applthermaleng.2026.130845)）
- **2026.03**  成功更新了基于AI工具的数字化研究工作流（详见[博客](https://huqiqi.net/blogs/2026_Mar)）。
- **2026.02**  开始“锂离子电池相变材料热管理的系统性综述”研究
- **2025.11**  开始“基于人工智能的锂离子电池热失控预警”研究
- **2025.09**  开展“基于相变-风冷耦合的锂离子电池高倍率放电热管理”研究  
- **2025.05**  开展“PCM耦合风冷对电池热失控传播的影响机制”研究  
- **2024.03**  开展“基于Diffusion模型的图生图版权保护”研究  

---

### <i data-lucide="user-check" class="icon-rigorous"></i> 学术服务
- *Journal of Computer Security (CCF-B)* 审稿人  

---

### <i data-lucide="history" class="icon-rigorous"></i> 研究经历
- *2024.01 – 2024.12*  访问研究生，南方科技大学计算机系，可信扩散模型与AIGC内容安全  
- *2021.01 – 2021.11*  本科科研实习，青岛大学计算机学院，隐私保护与安全外包计算  

---

### <i data-lucide="code-2" class="icon-rigorous"></i> 技能与科研工具
我常用的科研开发与仿真工具包括：
- **编程语言：** Python、MATLAB、C、LaTeX  
- **框架与库：** PyTorch、TensorFlow（深度学习）、scikit-learn（机器学习）  
- **科研工具：** Linux、VSCode、Anaconda、COMSOL 多物理场仿真、Microsoft Office  
- **语言能力：** 中文（母语）、英文（流利）

