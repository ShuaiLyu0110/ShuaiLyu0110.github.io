---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hello everyone, my name is <strong>Shuai Lyu (吕帅)</strong>. I am a Ph.D. student at the School of Computer Science, <a href="https://www.bupt.edu.cn/" target="_blank" rel="noopener noreferrer">Beijing University of Posts and Telecommunications (BUPT)</a>, supervised by Prof. Zhonghong Ou.

My research interests include <strong>multimodal large language models, reinforcement learning post-training, visual token efficiency, and cross-modal retrieval</strong>. I work on improving the reliability and efficiency of vision-language systems through branch-level policy optimization, answer-aware visual evidence selection, and robust image-text representation learning.

My first-author research includes <strong>ACM Multimedia 2026 (Oral)</strong> and <strong>AAAI 2025</strong>. My paper <strong>SQL-o1</strong> has also been accepted for publication in <em>ACM Transactions on Software Engineering and Methodology (TOSEM)</em>.

<span style="color: green;">If you have any questions about my work or are interested in collaboration, please feel free to contact me.</span>

<h1 id="-news" class="section-heading"><span class="section-heading__emoji">🔥</span><span class="section-heading__text">News</span></h1>

<div class="news-timeline">
  <div class="news-item news-item--featured">
    <div class="news-date">2026.10</div>
    <div class="news-content">🎉 Our paper <strong>SQL-o1</strong> has been accepted for publication in <em>ACM Transactions on Software Engineering and Methodology (TOSEM)</em>.</div>
  </div>
  <div class="news-item news-item--featured">
    <div class="news-date">2026.08</div>
    <div class="news-content">🎉 Our paper <strong>MBPO</strong> was accepted to ACM Multimedia 2026 as an <strong>Oral</strong> paper.</div>
  </div>
  <div class="news-item">
    <div class="news-date">2026.07</div>
    <div class="news-content">🎉 Our collaborative work <strong>HEDP</strong> appeared in the proceedings of ICML 2026.</div>
  </div>
  <div class="news-item">
    <div class="news-date">2026.03</div>
    <div class="news-content">🎉 Our collaborative work <strong>CreBench</strong> was accepted to AAAI 2026.</div>
  </div>
  <div class="news-item">
    <div class="news-date">2025.09</div>
    <div class="news-content">🎉 Our collaborative work <strong>Multi-SEA</strong> was published in <em>Information Processing &amp; Management</em>.</div>
  </div>
  <div class="news-item">
    <div class="news-date">2025.04</div>
    <div class="news-content">🎉 Our papers <strong>TSVC</strong> and <strong>LS-TGNN</strong> appeared at AAAI 2025.</div>
  </div>
</div>

<h1 id="-publications" class="section-heading"><span class="section-heading__emoji">📝</span><span class="section-heading__text">Publications</span><span class="section-heading__note">* Equal contribution</span></h1>

<div class="paper-list">
  <article class="paper-item">
    <div class="paper-header">
      <div class="paper-title">SQL-o1: Automatic Text-to-SQL Program Synthesis via Self-Reward Heuristic Search</div>
      <span class="paper-badge">TOSEM · Accepted</span>
    </div>
    <div class="paper-authors"><strong>Shuai Lyu*</strong>, <strong>Haoran Luo*</strong>, Ripeng Li, Zhonghong Ou, Yifan Zhu, Tiesunlong Shen</div>
    <div class="paper-meta"><em>ACM Transactions on Software Engineering and Methodology (TOSEM)</em> · Accepted for publication</div>
    <p>Combines self-reward heuristics with search-based program synthesis to guide structured exploration and improve execution-aware Text-to-SQL generation.</p>
    <div class="paper-links">
      <a href="https://arxiv.org/abs/2502.11741" target="_blank" rel="noopener noreferrer">Paper (arXiv)</a>
      <a href="https://github.com/ShuaiLyu0110/SQL-o1" target="_blank" rel="noopener noreferrer">Code</a>
    </div>
  </article>

  <article class="paper-item">
    <div class="paper-header">
      <div class="paper-title">Multi-Branch Policy Optimization for Multimodal Reasoning via Sibling-Relative Advantage Estimation</div>
      <span class="paper-badge">ACM MM 2026 · Oral</span>
    </div>
    <div class="paper-authors"><strong>Shuai Lyu*</strong>, <strong>Yuning Gong*</strong>, Ruiling Gao, Xiaoran Shang, Zhonghong Ou, Ping Zong, Yifan Zhu, Yuan Sun, Yang Qin, Peng Hu</div>
    <div class="paper-meta"><em>ACM International Conference on Multimedia (ACM MM 2026)</em> · Oral</div>
    <p>Introduces sibling-relative advantage estimation for branch-level credit assignment, improving exploration and self-correction in multimodal reasoning.</p>
    <div class="paper-links">
      <a href="https://arxiv.org/abs/2608.07581" target="_blank" rel="noopener noreferrer">Paper (arXiv)</a>
      <a href="https://github.com/ShuaiLyu0110/MBPO" target="_blank" rel="noopener noreferrer">Code</a>
    </div>
  </article>

  <article class="paper-item">
    <div class="paper-header">
      <div class="paper-title">TSVC: Tripartite Learning with Semantic Variation Consistency for Robust Image-Text Retrieval</div>
      <span class="paper-badge">AAAI 2025</span>
    </div>
    <div class="paper-authors"><strong>Shuai Lyu</strong>, Zijing Tian, Zhonghong Ou, Yifan Zhu, Xiao Zhang, Qiankun Ha, Haoran Luo, Meina Song</div>
    <div class="paper-meta"><em>Proceedings of the AAAI Conference on Artificial Intelligence</em>, 39(18): 19269–19277, 2025</div>
    <p>Proposes tripartite cooperative learning and semantic-variation consistency to improve image-text retrieval under noisy image-text correspondences.</p>
    <div class="paper-links">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/34121" target="_blank" rel="noopener noreferrer">Paper</a>
      <a href="https://arxiv.org/abs/2501.10935" target="_blank" rel="noopener noreferrer">arXiv</a>
    </div>
  </article>

  <article class="paper-item">
    <div class="paper-header">
      <div class="paper-title">HEDP: A Hybrid Energy-Distance Prompt-based Framework for Domain Incremental Learning</div>
      <span class="paper-badge">ICML 2026</span>
    </div>
    <div class="paper-authors">Yu Feng, Zhen Tian, Haoran Luo, Xie Yu, Diancheng Cheng, Haoyue Zheng, <strong>Shuai Lyu</strong>, Ping Zong, Lianyuan Li, Xin Ge, Yifan Zhu</div>
    <div class="paper-meta"><em>International Conference on Machine Learning (ICML 2026)</em></div>
    <p>Combines energy regularization with hybrid energy-distance cues to improve domain selection and generalization in domain-incremental learning.</p>
    <div class="paper-links">
      <a href="https://proceedings.mlr.press/v306/feng26r.html" target="_blank" rel="noopener noreferrer">Paper</a>
      <a href="https://github.com/dannis97500/HEDP" target="_blank" rel="noopener noreferrer">Code</a>
    </div>
  </article>

  <article class="paper-item">
    <div class="paper-header">
      <div class="paper-title">CreBench: Human-Aligned Creativity Evaluation from Idea to Process to Product</div>
      <span class="paper-badge">AAAI 2026</span>
    </div>
    <div class="paper-authors">Kaiwen Xue, Chenglong Li, Zhonghong Ou, Guoxin Zhang, Kaoyan Lu, <strong>Shuai Lyu</strong>, Yifan Zhu, Ping Zong, Junpeng Ding, Xinyu Liu, Qunlin Chen, Weiwei Qin, Yiran Shen, Jiayi Cen</div>
    <div class="paper-meta"><em>Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2026)</em></div>
    <p>Builds a creativity-evaluation benchmark and multimodal instruction dataset aligned with human judgments across creative ideas, processes, and products.</p>
    <div class="paper-links">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/39962" target="_blank" rel="noopener noreferrer">Paper</a>
      <a href="https://arxiv.org/abs/2511.13626" target="_blank" rel="noopener noreferrer">arXiv</a>
      <a href="https://kaixuewen.github.io/Crebench/" target="_blank" rel="noopener noreferrer">Project</a>
    </div>
  </article>

  <article class="paper-item">
    <div class="paper-header">
      <div class="paper-title">Satellite-Enabled Edge Intelligence for Climate-Resilient Emergency Mobility: A Survey of On-Orbit Edge Computing</div>
      <span class="paper-badge">IEEE TITS 2026</span>
    </div>
    <div class="paper-authors">Ping Zong, Zhonghong Ou, Yifan Zhu, Ran An, Qingnan Zhao, Guoxin Zhang, Kaiwen Xue, Zijing Tian, <strong>Shuai Lyu</strong>, et al.</div>
    <div class="paper-meta"><em>IEEE Transactions on Intelligent Transportation Systems</em> · 2026</div>
    <p>Reviews satellite-enabled edge intelligence and on-orbit edge computing, with an emphasis on architectures and methods for climate-resilient emergency mobility.</p>
    <div class="paper-links">
      <a href="https://ieeexplore.ieee.org/document/11466345" target="_blank" rel="noopener noreferrer">Paper</a>
    </div>
  </article>

  <article class="paper-item">
    <div class="paper-header">
      <div class="paper-title">LS-TGNN: Long and Short-Term Temporal Graph Neural Network for Session-Based Recommendation</div>
      <span class="paper-badge">AAAI 2025</span>
    </div>
    <div class="paper-authors">Zhonghong Ou, Xiao Zhang, Yifan Zhu, <strong>Shuai Lyu</strong>, Jiahao Liu, Tu Ao</div>
    <div class="paper-meta"><em>Proceedings of the AAAI Conference on Artificial Intelligence</em>, 39(12): 12426–12434, 2025</div>
    <p>Models long-term user preferences and short-term session intent through temporal graph learning for session-based recommendation.</p>
    <div class="paper-links">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/33354" target="_blank" rel="noopener noreferrer">Paper</a>
    </div>
  </article>

  <article class="paper-item">
    <div class="paper-header">
      <div class="paper-title">Multi-SEA: Multi-stage Semantic Enhancement and Aggregation for Image-Text Retrieval</div>
      <span class="paper-badge">IPM 2025</span>
    </div>
    <div class="paper-authors">Zijing Tian, Zhonghong Ou, Yifan Zhu, <strong>Shuai Lyu</strong>, Hanyu Zhang, Jinghua Xiao, Meina Song</div>
    <div class="paper-meta"><em>Information Processing &amp; Management</em>, 62(5): 104165, 2025</div>
    <p>Combines agent attention, gating, and hierarchical alignment through multi-stage semantic enhancement and aggregation for image-text retrieval.</p>
    <div class="paper-links">
      <a href="https://doi.org/10.1016/j.ipm.2025.104165" target="_blank" rel="noopener noreferrer">Paper</a>
    </div>
  </article>

  <article class="paper-item">
    <div class="paper-header">
      <div class="paper-title">Load Balancing for LLM Traffic via Flow Block</div>
      <span class="paper-badge">IEEE LCN 2025</span>
    </div>
    <div class="paper-authors">Xingyi Li, Yiran Zhang, <strong>Shuai Lyu</strong>, Shangguang Wang</div>
    <div class="paper-meta"><em>IEEE Conference on Local Computer Networks (LCN 2025)</em></div>
    <p>Studies flow-block-based load balancing strategies for networked large language model inference traffic.</p>
    <div class="paper-links">
      <a href="https://dblp.org/rec/conf/lcn/LiZLW25" target="_blank" rel="noopener noreferrer">Publication record</a>
    </div>
  </article>
</div>

<h1 id="-honors-and-awards" class="section-heading awards-list"><span class="section-heading__emoji">🎖</span><span class="section-heading__text">Honors and Awards</span></h1>

<div class="award-list">
  <div class="award-item"><span class="award-index">1</span><span class="award-title">BYD Enterprise-Donated Scholarship (one recipient per year)</span><span class="award-year">2026.10</span></div>
  <div class="award-item"><span class="award-index">2</span><span class="award-title">Academic Innovation Award, Engineering Research Center of Information Networks, Ministry of Education</span><span class="award-year">2025.12</span></div>
  <div class="award-item"><span class="award-index">3</span><span class="award-title">Outstanding Ph.D. Student, Beijing University of Posts and Telecommunications</span><span class="award-year">2025.12</span></div>
  <div class="award-item"><span class="award-index">4</span><span class="award-title">Ph.D. Academic Scholarship, Beijing University of Posts and Telecommunications (4 times)</span><span class="award-year">4×</span></div>
  <div class="award-item"><span class="award-index">5</span><span class="award-title">Undergraduate Special Scholarship (one recipient per year)</span><span class="award-year">2016.11</span></div>
  <div class="award-item"><span class="award-index">6</span><span class="award-title">University First- and Second-Class Scholarships (6 times)</span><span class="award-year">—</span></div>
  <div class="award-item"><span class="award-index">7</span><span class="award-title">Kaggle Home Credit Competition · Silver Medal (ranked 69 / 3,856 teams)</span><span class="award-year">2024</span></div>
  <div class="award-item"><span class="award-index">8</span><span class="award-title">Kaggle Optiver Competition · Bronze Medal (ranked 264 / 4,436 teams)</span><span class="award-year">2024</span></div>
  <div class="award-item"><span class="award-index">9</span><span class="award-title">Third Prize, Mathematics Competition</span><span class="award-year">2016</span></div>
</div>

<h1 id="-talks" class="section-heading"><span class="section-heading__emoji">💬</span><span class="section-heading__text">Talks</span></h1>

<div class="talk-list">
  <article class="talk-item">
    <div class="talk-date">2026</div>
    <div class="talk-body">
      <div class="talk-title">Multi-Branch Policy Optimization for Multimodal Reasoning via Sibling-Relative Advantage Estimation</div>
      <div class="talk-meta">ACM Multimedia 2026 · Oral Paper</div>
    </div>
    <a class="talk-link" href="https://arxiv.org/abs/2608.07581" target="_blank" rel="noopener noreferrer">Paper</a>
  </article>
</div>

<h1 id="-experiences" class="section-heading"><span class="section-heading__emoji">💻</span><span class="section-heading__text">Experiences</span></h1>

<div class="experience-list">
  <article class="experience-item">
    <div class="experience-side">
      <div class="experience-time">2023 - Present</div>
      <span class="experience-logo-wrap"><img class="experience-logo experience-logo--wide" src="https://vi.bupt.edu.cn/images/logo2.png" alt="Beijing University of Posts and Telecommunications logo"></span>
    </div>
    <div class="experience-body">
      <div class="experience-heading">
        <div>
          <div class="experience-title">Beijing University of Posts and Telecommunications</div>
          <div class="experience-location">Beijing, China</div>
        </div>
      </div>
      <div class="experience-detail"><span>Position</span><strong>Ph.D. Student, School of Computer Science</strong></div>
      <div class="experience-detail"><span>Advisor</span><strong>Prof. Zhonghong Ou</strong></div>
      <div class="experience-detail"><span>Research</span><strong>Multimodal reasoning, reinforcement learning post-training, visual token efficiency, and cross-modal retrieval</strong></div>
    </div>
  </article>
  <article class="experience-item">
    <div class="experience-side">
      <div class="experience-time">Ph.D. Research</div>
      <span class="experience-logo-wrap"><span style="font-size:1rem;font-weight:900;color:#224b8d;">NKR&amp;D</span></span>
    </div>
    <div class="experience-body">
      <div class="experience-heading">
        <div>
          <div class="experience-title">National Key R&amp;D Program of China</div>
          <div class="experience-location">China</div>
        </div>
      </div>
      <div class="experience-detail"><span>Role</span><strong>Core Project Member</strong></div>
      <div class="experience-detail"><span>Focus</span><strong>Multimodal intelligence and reasoning technologies</strong></div>
    </div>
  </article>
  <article class="experience-item">
    <div class="experience-side">
      <div class="experience-time">Ph.D. Research</div>
      <span class="experience-logo-wrap"><span style="font-size:1rem;font-weight:900;color:#224b8d;">SGCC</span></span>
    </div>
    <div class="experience-body">
      <div class="experience-heading">
        <div>
          <div class="experience-title">State Grid Hebei Collaboration</div>
          <div class="experience-location">Hebei, China</div>
        </div>
      </div>
      <div class="experience-detail"><span>Role</span><strong>Student Project Lead</strong></div>
      <div class="experience-detail"><span>Focus</span><strong>Applied AI research and cross-modal retrieval for power-system knowledge services</strong></div>
    </div>
  </article>
</div>

<h1 id="-academic-service" class="section-heading"><span class="section-heading__emoji">🤝</span><span class="section-heading__text">Academic Service</span></h1>

<ul>
  <li><strong>Reviewer:</strong> AAAI 2025/2027, ICML 2026, ACM Multimedia 2024/2026, and PRCV.</li>
  <li><strong>Program Committee Member:</strong> CCKS 2025.</li>
  <li><strong>Additional service:</strong> Phase-2 reviewer for AAAI 2027.</li>
  <li><strong>Social service:</strong> Publicity Committee Member, Ph.D. Student Party Branch, Data Science Center, BUPT.</li>
</ul>
