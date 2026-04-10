---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* About me section - smaller font */
.about-section {
  font-size: 16px;
  line-height: 1.7;
  color: var(--global-text-color, #333);
}

/* News section with scrollbar */
.news-section {
  max-height: 220px;
  overflow-y: auto;
  padding-right: 8px;
  margin-bottom: 10px;
}
.news-section::-webkit-scrollbar {
  width: 6px;
}
.news-section::-webkit-scrollbar-track {
  background: #f1f1f1;
  border-radius: 3px;
}
.news-section::-webkit-scrollbar-thumb {
  background: #bbb;
  border-radius: 3px;
}
.news-section::-webkit-scrollbar-thumb:hover {
  background: #888;
}
.news-item {
  padding: 4px 0;
  font-size: 14px;
  border-bottom: 1px dashed #eee;
}
.news-item:last-child {
  border-bottom: none;
}
.news-date {
  font-weight: bold;
  color: #2a7ae2;
  min-width: 120px;
  display: inline-block;
}

/* Publications section with scrollbar and card style */
.pub-scroll-container {
  max-height: 800px;
  overflow-y: auto;
  padding-right: 8px;
}
.pub-scroll-container::-webkit-scrollbar {
  width: 6px;
}
.pub-scroll-container::-webkit-scrollbar-track {
  background: #f1f1f1;
  border-radius: 3px;
}
.pub-scroll-container::-webkit-scrollbar-thumb {
  background: #bbb;
  border-radius: 3px;
}
.pub-scroll-container::-webkit-scrollbar-thumb:hover {
  background: #888;
}

.pub-card {
  display: flex;
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 10px;
  padding: 16px;
  margin-bottom: 16px;
  transition: box-shadow 0.2s;
}
.pub-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
.pub-img {
  flex-shrink: 0;
  width: 180px;
  height: 120px;
  border-radius: 6px;
  overflow: hidden;
  margin-right: 18px;
  background: #e9ecef;
  display: flex;
  align-items: center;
  justify-content: center;
}
.pub-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.pub-img .placeholder {
  font-size: 36px;
  color: #adb5bd;
}
.pub-info {
  flex: 1;
  min-width: 0;
}
.pub-title {
  font-weight: 700;
  font-size: 15px;
  margin-bottom: 5px;
  line-height: 1.4;
}
.pub-title a {
  color: var(--global-text-color, #1a1a2e);
  text-decoration: none;
}
.pub-title a:hover {
  color: #2a7ae2;
}
.pub-authors {
  font-size: 13px;
  color: #555;
  margin-bottom: 3px;
}
.pub-venue {
  font-size: 13px;
  color: #2a7ae2;
  font-style: italic;
  margin-bottom: 8px;
}
.pub-links a {
  display: inline-block;
  padding: 3px 10px;
  margin-right: 6px;
  margin-bottom: 4px;
  font-size: 12px;
  border: 1px solid #dee2e6;
  border-radius: 4px;
  color: #495057;
  text-decoration: none;
  background: #fff;
  transition: all 0.15s;
}
.pub-links a:hover {
  background: #2a7ae2;
  color: #fff;
  border-color: #2a7ae2;
}

@media (max-width: 600px) {
  .pub-card {
    flex-direction: column;
  }
  .pub-img {
    width: 100%;
    height: 160px;
    margin-right: 0;
    margin-bottom: 12px;
  }
}

/* Dark mode adaptations */
html[data-theme="dark"] .about-section { color: #ffffff; }
html[data-theme="dark"] .about-section a { color: #0ea1c5; }
html[data-theme="dark"] .news-date { color: #0ea1c5; }
html[data-theme="dark"] .news-item { color: #eaeaea; border-bottom-color: #555; }
html[data-theme="dark"] .pub-card { background: #3a3a3a; border-color: #555; }
html[data-theme="dark"] .pub-title a { color: #eaeaea; }
html[data-theme="dark"] .pub-title a:hover { color: #0ea1c5; }
html[data-theme="dark"] .pub-authors { color: #ccc; }
html[data-theme="dark"] .pub-venue { color: #0ea1c5; }
html[data-theme="dark"] .pub-links a { background: #4a4a4a; color: #eaeaea; border-color: #666; }
html[data-theme="dark"] .pub-links a:hover { background: #0ea1c5; color: #fff; border-color: #0ea1c5; }
html[data-theme="dark"] .pub-img { background: #4a4a4a; }
html[data-theme="dark"] .pub-scroll-container::-webkit-scrollbar-track { background: #3a3a3a; }
html[data-theme="dark"] .pub-scroll-container::-webkit-scrollbar-thumb { background: #666; }
html[data-theme="dark"] .news-section::-webkit-scrollbar-track { background: #3a3a3a; }
html[data-theme="dark"] .news-section::-webkit-scrollbar-thumb { background: #666; }
</style>

<div class="about-section">
Hi, I'm <b>Chenxi Song</b>, currently a postdoctoral researcher at AGI Lab, Westlake University, supervised by Prof. <a href="https://icoz69.github.io/">Chi Zhang</a>. I received my Ph.D. degree in Engineering from Jilin University in 2024, where I focused on 3D Computer Vision and Computer Graphics under the supervision of Prof. <a href="https://dce.jlu.edu.cn/info/1066/7660.htm">Shigang Wang</a>, with co-supervision from Prof. <a href="https://wei-jian.github.io/about/">Jian Wei</a> and Prof. <a href="https://dce.jlu.edu.cn/info/1181/5220.htm">Yan Zhao</a>.
<br><br>
My current research interests lie in <b>3D & 4D scene and controllable video generation</b>. I am actively engaged in the academic community, serving as a reviewer for top-tier AI conferences and journals including NeurIPS, CVPR, ECCV, AAAI, MM, and T-CSVT.
I recently launched a lightweight world model project called <b><a href="https://worldforge-agi.github.io" style="color:inherit;text-decoration:underline;">WorldForge</a></b>. I will continue to focus on controllable video generation and world model research. Welcome to collaborate!
</div>

---

## News

<div class="news-section">
  <div class="news-item"><span class="news-date">Apr 2026</span> 🏆 <b>WorldForge</b> is selected as CVPR <span style="color:#ea3277;font-weight:bold;">Highlight</span>!</div>
  <div class="news-item"><span class="news-date">Feb 2026</span> 🎉 <b>5</b> papers are accepted by <b>CVPR 2026</b>!</div>
  <div class="news-item"><span class="news-date">Feb 2026</span> 🔥 <a href="https://github.com/Westlake-AGI-Lab/WorldForge" style="color:inherit;text-decoration:underline;">WorldForge</a> code is now open-sourced!</div>
  <div class="news-item"><span class="news-date">Sep 2025</span> 🔥 Released WorldForge, a training-free world model project.</div>
  <div class="news-item"><span class="news-date">Jan 2025</span> Joined Westlake University School of Engineering as a postdoctoral researcher.</div>
  <div class="news-item"><span class="news-date">Sep 2024</span> Graduated from Jilin University with Ph.D. degree.</div>
  <div class="news-item"><span class="news-date">May 2024</span> Our work FewarNet on sparse-view multi-view synthesis was published in T-CSVT.</div>
</div>

---

## Publications

You can also find my articles on <a href="https://scholar.google.com/citations?hl=zh-CN&user=rytyb7QAAAAJ">my Google Scholar profile</a>.

<div class="pub-scroll-container">

<!-- WorldForge -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/worldforge.gif" onerror="this.onerror=null;this.src='/images/paper/worldforge.png';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128293;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="https://arxiv.org/abs/2509.15130">WorldForge: Taming Video Models for 3D and 4D Generation via Zero-Shot Camera Control</a></div>
    <div class="pub-authors"><b>C Song</b>, Y Yang, T Zhao, R Li, C Zhang</div>
    <div class="pub-venue"><b>CVPR 2026 (Highlight)</b></div>
    <div class="pub-links">
      <a href="https://worldforge-agi.github.io">Page</a>
      <a href="https://arxiv.org/abs/2509.15130">PDF</a>
      <a href="https://github.com/Westlake-AGI-Lab/WorldForge">Code</a>
    </div>
  </div>
</div>

<!-- FewarNet -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/fewarnet.gif" onerror="this.onerror=null;this.src='/images/paper/fewarnet2.png';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128196;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="https://doi.org/10.1109/TCSVT.2024.3395447">FewarNet: An efficient few-shot view synthesis network based on trend regularization</a></div>
    <div class="pub-authors"><b>C Song</b>, S Wang, J Wei, Y Zhao</div>
    <div class="pub-venue">IEEE Transactions on Circuits and Systems for Video Technology 34 (10), 9264-9278, 2024</div>
    <div class="pub-links">
      <a href="https://doi.org/10.1109/TCSVT.2024.3395447">PDF</a>
    </div>
  </div>
</div>

<!-- SwitchCrafter -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/switchcraft.gif" onerror="this.onerror=null;this.src='/images/paper/switchcraft.mp4';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128196;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="#">SwitchCraft: Training-Free Multi-Event Video Generation with Attention Controls</a></div>
    <div class="pub-authors">Q Xu, <b>C Song</b><sup>†</sup>, Y Cai, C Zhang</div>
    <div style="font-size: 0.85em; color: #666;">(Project lead)</div>
    <div class="pub-venue"><b>CVPR 2026</b></div>
    <div class="pub-links">
      <a href="https://switchcraft-project.github.io/">Page</a>
      <a href="https://arxiv.org/abs/2602.23956">PDF</a>
      <a href="https://github.com/Westlake-AGI-Lab/SwitchCraft">Code</a>
    </div>
  </div>
</div>

<!-- Free-Lunch -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/freelunch.gif" onerror="this.onerror=null;this.src='/images/paper/freelunch.mp4';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128196;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="#">Free-Lunch Long Video Generation via Layer-Adaptive O.O.D Correction</a></div>
    <div class="pub-authors">J Tian, <b>C Song</b><sup>†</sup>, W Cheng, C Zhang</div>
    <div style="font-size: 0.85em; color: #666;">(Project lead)</div>
    <div class="pub-venue"><b>CVPR 2026</b></div>
    <div class="pub-links">
      <!-- <a href="https://flowdirector-edit.github.io/">Page</a> -->
      <a href="https://arxiv.org/abs/2603.25209">PDF</a>
      <a href="https://github.com/Westlake-AGI-Lab/FreeLOC">Code</a>
    </div>
  </div>
</div>

<!-- Wide-baseline -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/widebaseline.png" onerror="this.onerror=null;this.src='/images/paper/widebaseline.png';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128196;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="https://doi.org/10.1016/j.displa.2023.102503">Wide-baseline view synthesis for light-field display based on plane-depth-fused sweep volume</a></div>
    <div class="pub-authors"><b>C Song</b>, S Wang, J Wei, Y Zhao, R Zhang</div>
    <div class="pub-venue">Displays 79, 102503, 2023</div>
    <div class="pub-links">
      <a href="https://doi.org/10.1016/j.displa.2023.102503">PDF</a>
    </div>
  </div>
</div>

<!-- FlowDirector -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/flowdirector.gif" onerror="this.onerror=null;this.src='/images/paper/flowdirector.png';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128196;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="https://arxiv.org/abs/2506.05046">FlowDirector: Training-Free Flow Steering for Precise Text-to-Video Editing</a></div>
    <div class="pub-authors">G Li, Y Yang, <b>C Song</b>, C Zhang</div>
    <div class="pub-venue"><b>CVPR 2026</b></div>
    <div class="pub-links">
      <a href="https://flowdirector-edit.github.io/">Page</a>
      <a href="https://arxiv.org/abs/2506.05046">PDF</a>
      <a href="https://github.com/Westlake-AGI-Lab/FlowDirector">Code</a>
    </div>
  </div>
</div>

<!-- Fast3Dcache -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/fast3dcache.gif" onerror="this.onerror=null;this.src='/images/paper/fast3dcache.png';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128196;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="https://arxiv.org/abs/2511.22533">Fast3Dcache: Training-free 3D Geometry Synthesis Acceleration</a></div>
    <div class="pub-authors">M Yang, Y Yang, C Xu, <b>C Song</b>, Y Zuo, T Zhao, R Li, C Zhang</div>
    <div class="pub-venue"><b>CVPR 2026</b></div>
    <div class="pub-links">
    <a href="https://fast3dcache-agi.github.io">Page</a>
    <a href="https://arxiv.org/abs/2511.22533">PDF</a>
    <a href="https://github.com/Westlake-AGI-Lab/Fast3Dcache">Code</a>
    </div>
  </div>
</div>

<!-- AppAgentX -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/appagentx.gif" onerror="this.onerror=null;this.src='/images/paper/appagentx.png';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128196;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="https://arxiv.org/abs/2503.02268">AppAgentX: Evolving GUI agents as proficient smartphone users</a></div>
    <div class="pub-authors">W Jiang, Y Zhuang, <b>C Song</b>, X Yang, JT Zhou, C Zhang</div>
    <div class="pub-venue">arXiv preprint arXiv:2503.02268, 2025</div>
    <div class="pub-links">
    <a href="https://appagentx.github.io/">Page</a>
    <a href="https://arxiv.org/abs/2511.22533">PDF</a>
    <a href="https://github.com/Westlake-AGI-Lab/AppAgentX">Code</a>
    </div>
  </div>
</div>

<!-- DyWeight -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/dyweight.png" onerror="this.onerror=null;this.parentElement.innerHTML='<div class=placeholder>&#128293;</div>';" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="https://arxiv.org/abs/2603.11607">DyWeight: Dynamic Gradient Weighting for Few-Step Diffusion Sampling</a></div>
    <div class="pub-authors">T Zhao, M Lei, L Yuan, Y Yang, <b>C Song</b>, Y Wang, B Zhu, C Zhang</div>
    <div class="pub-venue">arXiv preprint arXiv:2603.11607, 2026</div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2603.11607">PDF</a>
      <a href="https://github.com/Westlake-AGI-Lab/DyWeight">Code</a>
    </div>
  </div>
</div>

<!-- Elemental image array -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/elemental.gif" onerror="this.onerror=null;this.src='/images/paper/elemental.png';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128196;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="#">Elemental image array generation based on BVH structure combined with spatial partition and display optimization</a></div>
    <div class="pub-authors">T Li, S Wang, J Wei, Y Zhao, <b>C Song</b>, R Zhang</div>
    <div class="pub-venue">Displays 84, 102784, 2024</div>
    <div class="pub-links">
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S0141938224001483">PDF</a>
    </div>
  </div>
</div>

<!-- Efficiently enhancing -->
<div class="pub-card">
  <div class="pub-img"><img src="/images/paper/lightfield.jpg" onerror="this.onerror=null;this.src='/images/paper/lightfield.png';this.onerror=function(){this.parentElement.innerHTML='<div class=placeholder>&#128196;</div>';}" /></div>
  <div class="pub-info">
    <div class="pub-title"><a href="#">Efficiently enhancing co-occurring details while avoiding artifacts for light field display</a></div>
    <div class="pub-authors">J Wei, S Wang, Y Zhao, M Piao, <b>C Song</b></div>
    <div class="pub-venue">Applied Optics 59 (21), 6315-6326, 2020</div>
    <div class="pub-links">
      <a href="https://opg.optica.org/ao/abstract.cfm?uri=ao-59-21-6315">PDF</a>
    </div>
  </div>
</div>

</div>