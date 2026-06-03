---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* Light mode (default) */
:root {
  --accent:       #4a90d9;
  --accent-bg:    rgba(74, 144, 217, 0.08);
  --label-color:  #999;
  --divider:      #e5e5e5;
  --title-color:  #222;
  --sub-color:    #666;
  --contact-bg:   #f7f9fc;
  --contact-border: #dde4ef;
  --contact-color:  #555;
}

/* Dark mode overrides */
@media (prefers-color-scheme: dark) {
  :root {
    --accent:         #7db8f0;
    --accent-bg:      rgba(125, 184, 240, 0.12);
    --label-color:    #888;
    --divider:        #333;
    --title-color:    #e8e8e8;
    --sub-color:      #aaa;
    --contact-bg:     #1e2530;
    --contact-border: #2e3a4a;
    --contact-color:  #bbb;
  }
}

.tags { display: flex; flex-wrap: wrap; gap: 8px; margin: 1rem 0 1.5rem; }
.tag {
  font-size: 0.78rem;
  font-weight: 500;
  padding: 4px 14px;
  border-radius: 20px;
  border: 1.5px solid var(--accent);
  color: var(--accent);
  background: var(--accent-bg);
  letter-spacing: 0.03em;
  display: inline-block;
}

.section-label {
  font-size: 0.7rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--label-color);
  margin: 2rem 0 0.75rem;
  border-bottom: 1px solid var(--divider);
  padding-bottom: 6px;
}

.timeline { margin: 0.5rem 0 1.5rem; }
.tl-item {
  display: flex;
  gap: 16px;
  margin-bottom: 1.25rem;
  align-items: flex-start;
}
.tl-period {
  font-size: 0.78rem;
  color: var(--label-color);
  min-width: 100px;
  padding-top: 2px;
  flex-shrink: 0;
  font-variant-numeric: tabular-nums;
}
.tl-title {
  font-size: 0.92rem;
  font-weight: 600;
  color: var(--title-color);
  margin: 0 0 2px;
}
.tl-sub {
  font-size: 0.82rem;
  color: var(--sub-color);
  margin: 0;
}
.tl-sub a { color: var(--accent); text-decoration: none; }
.tl-sub a:hover { text-decoration: underline; }

.contact-block {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  margin-top: 0.5rem;
  font-size: 0.88rem;
  color: var(--contact-color);
  background: var(--contact-bg);
  border: 1px solid var(--contact-border);
  border-radius: 8px;
  padding: 8px 16px;
}
</style>

I am a researcher developing methods using mass spectrometry and ion mobility spectrometry to explore chemistry in new ways, currently at the [Organic Synthesis & Mass Spectrometry Lab](https://web.umons.ac.be/smos/) at the University of Mons (Belgium).

<p class="section-label">Research interests</p>
<div class="tags">
  <span class="tag">Mass spectrometry</span>
  <span class="tag">Ion mobility spectrometry</span>
  <span class="tag">Analytical chemistry</span>
  <span class="tag">Reaction mechanisms and dynamics</span>
</div>

<p class="section-label">Career</p>
<div class="timeline">
  <div class="tl-item">
    <span class="tl-period">2023 – present</span>
    <div class="tl-body">
      <p class="tl-title">Chargé de Recherches, FNRS</p>
      <p class="tl-sub"><a href="https://web.umons.ac.be/smos/">S2MOS Lab</a> · University of Mons, Belgium</p>
    </div>
  </div>
  <div class="tl-item">
    <span class="tl-period">2022 – 2023</span>
    <div class="tl-body">
      <p class="tl-title">Postdoctoral Researcher</p>
      <p class="tl-sub"><a href="https://www.hucklab.com/">Huck Group</a> · Radboud University, Nijmegen, The Netherlands</p>
    </div>
  </div>
  <div class="tl-item">
    <span class="tl-period">2020 – 2022</span>
    <div class="tl-body">
      <p class="tl-title">Postdoctoral Researcher</p>
      <p class="tl-sub"><a href="https://www.roithova-group.com/">Roithová Group</a> · Radboud University, Nijmegen, The Netherlands</p>
    </div>
  </div>
  <div class="tl-item">
    <span class="tl-period">2016 – 2020</span>
    <div class="tl-body">
      <p class="tl-title">Aspirant FNRS — PhD Student</p>
      <p class="tl-sub"><a href="https://web.umons.ac.be/smos/">S2MOS Lab</a> · University of Mons, Belgium · Supervised by Pascal Gerbaux &amp; Jérôme Cornil</p>
    </div>
  </div>
</div>

<p class="section-label">Contact</p>
<div class="contact-block">
  ✉️ quentin.duez [at] umons.ac.be
</div>
