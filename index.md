---
date: 2015-11-11T17:18:58+03:00
author: Samet Demir
layout: page
---

<style>
.profile-container {
  display:flex; flex-wrap:wrap; align-items:flex-start; justify-content:center;
  gap:2rem; margin:2rem auto;
}
.profile-image-section { flex-shrink:0; text-align:center; }
.profile-content { flex:1; min-width:300px; text-align:justify; }
@media (max-width:768px){ .profile-container{flex-direction:column; align-items:center;} .profile-content{text-align:center;} }
.section-title, h4.section-title { margin-top:1.5rem; font-weight:700; }
.small { font-size:.95rem; }
ul.compact{ margin:.5rem 0 0 1.2rem; } ul.compact li{ margin:.2rem 0; }
.badge{ display:inline-block; padding:.15rem .5rem; border-radius:999px; font-size:.8rem; background:#f2f2f2; margin-right:.4rem; }
.link-row a{ margin-right:.8rem; }

/* --- CV button --- */
.cv-button {
  display:inline-block;
  padding:0.55rem 1.25rem;
  border-radius:999px;
  border:1px solid #0f6ad8;
  background:linear-gradient(135deg,#0f6ad8,#4d9dff);
  color:#fff !important;
  font-size:0.9rem;
  font-weight:600;
  text-decoration:none;
  box-shadow:0 0 0 2px rgba(15,106,216,0.15);
  transition:transform 0.12s ease, box-shadow 0.12s ease, background 0.12s ease;
}
.cv-button:hover,
.cv-button:focus-visible {
  background:linear-gradient(135deg,#0d5ec0,#327fe3);
  box-shadow:0 0 0 3px rgba(15,106,216,0.28);
  transform:translateY(-1px);
}
.cv-button:active {
  transform:translateY(0);
  box-shadow:0 0 0 1px rgba(15,106,216,0.2);
}

.link-row{
  margin:1rem 0 .5rem;
  text-align:center;
}
.link-row a{
  margin-right:.8rem;
}

.market-note-wrapper{
  text-align:center;
  margin-top:0.6rem;
}

.market-note{
  display:inline-block;
  margin:0;
  padding:0.3rem 0.9rem;
  background:#f7f7f7;
  border:1px solid #e0e0e0;
  border-radius:8px;
  font-size:0.85rem;
  color:#555;
}


</style>

<div class="profile-container">
  <div class="profile-image-section">
    <img src="/uploads/photo.jpg" alt="Photo of Samet Demir" width="197" height="236" />
    <p><em><strong>E-mail: </strong><a href="mailto:samet.demir@austin.utexas.edu">samet.demir@austin.utexas.edu</a></em></p>
    <p><em><strong>Address: </strong><a href="https://www.google.com/maps/search/?api=1&query=201+E+24th+St+Austin+TX+78712">POB 6.244, Oden Institute, UT Austin <br/><span style="float:right;">Austin, TX / USA</span></a></em></p>
  </div>

  <div class="profile-content">
    <p>
      I’m a <a href="https://oden.utexas.edu/">Peter O’Donnell, Jr. Postdoctoral Fellow</a> at the <a href="https://oden.utexas.edu/">Oden Institute for Computational Engineering &amp; Sciences</a>, <a href="https://www.utexas.edu/">The University of Texas at Austin</a>, working with <a href="https://blakebordelon.github.io/">Prof. Blake Bordelon</a>. I received my Ph.D. in <a href="https://cs.ku.edu.tr/">Computer Science &amp; Engineering</a> from <a href="https://www.ku.edu.tr/en/">Koc University</a> in 2026, advised by <a href="https://mysite.ku.edu.tr/zdogan/">Prof. Zafer Dogan</a>, where I was an AI Fellow at the <a href="https://ai.ku.edu.tr/">KUIS AI Research Center</a> and a senior member of the Machine Learning &amp; Information Processing (MLIP) group. Previously, I received B.S. in Computer Engineering from Boğaziçi University.
    </p>
    <p>
      <em>My research develops a high-dimensional learning theory for how the statistics of learned representations arise from the interplay of architecture, data, and optimization—and how these statistics govern behaviors like generalization, in-context learning, and robustness in modern deep learning.</em>
    </p>

    <h4 class="section-title">Research interests</h4>
    <p class="small">
      <span class="badge">Learning theory</span>
      <span class="badge">High-dimensional statistics</span>
      <span class="badge">Deep learning</span>
      <span class="badge">In-context learning</span>
      <span class="badge">Gaussian universality</span>
      <span class="badge">Random matrix theory</span>
      <span class="badge">Robust learning</span>
    </p>

    <div class="link-row" style="margin:1rem 0 0.5rem;">
      <a class="cv-button" href="https://sametdemir.xyz/cv">
        View full CV
      </a>
    </div>

    <div class="market-note-wrapper">
      <p class="small market-note">
        Open to research positions starting <strong>Fall 2027</strong>
      </p>
    </div>


    <h4 class="section-title">Selected publications</h4>
    <ul class="compact small">
      <li><strong>Demir</strong> &amp; Dogan. <a href="https://arxiv.org/abs/2511.01292"><em>Optimal Attention Temperature Improves the Robustness of In-Context Learning under Distribution Shift in High Dimensions.</em></a> <strong>ICML 2026</strong>.</li>
      <li><strong>Demir</strong> &amp; Dogan. <a href="https://openreview.net/forum?id=615vk8hmeH"><em>How Data Mixing Shapes In-Context Learning: Asymptotic Equivalence for Transformers with MLPs.</em></a> <strong>NeurIPS 2025</strong>.</li>
      <li><strong>Demir</strong> &amp; Dogan. <a href="https://openreview.net/forum?id=tNn6Hskmti"><em>Asymptotic Analysis of Two-Layer Neural Networks after One Gradient Step under Gaussian Mixtures with Structure.</em></a> <strong>ICLR 2025</strong>.</li>
      <li><strong>Demir</strong> &amp; Dogan. <a href="https://arxiv.org/abs/2409.20250"><em>Input-Label Correlation Governs a Linear-to-Nonlinear Transition in Random Features under Spiked Covariance.</em></a> <strong>SIAM Journal on Mathematics of Data Science</strong>, 2026.</li>
      <li><strong>Demir</strong> &amp; Dogan. <a href="https://arxiv.org/abs/2512.01231"><em>Implicitly Normalized Online PCA: A Regularized Algorithm with Exact High-Dimensional Dynamics.</em></a> arXiv preprint, arXiv:2512.01231, 2025.</li>
      <li>More on <a href="https://scholar.google.com/citations?user=VKyOvOYAAAAJ">Google Scholar</a>.</li>
    </ul>

    <h4 class="section-title">Awards &amp; fellowships</h4>
    <ul class="compact small">
      <li><b>Peter O’Donnell, Jr. Postdoctoral Fellowship</b>, Oden Institute, UT Austin (2026–27).</li>
      <li><b>AI Fellowship</b>, KUIS AI Research Center, Koc University.</li>
    </ul>

    <h4 class="section-title">Academic service</h4>
    <ul class="compact small">
      <li><b>Reviewer</b>: ICML 2026, ICLR 2025–26, NeurIPS 2025-26, AAAI 2026, ACML 2024–25.</li>
    </ul>

    <h4 class="section-title">Teaching</h4>
    <ul class="compact small">
      <li><b>Head TA</b>: Introduction to Modern Learning Theory (2025–26); Programming for Engineers (2024–26).</li>
      <li><b>TA</b>: Algorithms &amp; Complexity (2023–24), Software Engineering (2023), Programming with Python (2022), Computer Systems &amp; Programming (2020–22), Introduction to Computing (2017).</li>
    </ul>
  </div>
</div>