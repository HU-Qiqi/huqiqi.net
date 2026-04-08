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

I am currently a **Master’s student at {{ site.owner.university }}**, working in the *{{ site.owner.lab }}* at the {{ site.owner.department }}, supervised by [**{{ site.owner.advisor }}**]({{ site.owner.advisor_url }}).
Previously, I was a visiting research student at the Southern University of Science and Technology (SUSTech), advised by [**Prof. Feng Zheng**](https://faculty.sustech.edu.cn/?tagid=fengzheng&iscss=1&snapid=1&orderby=date&go=1&lang=en)(a recipient of the National Excellent Young Scientist Award), where I worked on trustworthy diffusion models and content security in AIGC. I received my Bachelor’s degree in Information Security from Qingdao University, where I conducted research under [**Prof. Hanlin Zhang**](https://cst.qdu.edu.cn/info/1072/7423.htm) — who completed his Ph.D. under [**Prof. Wei Yu**](https://www.towson.edu/fcsm/departments/computerinfosci/facultystaff/wyu.html), an NSF CAREER Awardee — focusing on privacy-preserving outsourcing computation and secure IoT systems. These experiences equipped me with solid research training in cybersecurity and trustworthy AI, providing a strong algorithmic foundation that now supports my interdisciplinary work in **AI for Energy and Sustainability**.

I am always open to discussions and collaborations — feel free to [**email me**](mailto:{{ site.owner.email }}).

---

## <i data-lucide="target" class="icon-rigorous"></i> Research Vision
My overarching goal is to harness **artificial intelligence and optimization** to accelerate innovation in **low-carbon and sustainable energy systems**.  
I aim to bridge the gap between *materials, systems, and decision-making* through **trustworthy, data-driven, and interpretable AI frameworks**.

---

## <i data-lucide="microscope" class="icon-rigorous"></i> Research Interests

### Thermal Management and Energy Safety
Previously, my research focused on thermal management of lithium-ion batteries, which naturally motivated my current interest in **AI-driven energy systems**.
- Investigating mechanisms for suppressing thermal runaway in lithium-ion batteries and developing **PCM-based hybrid cooling strategies**  
- Thermal management of LIBs under high-power discharge conditions using **finite element modeling** and **multiphysics simulation**  
- Applications in energy storage and electronic thermal control  

### AI for Energy Systems & Battery Storage
- Data-driven modeling and intelligent prediction of **battery energy storage safety**
- Intelligent optimization for **low-carbon, safe, and stable energy operation**
- ML-based modeling and optimization of energy systems and multi-energy networks 
- Scientific ML & generative models for physical processes in energy devices  


### Trustworthy AI & Secure Generative Models
- **Content safety for AIGC** using diffusion models — PGD-based adversarial defense and encoder–decoder watermarking  
- **Privacy-preserving in cloud computing and Internet of Things**, including cloud-assisted and IoT security with matrix transformation methods for image denoising and segmentation  
- Extending **trustworthy machine learning** and robust optimization techniques toward **digital low-carbon energy applications**

---

## <i data-lucide="graduation-cap" class="icon-rigorous"></i> Academic Background
- **M.Eng. in Environmental Science and New Energy Technology**, Shenzhen International Graduate School, Tsinghua University  
- Visiting Research Student, Department of Computer Science and Engineering, SUSTech  
- **B.Eng. in Information Security**, School of Computer Science and Technology, Qingdao University

---

## <i data-lucide="megaphone" class="icon-rigorous"></i> News and Updates
- **2026.03** – Our paper on interpretable prediction of lithium-ion battery thermal runaway severity was accepted by *Process Safety and Environmental Protection* ([DOI](https://doi.org/10.1016/j.psep.2026.108830))
- **2026.03** – Our paper on UAV battery thermal management optimization using PCM–air cooling was accepted by *Applied Thermal Engineering* ([DOI](https://doi.org/10.1016/j.applthermaleng.2026.130845))
- **2026.03** – Successfully updated my AI-powered digital research workflow (See [Blog post](https://huqiqi.net/blogs/2026_Mar))
- **2026.02** – Started preparing a comprehensive review on phase-change-material-based thermal management for lithium-ion batteries
- **2025.11** – Initiated research on AI-driven early warning of lithium-ion battery thermal runaway
- **2025.09** – Studied thermal management of lithium-ion batteries under high-rate discharge using coupled PCM and air cooling
- **2025.05** – Investigated the effects of PCM-assisted air cooling on thermal runaway propagation in lithium-ion battery modules
- **2024.03** – Explored copyright protection in diffusion-based image-to-image generation


---

## <i data-lucide="code-2" class="icon-rigorous"></i> Skills / Research Toolkit
- **Programming:** Python, MATLAB, C, LaTeX  
- **Frameworks:** PyTorch, TensorFlow (for deep learning), scikit-learn (for machine learning) 
- **Tools:** Linux, VSCode, Anaconda, COMSOL, Microsoft Office  
- **Languages:** Chinese (Native), English (Fluent)


<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=uv82N_7dV3rkBt0dfztE_3a8xjOEZQwsnE6OqptIpDE&cl=ffffff&w=a"></script>
