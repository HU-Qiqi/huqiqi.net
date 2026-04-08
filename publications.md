---
layout: single
title: Publications
permalink: /publications/
author_profile: true
breadcrumbs: true
---

<style>
/* ===== Hide Sidebar on this page entirely ===== */
.sidebar { 
  display: none !important; 
}

/* ===== Center the page to 75% width ===== */
.page {
  width: 75% !important;
  max-width: 960px !important;
  margin: 0 auto !important;
  float: none !important;
  padding-right: 0 !important;
}

.page__inner-wrap {
  width: 100% !important;
}

/* ===== Publications Container ===== */
.pub-wrap {
  width: 100%;
  max-width: 960px;
  margin: 0 auto;
}

.pub-wrap > h2 { 
  margin: 0 0 12px; 
  font-weight: 800; 
  font-size: 2em;
  color: #1a1a1a;
}
.pub-wrap > p { margin: 0 0 24px; font-size: 1.1em; }
.pub-wrap > p a { 
  color: #2a59ff; 
  text-decoration: none; 
  border-bottom: 2px dashed rgba(42,89,255,.3); 
  font-weight: 600;
  transition: all 0.2s;
}
.pub-wrap > p a:hover { opacity: 0.8; border-bottom: 2px solid rgba(42,89,255,.8); }

/* ===== 重点：卡片式UI设计 ===== */
.pub {
  display: flex;
  align-items: flex-start;
  gap: 32px;
  margin: 0 auto 40px;
  padding: 30px;
  background: #ffffff;
  border-radius: 16px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05); /* 柔和阴影 */
  border: 1px solid rgba(0, 0, 0, 0.04);
  transition: transform 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275), box-shadow 0.3s ease;
  position: relative;
  overflow: hidden;
}

/* 悬停动画：卡片轻微上浮并加深阴影 */
.pub:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.08);
}

.pub .thumb {
  flex: 0 0 440px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 15px rgba(0,0,0,0.06);
}

.pub .thumb img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 12px;
  transition: transform 0.5s ease;
}

/* 悬停动画：图片轻微放大 */
.pub:hover .thumb img {
  transform: scale(1.03);
}

.pub .body {
  flex: 1;
  min-width: 0;
  line-height: 1.6;
}

/* 标题样式 */
.pub .body .title { 
  margin: 0 0 0.5rem; 
  font-size: 1.25rem;
  font-weight: 700; 
  color: #2c3e50;
  line-height: 1.4;
}

/* 作者/Advisor 徽章 — 青色 */
.pub .badge-advisor {
  display: inline-flex;
  align-items: center;
  gap: 5px;
  margin-top: 8px;
  padding: 4px 12px;
  background: #f0fdfa;
  color: #0f766e;
  font-size: 0.82rem;
  font-weight: 600;
  border-radius: 20px;
  border: 1px solid #ccfbf1;
}
.pub .badge-advisor i { color: #14b8a6; }

/* 元数据行 */
.pub .meta {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 0.6rem 0 1.2rem;
  padding-bottom: 14px;
  border-bottom: 1px solid #f1f5f9;
}

/* 通用 badge 基础 */
.pub .badge {
  display: inline-flex;
  align-items: center;
  gap: 5px;
  padding: 3px 10px;
  font-size: 0.78rem;
  font-weight: 600;
  border-radius: 20px;
  letter-spacing: 0.01em;
  white-space: nowrap;
}
.pub .badge i, .pub .badge .badge-icon { font-size: 0.72rem; opacity: 0.85; }

/* Type 类型 — 蓝色 */
.pub .badge-type {
  background: #eff6ff;
  color: #1d4ed8;
  border: 1px solid #dbeafe;
}

/* Venue 期刊/会议 — 紫色 */
.pub .badge-venue {
  background: #f5f3ff;
  color: #6d28d9;
  border: 1px solid #ede9fe;
}

/* Date 日期 — 暖色 */
.pub .badge-date {
  background: #fffbeb;
  color: #b45309;
  border: 1px solid #fef3c7;
}

/* IF 影响因子 — 翡翠绿 */
.pub .badge-if {
  background: #ecfdf5;
  color: #047857;
  border: 1px solid #d1fae5;
}

/* DOI — 灰色/深蓝 */
.pub .badge-doi {
  background: #f8fafc;
  color: #64748b;
  border: 1px solid #e2e8f0;
}

/* Button styles for links like Code, DOI, etc. */
.pub-btn {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 6px 14px;
  margin-right: 10px;
  margin-top: 12px;
  font-size: 0.88rem;
  font-weight: 600;
  color: #fff !important;
  background: #2a59ff;
  border-radius: 8px;
  text-decoration: none !important;
  border: none !important;
  transition: all 0.2s cubic-bezier(0.4, 0, 0.2, 1);
  box-shadow: 0 2px 4px rgba(42, 89, 255, 0.1);
}
.pub-btn:hover {
  background: #1e40b5;
  transform: translateY(-2px);
  box-shadow: 0 6px 15px rgba(42, 89, 255, 0.25);
}
.pub-btn:active {
  transform: translateY(0);
}
.pub-btn i {
  font-size: 0.95rem;
}
.pub-btn.btn-gh {
  background: #24292e;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.pub-btn.btn-gh:hover {
  background: #000;
  box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
}

/* 链接视觉统一 */
.pub .body a { 
  color: #2a59ff; 
  text-decoration: none; 
  border-bottom: 2px solid transparent; 
  transition: border-color 0.2s ease, opacity 0.2s ease; 
}
.pub .body a:hover { 
  border-bottom-color: rgba(42,89,255,1); 
  opacity: 0.9; 
}
.pub .body a:visited { 
  color: #1e40b5; 
}

/* 正文对其 */
.pub .body p {
  text-align: justify;
  text-justify: inter-word;
  hyphens: auto;
  color: #4a5568;
  font-size: 0.95rem;
  margin-bottom: 1rem;
}

.pub .body p:last-child {
  margin-bottom: 0;
}

/* 手机端响应式堆叠 */
@media (max-width: 768px) {
  .page { width: 95% !important; max-width: 100% !important; }
  .pub { flex-direction: column; padding: 20px; gap: 20px; }
  .pub .thumb { flex: auto; width: 100%; margin-bottom: 8px; }
  .pub .body .title { font-size: 1.15rem; }
}
</style>

<div class="pub-wrap">
  <h2>Publications / Projects</h2>
  <p><a href="/">← Back to Home</a></p>

  <div class="pub">
    <div class="thumb">
      <a href="/images/thermal_runaway_ml.png" class="image-popup" title="Thermal runaway severity ML framework">
        <img src="/images/thermal_runaway_ml.png" alt="Thermal runaway severity ML framework" loading="lazy">
      </a>
    </div>
    <div class="body">
      <p class="title">
        <a href="https://doi.org/10.1016/j.psep.2026.108830">
          Safety-oriented pre-event severity prediction of lithium-ion battery thermal runaway using interpretable machine learning
        </a><br>
        <span class="badge-advisor"><i class="fas fa-user-tie"></i> Advisor: Minqiang Wu, Hongda Du</span>
      </p>
      <div class="meta">
        <span class="badge badge-type"><i class="fas fa-file-alt"></i> Journal Article</span>
        <span class="badge badge-venue"><i class="fas fa-book"></i> Process Safety and Environmental Protection</span>
        <span class="badge badge-date"><i class="fas fa-calendar"></i> 2026.04</span>
        <span class="badge badge-doi"><i class="fas fa-link"></i> DOI: 10.1016/j.psep.2026.108830</span>
        <span class="badge badge-if"><i class="fas fa-chart-line"></i> IF 7.8</span>
      </div>
      <p>
        Proposed an <strong>interpretable machine-learning framework</strong> for <strong>pre-event prediction</strong> of lithium-ion battery thermal runaway severity using only structural and engineering metadata. 
        Constructed a hazard-oriented <strong>Severity Index</strong> integrating heat release and material ejection indicators, and developed a <strong>CatBoost-based classifier</strong> achieving <strong>81% accuracy</strong> with <strong>100% recall for High-severity events</strong>. 
        SHAP analysis provides physics-consistent interpretability to support safety-oriented decision-making.
      </p>
      <p>
        提出一种基于<strong>结构与工程元数据</strong>的锂离子电池<strong>热失控事前严重度预测框架</strong>，构建融合放热与喷射特征的<strong>危险导向严重度指数（Severity Index）</strong>，并基于 <strong>CatBoost</strong> 实现多分类预测，整体准确率达 <strong>81%</strong>，对高危事件识别率 <strong>100%</strong>。通过 SHAP 可解释分析揭示关键安全影响因素，支持风险导向电池安全评估。
      </p>
      <a href="https://github.com/HU-Qiqi/thermal-runaway-severity-prediction" class="pub-btn btn-gh"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>

  <div class="pub">
    <div class="thumb">
      <a href="/images/BTMS.png" class="image-popup" title="Hybrid BTMS">
        <img src="/images/BTMS.png" alt="Hybrid BTMS" loading="lazy">
      </a>
    </div>
    <div class="body">
      <p class="title">
        <a href="https://doi.org/10.1016/j.applthermaleng.2026.130845">
          Design and Multi-Objective Optimization of Efficient UAV Battery Thermal Management System Using PCM–Air Synergistic Cooling Strategy
        </a><br>
        <span class="badge-advisor"><i class="fas fa-user-tie"></i> Advisor: Minqiang Wu, Hongda Du</span>
      </p>
      <div class="meta">
        <span class="badge badge-type"><i class="fas fa-file-alt"></i> Journal Article</span>
        <span class="badge badge-venue"><i class="fas fa-book"></i> Applied Thermal Engineering</span>
        <span class="badge badge-date"><i class="fas fa-calendar"></i> 2026.03</span>
        <span class="badge badge-doi"><i class="fas fa-link"></i> DOI: 10.1016/j.applthermaleng.2026.130845</span>
        <span class="badge badge-if"><i class="fas fa-chart-line"></i> IF 6.9</span>
      </div>
      <p>Developed a <strong>PCM–air hybrid battery thermal management system (BTMS)</strong> for UAV lithium-ion batteries, achieving <strong>43.3% lower peak temperature (below 46.8 °C)</strong> with only <strong>22.2 wt% mass increase</strong>. Multi-factor optimization using an <strong>entropy–TOPSIS</strong> framework ensures a balance between cooling performance and lightweight design.</p>
      <p>提出了一种用于无人机锂离子电池的<strong>相变材料–风冷混合热管理系统（BTMS）</strong>，在总质量仅增加约 22 wt% 的情况下，使电池最高温度降低 43.3% 且保持低于 46.8 °C；通过 TOPSIS 优化实现轻量化与散热性能的平衡。</p>
    </div>
  </div>

  <div class="pub">
    <div class="thumb">
      <a href="/images/WM_encoder_decoder.png" class="image-popup" title="WM encoder-decoder schematic">
        <img src="/images/WM_encoder_decoder.png" alt="WM encoder-decoder schematic" loading="lazy">
      </a>
    </div>
    <div class="body">
      <p class="title">
        WM_encoder_decoder for Copyright Protection in Image-to-Image Tasks (Diffusion) · <a href="https://huqiqi.net/file/WM_encoder_decoder.pptx">PPT</a><br>
        <span class="badge-advisor"><i class="fas fa-user-tie"></i> Advisor: Feng Zheng</span>
      </p>
      <div class="meta">
        <span class="badge badge-type"><i class="fas fa-code"></i> Project / Code</span>
        <span class="badge badge-date"><i class="fas fa-calendar"></i> 2024.03–2024.12</span>
      </div>
      <p>Dual-protection scheme combining <strong>digital watermarking</strong> and <strong>adversarial perturbations</strong> in the latent space; precise embed/extract via a pre-trained encoder–decoder; robust, transferable, and high-quality without model fine-tuning.</p>
      <p>提出<strong>数字水印 + 对抗扰动</strong>的双重保护方案，在隐空间抑制篡改与生成操控；无需微调、具有良好迁移性与鲁棒性。</p>
      <a href="https://github.com/HU-Qiqi/WM_encoder_decoder" class="pub-btn btn-gh"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>

  <div class="pub">
    <div class="thumb">
      <a href="/images/SSNN.png" class="image-popup" title="SSNN framework">
        <img src="/images/SSNN.png" alt="SSNN framework" loading="lazy">
      </a>
    </div>
    <div class="body">
      <p class="title">
        <a href="https://ssrn.com/abstract=4625590">
          Privacy-Preserving Secure Shared Nearest Neighbor Clustering Scheme in Internet of Things
        </a><br><span class="badge-advisor"><i class="fas fa-user-tie"></i> Advisor: Hanlin Zhang</span>
      </p>
      <div class="meta">
        <span class="badge badge-type"><i class="fas fa-flask"></i> Research Project</span>
      </div>
      <p>Cloud-assisted, privacy-preserving <strong>SNN clustering</strong> using <strong>orthogonal matrix transformation</strong> and lightweight verification; cuts the most complex step from <strong>10.859 s → 1.183 s</strong> while preserving accuracy.</p>
      <p>云辅助的<strong>隐私保护 SNN 聚类</strong>，外包前以正交矩阵加密并可验证返回结果；在保持精度下显著降低本地计算开销。</p>
    </div>
  </div>

  <div class="pub">
    <div class="thumb">
      <a href="/images/SNLM.png" class="image-popup" title="SNLM denoising outsourcing">
        <img src="/images/SNLM.png" alt="SNLM denoising outsourcing" loading="lazy">
      </a>
    </div>
    <div class="body">
      <p class="title">Secure and Efficient Image Denoising Algorithm in Internet of Things<br><span class="badge-advisor"><i class="fas fa-user-tie"></i> Advisor: Hanlin Zhang</span></p>
      <div class="meta">
        <span class="badge badge-type"><i class="fas fa-graduation-cap"></i> Degree Thesis</span>
      </div>
      <p>Secure outsourcing for image denoising using <strong>Householder transformation</strong> and optimal-probability verification; maintains accuracy (<strong>PSNR ≈ 20–21 dB</strong>) while greatly reducing client computation.</p>
      <p>面向物联网图像去噪的<strong>安全外包方案</strong>，以豪斯霍尔德变换保护隐私并可验证结果；在 <strong>PSNR 约 20–21 dB</strong> 下显著降低端侧计算。</p>
    </div>
  </div>

</div>

<!-- ===== 自建全功能灯箱（不依赖任何第三方库） ===== -->
<div id="pub-lightbox" style="display:none; position:fixed; inset:0; z-index:99999; background:rgba(0,0,0,.88); justify-content:center; align-items:center; opacity:0; transition:opacity .3s ease;">
  <!-- 关闭按钮 ✕ -->
  <button id="pub-lb-close" style="position:absolute; top:18px; right:24px; z-index:100001; background:none; border:none; color:#fff; font-size:36px; cursor:pointer; line-height:1; padding:8px; opacity:.85; transition:opacity .2s;" title="Close (Esc)">✕</button>
  <!-- 左箭头 -->
  <button id="pub-lb-prev" style="position:absolute; left:16px; top:50%; transform:translateY(-50%); z-index:100001; background:rgba(255,255,255,.15); border:none; color:#fff; font-size:32px; width:52px; height:52px; border-radius:50%; cursor:pointer; display:flex; align-items:center; justify-content:center; backdrop-filter:blur(4px); transition:background .2s;" title="Previous">❮</button>
  <!-- 右箭头 -->
  <button id="pub-lb-next" style="position:absolute; right:16px; top:50%; transform:translateY(-50%); z-index:100001; background:rgba(255,255,255,.15); border:none; color:#fff; font-size:32px; width:52px; height:52px; border-radius:50%; cursor:pointer; display:flex; align-items:center; justify-content:center; backdrop-filter:blur(4px); transition:background .2s;" title="Next">❯</button>
  <!-- 图片 -->
  <img id="pub-lb-img" src="" alt="" style="max-width:88vw; max-height:88vh; border-radius:8px; box-shadow:0 8px 40px rgba(0,0,0,.5); object-fit:contain; transition:opacity .25s ease;">
  <!-- 标题 -->
  <div id="pub-lb-caption" style="position:absolute; bottom:20px; left:50%; transform:translateX(-50%); color:#ddd; font-size:14px; text-align:center; max-width:80vw; pointer-events:none;"></div>
  <!-- 计数器 -->
  <div id="pub-lb-counter" style="position:absolute; top:22px; left:24px; color:#aaa; font-size:14px; pointer-events:none;"></div>
</div>

<style>
  #pub-lb-close:hover { opacity:1; }
  #pub-lb-prev:hover, #pub-lb-next:hover { background:rgba(255,255,255,.3); }
</style>

<script>
(function() {
  // 收集所有 .pub-wrap 里的灯箱图片
  var images = [];
  var currentIndex = 0;

  function collectImages() {
    images = [];
    var links = document.querySelectorAll('.pub-wrap .image-popup');
    links.forEach(function(a) {
      images.push({
        src: a.getAttribute('href'),
        title: a.getAttribute('title') || a.querySelector('img').getAttribute('alt') || ''
      });
    });
  }

  var overlay  = document.getElementById('pub-lightbox');
  var img      = document.getElementById('pub-lb-img');
  var caption  = document.getElementById('pub-lb-caption');
  var counter  = document.getElementById('pub-lb-counter');
  var btnClose = document.getElementById('pub-lb-close');
  var btnPrev  = document.getElementById('pub-lb-prev');
  var btnNext  = document.getElementById('pub-lb-next');

  function showImage(idx) {
    if (idx < 0) idx = images.length - 1;
    if (idx >= images.length) idx = 0;
    currentIndex = idx;
    img.style.opacity = '0';
    setTimeout(function() {
      img.src = images[idx].src;
      caption.textContent = images[idx].title;
      counter.textContent = (idx + 1) + ' / ' + images.length;
      img.style.opacity = '1';
    }, 150);
  }

  function openLightbox(idx) {
    collectImages();
    overlay.style.display = 'flex';
    // 强制 reflow 让 transition 生效
    void overlay.offsetWidth;
    overlay.style.opacity = '1';
    document.body.style.overflow = 'hidden';
    showImage(idx);
  }

  function closeLightbox() {
    overlay.style.opacity = '0';
    setTimeout(function() {
      overlay.style.display = 'none';
      document.body.style.overflow = '';
    }, 300);
  }

  // 绑定所有图片链接的点击事件
  document.addEventListener('click', function(e) {
    var link = e.target.closest('.pub-wrap .image-popup');
    if (link) {
      e.preventDefault();
      e.stopPropagation();
      // 找到它在列表中的索引
      collectImages();
      var href = link.getAttribute('href');
      var idx = 0;
      for (var i = 0; i < images.length; i++) {
        if (images[i].src === href) { idx = i; break; }
      }
      openLightbox(idx);
    }
  }, true); // useCapture = true 来抢先拦截

  btnClose.addEventListener('click', closeLightbox);
  btnPrev.addEventListener('click', function() { showImage(currentIndex - 1); });
  btnNext.addEventListener('click', function() { showImage(currentIndex + 1); });

  // 点击背景关闭
  overlay.addEventListener('click', function(e) {
    if (e.target === overlay) closeLightbox();
  });

  // 键盘导航
  document.addEventListener('keydown', function(e) {
    if (overlay.style.display !== 'flex') return;
    if (e.key === 'Escape' || e.key === 'Esc') closeLightbox();
    if (e.key === 'ArrowLeft')  showImage(currentIndex - 1);
    if (e.key === 'ArrowRight') showImage(currentIndex + 1);
  });
})();
</script>
