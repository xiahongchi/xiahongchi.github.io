---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!-- css -->
<link rel="stylesheet" type="text/css" href="/assets/css/paper.css">

<!-- self intro -->
### Bios
<p>My name is Hongchi Xia (夏鸿驰). I'm now a second-year Ph.D. student in Computer Science at the University of Illinois Urbana-Champaign (UIUC), where I collaborate with <a href="https://shenlong.web.illinois.edu/">Shenlong Wang</a> and <a href="https://www.cs.cornell.edu/~weichiu/">Wei-Chiu Ma</a>.</p>
<p>My research lies in 3D computer vision, building essential foundations for spatial intelligence. Previously, I conducted a series of works related to 3D reconstruction and photorealistic re-simulation with grounded physics. Recently, I've gone into 3D generation, aiming at addressing the urgent need for rich and diverse 3D data.</p>
<p>Check my Curriculum Vitae <a href="./files/CV.pdf">here</a>.</p>


### News
* <span class="news-date">Feb 2026</span> Our new agentic scene generation project "SAGE" is accepted to CVPR 2026! See you in Denver!
* <span class="news-date">Oct 2025</span> "HoloScene" is accepted to NeurIPS 2025! See you in San Diego!
* <span class="news-date">May 2025</span> Had my first summer internship at NVIDIA.
* <span class="news-date">Apr 2025</span> "DRAWER" is accepted to CVPR 2025! See you in Nashville!
* <span class="news-date">Aug 2024</span> Started the PhD journey at UIUC!
* <span class="news-date">Feb 2024</span> Two papers "Video2Game" and "WildRGB-D" are accepted to CVPR 2024!

<style>
/* section headers */
h3 {
  margin-top: 32px;
  margin-bottom: 14px;
  padding-bottom: 6px;
  border-bottom: 2px solid #eee;
}

/* news date badges */
.news-date {
  display: inline-block;
  min-width: 74px;
  background: #f0f4f8;
  color: #52adc8;
  font-size: 12px;
  font-weight: 700;
  padding: 2px 8px;
  border-radius: 10px;
  margin-right: 6px;
  vertical-align: middle;
}

/* cv entries */
.cv-entry {
  display: flex;
  align-items: flex-start;
  margin-bottom: 20px;
  gap: 0;
}
.cv-entry-date {
  min-width: 160px;
  color: #888;
  font-size: 13px;
  padding-top: 3px;
  flex-shrink: 0;
}
.cv-entry-info { flex: 1; }
.cv-entry-title { font-weight: bold; font-size: 15px; margin-bottom: 3px; }
.cv-entry-role { color: #444; font-size: 14px; margin-bottom: 3px; }
.cv-entry-advisor { color: #666; font-size: 13px; }
</style>

### Experience

<div class="cv-entry">
  <div class="cv-entry-date">May 2026 - Present</div>
  <div class="cv-entry-info">
    <div class="cv-entry-title"><a href="https://research.nvidia.com/labs/cosmos-lab/">NVIDIA Cosmos Lab</a></div>
    <div class="cv-entry-role">Research Intern</div>
    <div class="cv-entry-advisor">Manager: <a href="https://mingyuliu.net/">Ming-Yu Liu</a></div>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-entry-date">May 2025 - Feb 2026</div>
  <div class="cv-entry-info">
    <div class="cv-entry-title"><a href="https://research.nvidia.com/labs/dir/">NVIDIA Deep Imagination Research</a></div>
    <div class="cv-entry-role">Research Intern</div>
    <div class="cv-entry-advisor">Mentor: <a href="https://weify627.github.io/">Fangyin Wei</a>; Manager: <a href="https://mingyuliu.net/">Ming-Yu Liu</a></div>
  </div>
</div>

### Education

<div class="cv-entry">
  <div class="cv-entry-date">Aug 2024 – Present</div>
  <div class="cv-entry-info">
    <div class="cv-entry-title"><a href="https://illinois.edu/">University of Illinois Urbana-Champaign</a></div>
    <div class="cv-entry-role">Ph.D. in Computer Science</div>
    <div class="cv-entry-advisor">Advised by <a href="https://shenlong.web.illinois.edu/">Shenlong Wang</a> and <a href="https://www.cs.cornell.edu/~weichiu/">Wei-Chiu Ma</a></div>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-entry-date">Sep 2020 – May 2024</div>
  <div class="cv-entry-info">
    <div class="cv-entry-title"><a href="https://en.sjtu.edu.cn/">Shanghai Jiao Tong University</a></div>
    <div class="cv-entry-role">B.S. in Computer Science</div>
  </div>
</div>

### Selected Publications [<a href="https://scholar.google.com/citations?user=9iXQ-wsAAAAJ&hl=en">ALL</a>]

<!-- paper start -->
<div class="paper">

<div class="pimg"> 
<img src="/images/sage.gif" width="200" height="140">
</div>

<div class="ptitle">SAGE: Scalable Agentic 3D Scene Generation for Embodied AI</div>

<div class="pauthors"> <b><a href="https://xiahongchi.github.io/">Hongchi Xia</a></b>, <a href="https://xuan-li.github.io/">Xuan Li</a>, <a href="https://mli0603.github.io/">Zhaoshuo Li</a>, <a href="https://qianlim.github.io/">Qianli Ma</a>, <a href="https://cnut1648.github.io/">Jiashu Xu</a>, <a href="https://mingyuliu.net/">Ming-Yu Liu</a>, <a href="https://ycui.me/">Yin Cui</a>, <a href="https://tsungyilin.info/">Tsung-Yi Lin</a>, <a href="https://www.cs.cornell.edu/~weichiu/">Wei-Chiu Ma</a>, <a href="https://shenlong.web.illinois.edu/">Shenlong Wang</a>, <a href="https://shurans.github.io/">Shuran Song</a>, <a href="https://weify627.github.io/">Fangyin Wei</a></div>

<div class="pvenue">
<p>IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2026</p>
<p>[<a href="https://nvlabs.github.io/sage/">project</a>] [<a href="https://arxiv.org/pdf/2602.10116">paper</a>] [<a href="https://github.com/NVlabs/sage">code</a>] [<a href="https://huggingface.co/datasets/nvidia/SAGE-10k">dataset</a>]</p>
</div>

</div>
<!-- paper end -->


<!-- paper start -->
<div class="paper">

<div class="pimg"> 
<img src="/images/holoscene.gif" width="200" height="140">
</div>

<div class="ptitle">HoloScene: Simulation-Ready Interactive 3D Worlds from a Single Video</div>

<div class="pauthors"> <b><a href="https://xiahongchi.github.io/">Hongchi Xia</a></b>, <a href="https://chih-hao-lin.github.io/">Chih-Hao Lin</a>, <a href="https://haoyuhsu.github.io/">Hao-Yu Hsu</a>, <a href="https://www.linkedin.com/in/quentinleboutet/?originalSubdomain=de">Quentin Leboutet</a>, <a href="https://sites.google.com/view/katelyn-gao/home">Katelyn Gao</a>, <a href="https://www.linkedin.com/in/michael-paulitsch/?originalSubdomain=de">Michael Paulitsch</a>, <a href="https://scholar.google.com/citations?user=QGlp5ywAAAAJ&hl=en">Benjamin Ummenhofer</a>, <a href="https://shenlong.web.illinois.edu/">Shenlong Wang</a></div>

<div class="pvenue">
<p>Neural Information Processing Systems (NeurIPS), 2025</p>
<p>[<a href="https://xiahongchi.github.io/HoloScene/">project</a>] [<a href="https://arxiv.org/pdf/2510.05560">paper</a>] [<a href="https://github.com/xiahongchi/HoloScene">code</a>]</p>
</div>

</div>
<!-- paper end -->

<!-- paper start -->
<div class="paper">

<div class="pimg"> 
<img src="/images/drawer.gif" width="200" height="140">
</div>

<div class="ptitle">DRAWER: Digital Reconstruction and Articulation With Environment Realism</div>

<div class="pauthors"> <b><a href="https://xiahongchi.github.io/">Hongchi Xia</a></b>, <a href="https://entongsu.github.io/">Entong Su</a>, <a href="https://memmelma.github.io/">Marius Memmel</a>, <a href="https://arhanjain.github.io/">Arhan Jain</a>, <a href="https://raymondyu5.github.io/">Raymond Yu</a>, <a href="https://www.linkedin.com/in/numfor-mbiziwo-tiapo/">Numfor Mbiziwo-Tiapo</a>, <a href="https://homes.cs.washington.edu/~ali/">Ali Farhadi</a>, <a href="https://homes.cs.washington.edu/~abhgupta/">Abhishek Gupta</a>, <a href="https://shenlong.web.illinois.edu/">Shenlong Wang</a>, <a href="https://www.cs.cornell.edu/~weichiu/">Wei-Chiu Ma</a></div>

<div class="pvenue">
<p>IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2025</p>
<p>[<a href="https://drawer-art.github.io/">project</a>] [<a href="https://arxiv.org/abs/2504.15278">paper</a>] [<a href="https://github.com/xiahongchi/DRAWER">code</a>]</p>
</div>

</div>
<!-- paper end -->


<!-- paper start -->
<div class="paper">

<div class="pimg"> 
<img src="/images/garden.png" width="200" height="140">
</div>

<div class="ptitle">Video2Game: Real-time, Interactive, Realistic and Browser-Compatible Environment from a Single Video</div>

<div class="pauthors"> <b><a href="https://xiahongchi.github.io/">Hongchi Xia</a></b>, <a href="https://zhihao-lin.github.io/">Zhi-Hao Lin</a>, <a href="https://www.cs.cornell.edu/~weichiu/">Wei-Chiu Ma</a>, <a href="https://shenlong.web.illinois.edu/">Shenlong Wang</a></div>

<div class="pvenue">
<p>IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024</p>
<p>[<a href="https://video2game.github.io/">project</a>] [<a href="https://arxiv.org/abs/2404.09833">paper</a>] [<a href="https://github.com/video2game/video2game">code</a>]</p>
</div>

</div>
<!-- paper end -->


<!-- paper start -->
<div class="paper">

<div class="pimg"> 
<img class="media-object img-rounded img-responsive" src="/images/pineapple.avifs" width="200" height="140">
</div>

<div class="ptitle">RGBD Objects in the Wild: Scaling Real-World 3D Object Learning from RGB-D Videos</div>

<div class="pauthors"> <b><a href="https://xiahongchi.github.io/">Hongchi Xia</a></b>*, <a href="https://scholar.google.com/citations?user=bioUtz4AAAAJ&hl=en">Yang Fu</a>*, <a href="https://scholar.google.com/citations?user=j4pcHV4AAAAJ&hl=en">Sifei Liu</a>, <a href="https://scholar.google.com/citations?user=Y8O9N_0AAAAJ&hl=en">Xiaolong Wang</a> </div>

<div class="pvenue">
<p>IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024</p>
<p>[<a href="https://wildrgbd.github.io/">project</a>] [<a href="https://arxiv.org/abs/2401.12592">paper</a>] [<a href="https://github.com/wildrgbd/wildrgbd">code</a>]</p>
</div>

</div>
<!-- paper end -->

### OSS Contributions

[![Star History Chart](https://api.star-history.com/svg?repos=wildrgbd%2Fwildrgbd%2Cvideo2game%2Fvideo2game%2Cxiahongchi%2Fdrawer%2Cxiahongchi%2Fholoscene%2Cnvlabs%2Fsage&type=date&legend=top-left)](https://www.star-history.com/?repos=wildrgbd%2Fwildrgbd%2Cvideo2game%2Fvideo2game%2Cxiahongchi%2Fdrawer%2Cxiahongchi%2Fholoscene%2Cnvlabs%2Fsage&type=date&legend=top-left)