---
layout: default
title: Zhangrui Yang (杨章睿) | Tongji University
---

<style>
  #academic-profile {
    --primary: #2c3e50;
    --accent: #007bff;
    --border: #e9ecef;
    --muted: #666;
    color: var(--primary);
    line-height: 1.65;
    padding-top: 20px;
    overflow-wrap: break-word;
  }
  #academic-profile .profile-container { display: flow-root; border-bottom: 1px solid var(--border); padding-bottom: 20px; margin-bottom: 30px; }
  #academic-profile .profile-pic { float: right; width: 150px; max-width: 100%; height: auto; border-radius: 8px; margin: 0 0 10px 20px; box-shadow: 0 4px 8px rgba(0,0,0,.1); }
  #academic-profile .profile-name { margin-top: 0; }
  #academic-profile h2 { border-bottom: 2px solid var(--border); padding-bottom: 5px; margin-top: 36px !important; color: var(--primary); clear: both; }
  #academic-profile .pub-card { border-left: 4px solid var(--border); padding: 10px 15px; margin-bottom: 12px; background: #fcfcfc; }
  #academic-profile .exp-card { border: 1px solid var(--border); border-radius: 8px; padding: 15px; margin-bottom: 15px; background: #fff; }
  #academic-profile .card-heading { display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 4px 12px; }
  #academic-profile .card-heading strong, #academic-profile .pub-title { font-size: 1.08em; }
  #academic-profile .pub-title { display: block; }
  #academic-profile .meta { color: var(--muted); font-size: .9em; }
  #academic-profile .card-body { margin: 8px 0 0; color: #555; font-size: .95em; }
  #academic-profile .card-body ul { margin: 6px 0 0; padding-left: 1.25em; }
  #academic-profile .badge-row { margin-top: 10px; display: flex; gap: 8px; flex-wrap: wrap; }
  #academic-profile .pill { padding: 2px 10px; font-size: .8em; border-radius: 4px; text-decoration: none !important; display: inline-block; }
  #academic-profile .pill-red { background: #b31b1b; color: #fff !important; }
  #academic-profile .pill-gray { background: #24292e; color: #fff !important; }
  #academic-profile .pill-yellow { background: #fff3cd; color: #856404; border: 1px solid #ffeeba; }
  #academic-profile .pill-skill { background: #f0f2f5; color: #495057; border: 1px solid #d1d9e6; margin: 2px 4px 2px 0; }
  #academic-profile .honors { padding-left: 1.25em; }
  #academic-profile .honors li { margin-bottom: 8px; }
  #academic-profile .course-list { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 6px 12px; list-style: none; padding: 0; margin-bottom: 0; }
  #academic-profile .course-list li::before { content: '• '; color: var(--accent); }
  #academic-profile .education-card { background: #f8f9fa; padding: 15px; border-radius: 8px; margin-bottom: 12px; }
  @media (max-width: 600px) {
    #academic-profile .profile-pic { float: none; display: block; margin: 0 auto 20px; }
    #academic-profile .card-heading { display: block; }
    #academic-profile .card-heading .meta, #academic-profile .card-heading .pill { display: inline-block; margin-top: 4px; }
  }
</style>

<div id="academic-profile">
  <div class="profile-container">
    <img src="{{ '/assets/images/profile.jpg' | relative_url }}" class="profile-pic" alt="Portrait of Zhangrui Yang">
    <h1 class="profile-name">Zhangrui Yang (杨章睿)</h1>
    <p>
      Undergraduate Researcher &amp; Incoming Ph.D. Student (2027)<br>
      Computer Science and Technology (Elite Program)<br>
      <a href="https://ghc.tongji.edu.cn/">Guohao College</a>, Tongji University
    </p>
    <p>
      <a href="mailto:jerry.zryang@hotmail.com">Email</a> &nbsp;|&nbsp;
      <a href="https://github.com/Yarathustra">GitHub</a> &nbsp;|&nbsp;
      <a href="https://scholar.google.com/citations?user=1io0foEAAAAJ">Google Scholar</a>
    </p>
  </div>

  <section>
    <h2>About</h2>
    <p>
      I am an undergraduate researcher in the Computer Science and Technology Elite Program at Guohao College, Tongji University. I have received a provisional offer to pursue a Ph.D. in Computer Science and Technology at Tongji University, starting in 2027.
    </p>
    <p>
      My research interests center on <strong>spatial intelligence, 3D generative modeling, and computer vision</strong>. I am particularly interested in autoregressive 3D scene generation, long-range spatial consistency, and the generation of scalable and coherent 3D environments. My previous research also includes adversarial robustness and semantic segmentation.
    </p>
  </section>

  <section>
    <h2>Publications</h2>
    <div class="pub-card">
      <strong class="pub-title">Pseudo-Label Refinement for Robust Wheat Head Segmentation via Two-Stage Hybrid Training</strong>
      <span style="color:#555;">Jiahao Jiang*, <strong>Zhangrui Yang*</strong>, Xuanhan Wang, Jingkuan Song</span><br>
      <em>CVPPA Workshop, ICCV 2025 (Extended Abstract)</em>
      <div class="badge-row">
        <a href="https://arxiv.org/abs/2512.11874" class="pill pill-red">arXiv</a>
      </div>
    </div>
    <small>* Equal contribution</small>
  </section>

  <section>
    <h2>Research Experience</h2>
    <div class="exp-card">
      <div class="card-heading">
        <strong>BF-Attack</strong>
        <span class="meta">Sep 2025 – Apr 2026</span>
      </div>
      <div class="card-body">
        <strong>Project Lead &amp; Open-Source Maintainer</strong>
        <p style="margin:6px 0 0;">An open-source research project on transferable adversarial attacks. Responsible for algorithm development, implementation, and repository maintenance.</p>
      </div>
      <div class="badge-row">
        <a href="https://github.com/Yarathustra/BF-Attack" class="pill pill-gray">GitHub / Code</a>
      </div>
    </div>
    <div class="exp-card">
      <div class="card-heading">
        <strong>Global Wheat Full Semantic Segmentation (GWFSS)</strong>
        <span class="pill pill-yellow">Global Rank #2</span>
      </div>
      <div class="meta">Mar 2025 – Jun 2025</div>
      <div class="card-body">
        <strong>Co-Team Leader &amp; Core Researcher</strong>
        <ul>
          <li>Developed a two-stage pseudo-label refinement framework with iterative teacher-student training for wheat head segmentation.</li>
          <li>Led data augmentation, ablation studies, and hyperparameter optimization.</li>
          <li>Placed second among 26 teams worldwide; the work subsequently led to a co-first-authored extended abstract at the CVPPA Workshop, ICCV 2025.</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <h2>Engineering &amp; Project Experience</h2>
<div class="exp-card">
  <div class="card-heading">
    <strong>SurgeryMind — Intelligent Surgical Assistance System</strong>
    <span class="meta">Sep 2025 – Aug 2026</span>
  </div>

  <div class="card-body">
    <strong>Technical Lead</strong>
    <ul>
      <li>Led full-stack system architecture and integrated web-based parameter visualization with multimodal user inputs.</li>
      <li>Designed and refined the human-computer interaction interface for surgical assistance workflows.</li>
      <li>Led technical development of the project, which received three innovation and entrepreneurship competition awards.</li>
    </ul>

    <div style="border-top: 1px solid var(--border); margin-top: 12px; padding-top: 12px;">
      <strong>Project Awards</strong>
      <ul style="list-style: none; padding-left: 0; margin-top: 8px;">
        <li style="margin-bottom: 8px;">
          🏆 <strong>National First Prize</strong><br>
          iCAN AI Challenge
        </li>
        <li style="margin-bottom: 8px;">
          🥈 <strong>University-Level Silver Award</strong><br>
          China International College Students' Innovation Competition
        </li>
        <li>
          🥈 <strong>University-Level Second Prize</strong><br>
          Challenge Cup College Students' Entrepreneurship Competition
        </li>
      </ul>
    </div>
  </div>
</div>
    <div class="exp-card">
      <div class="card-heading">
        <strong>China Undergraduate Mathematical Contest in Modeling (CUMCM)</strong>
        <span class="meta">Sep 2025</span>
      </div>
      <div class="card-body">
        <strong>Team Leader</strong>
        <p style="margin:6px 0 0;">Developed statistical and machine learning models for non-invasive prenatal testing, combining mixed-effects models, survival analysis, decision trees, and ensemble learning. Awarded Shanghai Second Prize.</p>
      </div>
    </div>
    <div class="exp-card">
      <div class="card-heading">
        <strong>Collaborative Robot Project</strong>
        <span class="meta">Apr 2025 – May 2025</span>
      </div>
      <div class="card-body">
        <strong>Intern · Shanghai</strong>
        <p style="margin:6px 0 0;">Contributed to embodied AI data collection through master-slave robotic arm teleoperation, video annotation, and cluster-based training workflows.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Selected Honors &amp; Awards</h2>
    <ul class="honors">
      <li><strong>First-Class Undergraduate Scholarship for Outstanding Students</strong> — Tongji University, 2025–2026</li>
      <li><strong>National First Prize</strong> — iCAN AI Challenge, 2026</li>
      <li><strong>Global Second Place</strong> — Global Wheat Full Semantic Segmentation Competition, 2025</li>
      <li><strong>Shanghai Second Prize</strong> — China Undergraduate Mathematical Contest in Modeling, 2025</li>
      <li><strong>University-Level Silver Award</strong> — China International College Students' Innovation Competition</li>
      <li><strong>University-Level Second Prize</strong> — Challenge Cup College Students' Entrepreneurship Competition</li>
      <li><strong>Academic Scholarship</strong> — Guohao College, Tongji University, 2023–2024</li>
    </ul>
  </section>

  <section>
    <h2>Education</h2>
    <div class="education-card">
      <div class="card-heading">
        <strong>Tongji University</strong>
        <span class="meta">Expected entry: 2027</span>
      </div>
      <div>Ph.D. in Computer Science and Technology</div>
      <small class="meta">Incoming Ph.D. Student · Provisional Admission</small>
    </div>
    <div class="education-card">
      <div class="card-heading">
        <strong>Tongji University</strong>
        <span class="meta">Sep 2023 – Jun 2027 (expected)</span>
      </div>
      <div>B.S. in Computer Science and Technology (Elite Program)</div>
      <div class="meta">Guohao College</div>
      <p style="margin-top:10px; font-weight:600; font-size:.9em; border-top:1px solid #ddd; padding-top:10px;">Selected Coursework</p>
      <ul class="course-list">
        <li>Mathematical Analysis</li>
        <li>Advanced Algebra</li>
        <li>Probability &amp; Statistics</li>
        <li>Data Structures &amp; Algorithms</li>
        <li>Database Systems</li>
        <li>Pattern Recognition</li>
      </ul>
    </div>
  </section>

  <section>
    <h2>Technical Skills</h2>
    <p>
      <strong>Programming:</strong> <span class="pill pill-skill">Python</span> <span class="pill pill-skill">C++</span> <span class="pill pill-skill">Verilog HDL</span> <span class="pill pill-skill">SQL</span><br>
      <strong>Frameworks:</strong> <span class="pill pill-skill">PyTorch</span><br>
      <strong>Tools:</strong> <span class="pill pill-skill">Linux</span> <span class="pill pill-skill">Git</span> <span class="pill pill-skill">LaTeX</span>
    </p>
  </section>
</div>
