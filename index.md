
---
layout: default
title: Home
---

<style>
/* ── Base ── */
.research-home {
  --navy: #203451;
  --blue: #426eaa;
  --muted: #617186;
  --line: #e5eaf0;
  --soft: #f5f8fc;
  color: var(--navy);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
               Helvetica, Arial, sans-serif;
  line-height: 1.75;
}

.research-home * {
  box-sizing: border-box;
}

/* ── Hero ── */
.research-home .hero {
  padding: 64px 0 54px;
  border-bottom: 1px solid var(--line);
}

.research-home .eyebrow {
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: var(--blue);
  margin-bottom: 18px;
}

.research-home .hero h1 {
  font-size: clamp(40px, 6vw, 62px);
  font-weight: 750;
  letter-spacing: -2px;
  line-height: 1.15;
  margin: 0 0 18px;
  color: var(--navy);
  border: none;
}

.research-home .hero-subtitle {
  font-size: 19px;
  color: var(--blue);
  font-weight: 500;
  margin-bottom: 30px;
}

.research-home .hero-statement {
  font-size: clamp(21px, 3vw, 27px);
  font-weight: 500;
  line-height: 1.55;
  max-width: 800px;
  margin: 0 0 24px;
  letter-spacing: -0.4px;
}

.research-home .hero-statement strong {
  color: var(--blue);
}

.research-home .intro {
  max-width: 760px;
  font-size: 15.5px;
  color: var(--muted);
  line-height: 1.85;
  margin-bottom: 24px;
}

.research-home .position {
  font-size: 13.5px;
  color: var(--muted);
  margin: 0 0 26px;
}

.research-home .position strong {
  color: var(--navy);
}

.research-home .opportunity {
  border-left: 3px solid var(--blue);
  background: var(--soft);
  border-radius: 0 6px 6px 0;
  padding: 13px 18px;
  font-size: 14px;
  color: var(--muted);
  max-width: 760px;
}

/* ── Sections ── */
.research-home .section {
  padding: 52px 0 48px;
  border-bottom: 1px solid var(--line);
}

.research-home .section-label {
  color: var(--blue);
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 8px;
}

.research-home .section h2 {
  color: var(--navy);
  font-size: 27px;
  font-weight: 700;
  letter-spacing: -0.7px;
  border: none;
  margin: 0 0 14px;
}

.research-home .section-description {
  color: var(--muted);
  font-size: 15px;
  max-width: 700px;
  margin: 0 0 28px;
}

/* ── Research cards ── */
.research-home .research-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
}

.research-home .research-card {
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 10px;
  padding: 25px 22px;
  transition: transform 0.2s ease,
              box-shadow 0.2s ease,
              border-color 0.2s ease;
}

.research-home .research-card:hover {
  transform: translateY(-4px);
  border-color: #c7d7ec;
  box-shadow: 0 10px 28px rgba(32,52,81,0.07);
}

.research-home .card-number {
  font-size: 12px;
  color: var(--blue);
  font-weight: 700;
  letter-spacing: 1px;
  margin-bottom: 18px;
}

.research-home .research-card h3 {
  color: var(--navy);
  font-size: 18px;
  line-height: 1.4;
  font-weight: 700;
  margin: 0 0 13px;
  border: none;
}

.research-home .research-card .question {
  color: var(--blue);
  font-size: 13.5px;
  font-weight: 600;
  line-height: 1.65;
  margin-bottom: 15px;
}

.research-home .research-card p {
  color: var(--muted);
  font-size: 13.5px;
  line-height: 1.8;
  margin-bottom: 0;
}

/* ── Methods ── */
.research-home .methods-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 24px;
}

.research-home .method {
  border-top: 2px solid var(--line);
  padding-top: 18px;
}

.research-home .method h3 {
  color: var(--navy);
  font-size: 15px;
  margin: 0 0 8px;
  font-weight: 700;
  border: none;
}

.research-home .method p {
  color: var(--muted);
  font-size: 13.5px;
  margin: 0;
  line-height: 1.7;
}

/* ── Navigation ── */
.research-home .home-nav {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  padding: 36px 0 25px;
}

.research-home .home-nav a {
  display: inline-block;
  padding: 11px 21px;
  border: 1px solid var(--line);
  border-radius: 6px;
  color: var(--navy);
  font-size: 13.5px;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.2s ease;
}

.research-home .home-nav a:hover {
  background: var(--soft);
  border-color: var(--blue);
  color: var(--blue);
  text-decoration: none;
}

.research-home .home-nav a.primary {
  background: var(--navy);
  border-color: var(--navy);
  color: white;
}

.research-home .home-nav a.primary:hover {
  background: var(--blue);
  border-color: var(--blue);
}

/* ── Mobile ── */
@media (max-width: 760px) {
  .research-home .hero {
    padding: 38px 0 40px;
  }

  .research-home .research-grid,
  .research-home .methods-grid {
    grid-template-columns: 1fr;
  }

  .research-home .section {
    padding: 38px 0;
  }

  .research-home .research-card {
    padding: 22px;
  }

  .research-home .hero h1 {
    letter-spacing: -1px;
  }

  .research-home .home-nav a {
    flex: 1 1 42%;
    text-align: center;
  }
}
</style>

<div class="research-home">

  <!-- HERO -->
  <header class="hero">

    <div class="eyebrow">
      Cognitive Neuroscience
    </div>

    <h1>Jaeseob Lim</h1>

    <div class="hero-subtitle">
      Visual Working Memory &amp; Visual Cognition
    </div>

    <p class="hero-statement">
      I study how
      <strong>interactions and representational structure</strong>
      shape visual working memory and cognition.
    </p>

    <p class="intro">
      My research investigates how visual representations are
      influenced by past experiences and decisions, constrained
      by relationships with other representations, and shaped
      by the underlying geometry of representational space.
      I am particularly interested in how these interactions
      and structural properties relate to systematic biases
      in visual memory and behavior.
    </p>

    <p class="position">
      <strong>Research Assistant Professor</strong><br>
      Brain Imaging Center · Seoul National University
    </p>

    <div class="opportunity">
      I am currently seeking postdoctoral opportunities
      in cognitive neuroscience, psychology,
      and related fields.
    </div>

  </header>


  <!-- RESEARCH -->
  <section class="section">

    <div class="section-label">01 / Research</div>

    <h2>Research Interests</h2>

    <p class="section-description">
      I explore how visual representations are shaped by
      interactions across time, relationships between items,
      and the structure of representational space.
    </p>

    <div class="research-grid">

      <div class="research-card">
        <div class="card-number">01 — ACROSS TIME</div>

        <h3>History Effects<br>in Visual Cognition</h3>

        <div class="question">
          How do past experiences and decisions
          shape current visual cognition?
        </div>

        <p>
          Serial dependence and history-dependent biases,
          with a focus on previous decisions,
          contextual information, and task relevance.
        </p>
      </div>

      <div class="research-card">
        <div class="card-number">02 — ACROSS ITEMS</div>

        <h3>Relational Structure<br>in Working Memory</h3>

        <div class="question">
          How do relationships between remembered
          items constrain individual representations?
        </div>

        <p>
          Interactions between memory contents,
          relational constraints, and the organization
          of multiple visual representations
          in working memory.
        </p>
      </div>

      <div class="research-card">
        <div class="card-number">03 — REPRESENTATIONAL SPACE</div>

        <h3>Representational<br>Geometry &amp; Biases</h3>

        <div class="question">
          How does the geometry of neural representations
          relate to systematic behavioral biases?
        </div>

        <p>
          Neural representational structure,
          non-uniform geometry, and their relationships
          with behavioral biases during
          working memory maintenance.
        </p>
      </div>

    </div>
  </section>


  <!-- METHODS -->
  <section class="section">

    <div class="section-label">02 / Approaches</div>

    <h2>Research Methods</h2>

    <p class="section-description">
      Combining behavioral, neural, and computational
      approaches to understand visual memory and cognition.
    </p>

    <div class="methods-grid">

      <div class="method">
        <h3>Behavioral Experiments</h3>
        <p>
          Visual psychophysics<br>
          Web-based experiments<br>
          Laboratory experiments
        </p>
      </div>

      <div class="method">
        <h3>Neuroimaging</h3>
        <p>
          Functional MRI<br>
          EEG<br>
          Eye-tracking
        </p>
      </div>

      <div class="method">
        <h3>Computational Approaches</h3>
        <p>
          Computational modeling<br>
          Multivariate pattern analysis<br>
          Representational similarity analysis
        </p>
      </div>

    </div>
  </section>


  <!-- NAVIGATION -->
  <nav class="home-nav" aria-label="Main pages">
    <a class="primary" href="./research.html">Research</a>
    <a href="./publications.html">Publications</a>
    <a href="./cv.html">CV</a>
    <a href="./contact.html">Contact</a>
  </nav>

</div>
