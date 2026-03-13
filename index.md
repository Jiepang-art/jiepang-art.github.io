---
layout: default
title: Jie Pang
---

<style>
.hero {
  position: relative;
  min-height: 88vh;
  background-image: url('/assets/images/hero-poster.png');
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: flex-start;
  justify-content: flex-start;
  padding: 4rem 3rem;
  color: white;
}
.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.35);
}
.hero-content {
  position: relative;
  z-index: 1;
  max-width: 760px;
}
.hero-title {
  font-size: 3.4rem;
  line-height: 1.02;
  font-weight: 800;
  text-transform: uppercase;
  letter-spacing: -0.03em;
  margin: 0 0 1.5rem 0;
}
.hero-subtitle {
  font-size: 1.2rem;
  line-height: 1.6;
  max-width: 620px;
}

.section-block {
  margin: 4rem 0 5rem 0;
}

.statement-grid {
  display: grid;
  grid-template-columns: 1.1fr 1fr;
  gap: 2rem;
  align-items: center;
}

.statement-text h2,
.preview h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.statement-text p {
  font-size: 1.1rem;
  line-height: 1.9;
}

.statement-image img,
.preview-grid img {
  width: 100%;
  display: block;
  border-radius: 0;
}

.band-image {
  position: relative;
  margin: 4rem 0;
  min-height: 340px;
  background-image: url('/assets/images/lacquer-structure.png');
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
}
.band-image::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.30);
}
.band-text {
  position: relative;
  z-index: 1;
  color: white;
  padding: 2.5rem;
  max-width: 780px;
}
.band-text h2 {
  font-size: 2.2rem;
  margin-bottom: 1rem;
}
.band-text p {
  font-size: 1.1rem;
  line-height: 1.8;
}

.preview-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.5rem;
}
.preview-card p {
  margin-top: 0.7rem;
  font-size: 0.98rem;
  line-height: 1.7;
}

.section-links ul {
  margin-left: 1.2rem;
}

@media (max-width: 800px) {
  .hero {
    min-height: 72vh;
    padding: 2rem 1.2rem;
  }
  .hero-title {
    font-size: 2.2rem;
  }
  .statement-grid,
  .preview-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="hero">
  <div class="hero-content">
    <div class="hero-title">
      Lacquer Is Appearance<br>
      Structure Is Essence
    </div>
    <div class="hero-subtitle">
      Jie Pang is a lacquer artist, material thinker, and civilization narrator.
      Through lacquer, painting, writing, and digital image-making, he explores
      surface, structure, time, and civilizational memory.
    </div>
  </div>
</div>

<div class="section-block statement-grid">
  <div class="statement-text">
    <h2>Material Statement</h2>
    <p>
      Lacquer is not merely a material. It is time, memory, and transformation
      made visible. My work approaches lacquer as a civilizational medium: a
      structure through which surfaces are constructed, memory is preserved, and
      permanence is imagined.
    </p>
    <p>
      From Shu lacquer traditions to digital image formation, I investigate how
      layered structure becomes ontology — how appearance is never superficial,
      but the visible face of deep material logic.
    </p>
  </div>
  <div class="statement-image">
    <img src="/assets/images/mirror-lake.png" alt="Mirror Lake lacquer image">
  </div>
</div>

<div class="band-image">
  <div class="band-text">
    <h2>Current Research</h2>
    <p>
      Lacquer as structural ontology · Shu lacquer and civilizational memory ·
      Structural Digitalism · Cinema, surface, and deep-time narrative
    </p>
  </div>
</div>

<div class="section-block preview">
  <h2>Selected Visual Directions</h2>
  <div class="preview-grid">
    <div class="preview-card">
      <img src="/assets/images/lacquer-structure.png" alt="Lacquer structure work">
      <p>
        Digital lacquer structures: fractured planes, sedimented light, and the
        logic of appearance as constructed surface.
      </p>
    </div>
    <div class="preview-card">
      <img src="/assets/images/pier-drawing.png" alt="Pier drawing">
      <p>
        Structural drawing and spatial framework: the skeletal logic beneath
        visible form, where line and support become spatial philosophy.
      </p>
    </div>
  </div>
</div>

<div class="section-block section-links">
  <h2>Sections</h2>
  <ul>
    <li><a href="/works">Works</a></li>
    <li><a href="/writing">Writing</a></li>
    <li><a href="/about">About</a></li>
  </ul>
</div>
