---
layout: default
title: Publications
permalink: /publications.html
---

<style>
/* ==========================================
   PUBLICATIONS PAGE
========================================== */

.publications-page {
  --pub-navy: #203451;
  --pub-blue: #426eaa;
  --pub-muted: #617186;
  --pub-line: #e5eaf0;
  --pub-soft: #f5f8fc;
}

/* Introduction */

.publications-page .pub-header {
  padding: 40px 0 48px;
  border-bottom: 1px solid var(--pub-line);
}

.publications-page .pub-eyebrow {
  color: var(--pub-blue);
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 2px;
  margin-bottom: 14px;
}

.publications-page .pub-header h1 {
  font-size: clamp(36px, 4vw, 48px);
  color: var(--pub-navy);
  letter-spacing: -1px;
  margin: 0 0 20px;
}

.publications-page .pub-intro {
  max-width: 850px;
  font-size: 20px;
  line-height: 1.7;
  color: var(--pub-muted);
  margin: 0;
}

/* Sections */

.publications-page .pub-section {
  padding: 50px 0;
  border-bottom: 1px solid var(--pub-line);
}

.publications-page .pub-section-label {
  font-size: 12px;
  font-weight: 700;
  letter-spacing: 1.7px;
  color: var(--pub-blue);
  margin-bottom: 10px;
}

.publications-page .pub-section h2 {
  font-size: 30px;
  color: var(--pub-navy);
  margin: 0 0 12px;
}

.publications-page .pub-section-description {
  font-size: 17px;
  color: var(--pub-muted);
  margin-bottom: 28px;
}

/* Publication entries */

.publications-page .pub-entry {
  padding: 24px 0;
  border-bottom: 1px solid var(--pub-line);
}

.publications-page .pub-entry:last-child {
  border-bottom: none;
}

.publications-page .pub-title {
  font-size: 20px;
  font-weight: 650;
  line-height: 1.55;
  color: var(--pub-navy);
  margin: 0 0 12px;
}

.publications-page .pub-authors {
  font-size: 17px;
  line-height: 1.65;
  color: var(--pub-muted);
  margin: 0 0 8px;
}

.publications-page .pub-authors strong {
  color: var(--pub-navy);
}

.publications-page .pub-venue {
  font-size: 17px;
  color: var(--pub-blue);
  font-weight: 500;
  margin: 0;
}

/* Featured recent research */

.publications-page .featured-entry {
  background: var(--pub-soft);
  border-left: 3px solid var(--pub-blue);
  border-radius: 0 8px 8px 0;
  padding: 24px 28px;
  margin-bottom: 16px;
}

.publications-page .featured-entry:last-child {
  margin-bottom: 0;
}

.publications-page .pub-tag {
  display: inline-block;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1px;
  color: var(--pub-blue);
  margin-bottom: 12px;
}

/* Conference presentations */

.publications-page .conference-entry {
  display: grid;
  grid-template-columns: 110px minmax(0, 1fr);
  gap: 24px;
  padding: 20px 0;
  border-bottom: 1px solid var(--pub-line);
}

.publications-page .conference-entry:last-child {
  border-bottom: none;
}

.publications-page .conference-year {
  color: var(--pub-blue);
  font-size: 16px;
  font-weight: 700;
}

.publications-page .conference-title {
  font-size: 18px;
  line-height: 1.65;
  color: var(--pub-navy);
  margin: 0;
}

.publications-page .conference-status {
  color: var(--pub-muted);
  font-size: 14px;
  margin: 6px 0 0;
}

/* Mobile */

@media (max-width: 760px) {

  .publications-page .pub-header {
    padding: 28px 0 38px;
  }

  .publications-page .pub-intro {
    font-size: 18px;
  }

  .publications-page .pub-section {
    padding: 38px 0;
  }

  .publications-page .pub-section h2 {
    font-size: 26px;
  }

  .publications-page .pub-title {
    font-size: 19px;
  }

  .publications-page .pub-authors,
  .publications-page .pub-venue {
    font-size: 16px;
  }

  .publications-page .featured-entry {
    padding: 20px;
  }

  .publications-page .conference-entry {
    grid-template-columns: 1fr;
    gap: 6px;
  }
}
</style>

<div class="publications-page">

  <!-- INTRODUCTION -->
  <header class="pub-header">

    <div class="pub-eyebrow">
      RESEARCH OUTPUTS
    </div>

    <h1>Publications &amp; Presentations</h1>

    <p class="pub-intro">
      My research explores visual working memory,
      history-dependent biases, and the structure
      and dynamics of visual representations,
      using behavioral, computational,
      and neuroimaging approaches.
    </p>

  </header>


  <!-- PREPRINTS -->
  <section class="pub-section">

    <div class="pub-section-label">
      01 / RECENT RESEARCH
    </div>

    <h2>Preprints</h2>

    <p class="pub-section-description">
      Recent work on relational structure and
      neural representations in visual working memory.
    </p>

    <article class="featured-entry">

      <div class="pub-tag">
        PREPRINT · 2026
      </div>

      <h3 class="pub-title">
        Relational Structure Constrains Individual
        Value Estimates in Visual Working Memory
      </h3>

      <p class="pub-authors">
        <strong>Lim, J.</strong>, &amp; Lee, S. H.
      </p>

      <p class="pub-venue">
        bioRxiv (2026)
      </p>

    </article>

    <article class="featured-entry">

      <div class="pub-tag">
        PREPRINT · 2026
      </div>

      <h3 class="pub-title">
        Early Visual Cortex Represents Sensory and
        Mnemonic Orientations in Separate Subspaces
        with Preserved Geometry
      </h3>

      <p class="pub-authors">
        Kim, S., <strong>Lim, J.</strong>,
        Gu, H., Lee, H., Lee, H. J.,
        Choe, M., et al.
      </p>

      <p class="pub-venue">
        bioRxiv (2026)
      </p>

    </article>

  </section>


  <!-- MANUSCRIPT IN PREPARATION -->
  <section class="pub-section">

    <div class="pub-section-label">
      02 / ONGOING WORK
    </div>

    <h2>Manuscripts in Preparation</h2>

    <article class="pub-entry">

      <h3 class="pub-title">
        Stimulus-Specific Bias in Visual Working Memory
        Reflects the Asymmetry of Cortical
        Representational Geometry
      </h3>

      <p class="pub-authors">
        <strong>Lim, J.</strong>, et al.
      </p>

      <p class="pub-venue">
        Manuscript in preparation
      </p>

    </article>

  </section>


  <!-- PEER-REVIEWED PUBLICATIONS -->
  <section class="pub-section">

    <div class="pub-section-label">
      03 / PUBLISHED WORK
    </div>

    <h2>Peer-Reviewed Publications</h2>

    <article class="pub-entry">

      <h3 class="pub-title">
        Decision-Consistent Bias Mediated by
        Drift Dynamics of Human Visual Working Memory
      </h3>

      <p class="pub-authors">
        Gu, H., Lee, J., Kim, S.,
        <strong>Lim, J.</strong>,
        Lee, H. J., Lee, H., et al.
      </p>

      <p class="pub-venue">
        Neuron (2025)
      </p>

    </article>

    <article class="pub-entry">

      <h3 class="pub-title">
        Canonical Cortico-Hippocampal Dynamics
        Underlie Memory of Navigational Episodes
        and Its Deterioration in Aging
      </h3>

      <p class="pub-authors">
        <strong>Lim, J.</strong>,
        Park, S., Lee, S. H., &amp; Lee, S. A.
      </p>

      <p class="pub-venue">
        Imaging Neuroscience (2025)
      </p>

    </article>

    <article class="pub-entry">

      <h3 class="pub-title">
        Belief Updating in Decision-Variable Space:
        Past Decisions with Finer Granularity
        Attract Future Ones More Strongly
      </h3>

      <p class="pub-authors">
        Lee, H., <strong>Lim, J.</strong>,
        &amp; Lee, S. H.
      </p>

      <p class="pub-venue">
        iScience (2025)
      </p>

    </article>

    <article class="pub-entry">

      <h3 class="pub-title">
        Spatial Correspondence in Relative Space
        Regulates Serial Dependence
      </h3>

      <p class="pub-authors">
        <strong>Lim, J.</strong>, &amp; Lee, S. H.
      </p>

      <p class="pub-venue">
        Scientific Reports (2023)
      </p>

    </article>

    <article class="pub-entry">

      <h3 class="pub-title">
        Utility and Use of Accuracy Cues
        in Social Learning of Crowd Preferences
      </h3>

      <p class="pub-authors">
        <strong>Lim, J.</strong>, &amp; Lee, S. H.
      </p>

      <p class="pub-venue">
        PLOS ONE (2020)
      </p>

    </article>

  </section>


  <!-- CONFERENCE PRESENTATIONS -->
  <section class="pub-section">

    <div class="pub-section-label">
      04 / CONFERENCES
    </div>

    <h2>Selected Conference Presentations</h2>

    <div class="conference-entry">

      <div class="conference-year">
        SfN 2026
      </div>

      <div>
        <p class="conference-title">
          Biased Orientation Geometry in Early Visual Cortex
          Strengthens During Working Memory Maintenance
          and Tracks Individual Behavioral Bias
        </p>
        <p class="conference-status">
          Poster presentation · November 16, 2026 (upcoming)
        </p>
      </div>

    </div>

    <div class="conference-entry">

      <div class="conference-year">
        SfN 2025
      </div>

      <p class="conference-title">
        Recent Decisions Override Older History
        in Serial Dependence
      </p>

    </div>

    <div class="conference-entry">

      <div class="conference-year">
        VSS 2025
      </div>

      <p class="conference-title">
        Serial Dependence in Target Estimation
        Becomes More Pronounced with Increasing
        Temporal Variations in the Context
      </p>

    </div>

    <div class="conference-entry">

      <div class="conference-year">
        SfN 2024
      </div>

      <p class="conference-title">
        Similarity in Brain Activity Dynamics
        Across Individuals During Navigation
        and Its Prediction of Spatial Memory Performance
      </p>

    </div>

    <div class="conference-entry">

      <div class="conference-year">
        OHBM 2024
      </div>

      <p class="conference-title">
        Shared Cortical Activation Dynamics Across
        Subjects During Virtual Navigation and
        Its Prediction of Successful Encoding
        of Navigation Episodes
      </p>

    </div>

  </section>

</div>
