---
layout: default
title: Jie Pang
---

<style>
.hero {
  position: relative;
  min-height: 92vh;
  background-image: url('assets/images/hero-structural-lacquer.png');
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: flex-end;
  padding: 5rem 3rem;
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
  font-size: 3.8rem;
  line-height: 1.05;
  font-weight: 800;
  text-transform: uppercase;
  letter-spacing: -0.03em;
  margin-bottom: 1.5rem;
}

.hero-text {
  font-size: 1.25rem;
  line-height: 1.7;
  max-width: 620px;
}

.section {
  margin: 5rem 0;
}

.statement-grid {
  display: grid;
  grid-template-columns: 1.1fr 1fr;
  gap: 3rem;
  align-items: center;
}

.statement-text h2 {
  font-size: 2.2rem;
  margin-bottom: 1.2rem;
}

.statement-text p {
  font-size: 1.15rem;
  line-height: 1.9;
}

.statement-image img {
  width: 100%;
  display: block;
}

.preview-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}

.preview-card img {
  width: 100%;
  display: block;
}

.preview-card h3 {
  margin-top: 0.8rem;
}

@media (max-width: 800px) {
  .hero {
    min-height: 75vh;
    padding: 3rem 1.5rem;
  }

  .hero-title {
    font-size: 2.5rem;
  }

  .statement-grid {
    grid-template-columns: 1fr;
  }

  .preview-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="hero">
  <div class="hero-content">
    <div class="hero-title">
      Lacquer is Appearance<br>
      Structure is Essence
    </div>
    <div class="hero-text">
      Jie Pang is a lacquer artist, material thinker, and civilization narrator.
      Through lacquer, painting, writing, and digital image-making, he explores surface, structure, time, and civilizational memory.
    </div>
  </div>
</div>

<div class="section statement-grid">
  <div class="statement-text">
    <h2>Material Philosophy</h2>
    <p>
      Lacquer is not merely a material, but a temporal structure — a surface where time condenses into form.
      Through layered processes of accumulation, erosion, and illumination, lacquer becomes a medium for understanding how civilizations construct durability, memory, and metaphysical presence.
    </p>
    <p>
      Pang’s work connects ancient East Asian material systems with contemporary digital image structures, proposing a new ontology of surface and structural perception.
    </p>
  </div>
  <div class="statement-image">
    <img src="assets/images/lacquer-structure.png">
  </div>
</div>

<div class="section">
  <h2>Selected Works</h2>
  <div class="preview-grid">
    <div class="preview-card">
      <img src="assets/images/mirror-lake.png">
      <h3>Mirror Lake Series</h3>
    </div>
    <div class="preview-card">
      <img src="assets/images/pier-drawing.png">
      <h3>Waterfront Studies</h3>
    </div>
  </div>
</div>
