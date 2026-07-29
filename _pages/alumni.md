from pathlib import Path

content = r'''---
title: "Alumni"
permalink: /alumni/
layout: single
author_profile: true
---

<style>
:root {
  --alumni-card-bg: #ffffff;
  --alumni-card-text: #333333;
  --alumni-card-title: #3d2c8d;
  --alumni-card-muted: #666666;
  --alumni-card-border: #e2e2e2;
  --alumni-card-shadow: 0 4px 16px rgba(0, 0, 0, 0.07);
}

html[data-theme="dark"] {
  --alumni-card-bg: #242424;
  --alumni-card-text: #f2f2f2;
  --alumni-card-title: #a394f0;
  --alumni-card-muted: #c6c6c6;
  --alumni-card-border: #444444;
  --alumni-card-shadow: 0 4px 16px rgba(0, 0, 0, 0.30);
}

.alumni-intro {
  margin-bottom: 2rem;
}

.alumni-section {
  margin-top: 2.25rem;
}

.alumni-section h2 {
  margin-bottom: 1rem;
}

.alumni-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}

.alumni-card {
  padding: 1rem 1.15rem;
  border: 1px solid var(--alumni-card-border);
  border-left: 4px solid #18453b;
  border-radius: 12px;
  background: var(--alumni-card-bg);
  color: var(--alumni-card-text);
  box-shadow: var(--alumni-card-shadow);
}

.alumni-name {
  margin: 0 0 0.25rem 0;
  font-size: 1.02rem;
  line-height: 1.3;
  font-weight: 700;
  color: var(--alumni-card-title);
}

.alumni-name a {
  color: var(--alumni-card-title) !important;
  text-decoration: none;
}

.alumni-name a:hover {
  text-decoration: underline;
}

.alumni-meta {
  margin: 0;
  color: var(--alumni-card-muted);
  font-size: 0.92rem;
  line-height: 1.4;
}

.alumni-note {
  margin-top: 2.5rem;
  font-size: 0.88rem;
  color: var(--global-text-color-light, #666666);
}

@media screen and (max-width: 760px) {
  .alumni-grid {
    grid-template-columns: 1fr;
  }
}
</style>

# Alumni

<p class="alumni-intro">
Former members of the Hamann Lab are listed by their role in the group. Names link to a current professional or institutional profile when one could be confidently identified.
</p>

<!--
OPTIONAL ALUMNI PHOTO

Upload a photo as:
images/alumni-group.jpg

Then remove the opening and closing comment markers around the image block below.

<figure style="margin: 0 0 2rem 0;">
  <img
    src="{{ '/images/alumni-group.jpg' | relative_url }}"
    alt="Hamann Lab alumni and group members"
    style="width: 100%; max-height: 430px; object-fit: cover; border-radius: 14px;"
  >
  <figcaption style="margin-top: 0.45rem; font-size: 0.85rem; color: var(--global-text-color-light, #666666);">
    Hamann Lab alumni and group members.
  </figcaption>
</figure>
-->

<section class="alumni-section">
  <h2>PhD Alumni</h2>

  <div class="alumni-grid">

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/jesse-ondersma-61a64425" target="_blank" rel="noopener noreferrer">Jesse W. Ondersma</a></p>
      <p class="alumni-meta">PhD, 2012</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/benjaminklahr" target="_blank" rel="noopener noreferrer">Benjamin M. Klahr</a></p>
      <p class="alumni-meta">PhD, 2013</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://chemistry.nd.edu/people/kelley-young/" target="_blank" rel="noopener noreferrer">Kelley M. H. Young</a></p>
      <p class="alumni-meta">PhD, 2014</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/omidzandi" target="_blank" rel="noopener noreferrer">Omid Zandi</a></p>
      <p class="alumni-meta">PhD, 2015</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/yuling-xie-52219479" target="_blank" rel="noopener noreferrer">Yuling Xie</a></p>
      <p class="alumni-meta">PhD, 2015</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/dhritabrata-mandal-phd-b51a5abb" target="_blank" rel="noopener noreferrer">Dhritabrata Mandal</a></p>
      <p class="alumni-meta">PhD, 2017</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/dr-daniel-j-little" target="_blank" rel="noopener noreferrer">Daniel J. Little</a></p>
      <p class="alumni-meta">PhD, 2017</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name">Yuan Gao</p>
      <p class="alumni-meta">PhD, 2017</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/josh-baillargeon-425705136" target="_blank" rel="noopener noreferrer">Josh Baillargeon</a></p>
      <p class="alumni-meta">PhD, 2018</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/hhajibabaei" target="_blank" rel="noopener noreferrer">Hamed Hajibabaei Najafabadi</a></p>
      <p class="alumni-meta">PhD, 2018</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/faeze-habibzadeh" target="_blank" rel="noopener noreferrer">Faezeh Habib Zadeh</a></p>
      <p class="alumni-meta">PhD, 2019</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/wbrightyj" target="_blank" rel="noopener noreferrer">Yujue Wang</a></p>
      <p class="alumni-meta">PhD, 2019</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/parisa-shadabipour-phd-455314ba" target="_blank" rel="noopener noreferrer">Parisa Shadabipour</a></p>
      <p class="alumni-meta">PhD, 2020</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/austin-raithel" target="_blank" rel="noopener noreferrer">Austin Raithel</a></p>
      <p class="alumni-meta">PhD, 2021</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/chuan-pin-chen-b0000b219" target="_blank" rel="noopener noreferrer">Chuan-Pin Chen</a></p>
      <p class="alumni-meta">PhD, 2024</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/eric-firestone-a8b00581" target="_blank" rel="noopener noreferrer">Eric Firestone</a></p>
      <p class="alumni-meta">PhD, 2024</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/soumikdas7" target="_blank" rel="noopener noreferrer">Soumik Das</a></p>
      <p class="alumni-meta">PhD, 2024</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/samhita-kaushik" target="_blank" rel="noopener noreferrer">Samhita Kaushik</a></p>
      <p class="alumni-meta">PhD, 2024</p>
    </div>

  </div>
</section>

<section class="alumni-section">
  <h2>Postdoctoral Alumni</h2>

  <div class="alumni-grid">

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/jasonmthornton" target="_blank" rel="noopener noreferrer">Jason M. Thornton</a></p>
      <p class="alumni-meta">Postdoctoral researcher, 2012–2013</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.niist.res.in/drsuraj-soman" target="_blank" rel="noopener noreferrer">Suraj Soman</a></p>
      <p class="alumni-meta">Postdoctoral researcher, 2011–2014</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://be.linkedin.com/in/jirossero" target="_blank" rel="noopener noreferrer">Jorge Ivan Rossero</a></p>
      <p class="alumni-meta">Postdoctoral researcher, 2014–2015</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://de.linkedin.com/in/arianna-savini-34490239" target="_blank" rel="noopener noreferrer">Arianna Savini</a></p>
      <p class="alumni-meta">Postdoctoral researcher, 2014–2016</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://de.linkedin.com/in/qiong-wang-902393120" target="_blank" rel="noopener noreferrer">Qiong Wang</a></p>
      <p class="alumni-meta">Postdoctoral researcher, 2016–2017</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/geletuqing" target="_blank" rel="noopener noreferrer">Geletu Qing</a></p>
      <p class="alumni-meta">Postdoctoral researcher, 2017–2019</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://orcid.org/0000-0001-8510-8261" target="_blank" rel="noopener noreferrer">Tea-Yon Kim</a></p>
      <p class="alumni-meta">Postdoctoral researcher, 2018–2021</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/cjmi" target="_blank" rel="noopener noreferrer">Chenjia Mi</a></p>
      <p class="alumni-meta">Postdoctoral researcher, 2019–2022</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/susanne-miller-4813a7191" target="_blank" rel="noopener noreferrer">Susanne Miller</a></p>
      <p class="alumni-meta">Postdoctoral researcher, 2017–2022</p>
    </div>

  </div>
</section>

<section class="alumni-section">
  <h2>MS Alumni</h2>

  <div class="alumni-grid">

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/prabodha-b" target="_blank" rel="noopener noreferrer">Prabodha Balapuwaduge</a></p>
      <p class="alumni-meta">MS, 2021</p>
    </div>

  </div>
</section>

<section class="alumni-section">
  <h2>Undergraduate Alumni</h2>

  <div class="alumni-grid">

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/dillon-edwards-abba00126" target="_blank" rel="noopener noreferrer">Dillon Edwards</a></p>
      <p class="alumni-meta">MSU undergraduate, 2013–2016</p>
    </div>

    <div class="alumni-card">
      <p class="alumni-name"><a href="https://www.linkedin.com/in/abe-schon-088056215" target="_blank" rel="noopener noreferrer">Abraham R. Schon</a></p>
      <p class="alumni-meta">Undergraduate researcher</p>
    </div>

  </div>
</section>

<p class="alumni-note">
Alumni may contact the Hamann Lab to add or update a professional profile link.
</p>
'''

path = Path("/mnt/data/alumni.md")
path.write_text(content, encoding="utf-8")
print(f"Created {path} ({len(content.splitlines())} lines)")
