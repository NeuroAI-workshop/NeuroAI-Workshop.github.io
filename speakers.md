---
layout: page
title: "Speakers"
permalink: /speakers/
---

Meet the speakers who will be presenting at the NeuroAI Workshop. We have a diverse lineup of experts from the fields of neuroscience and artificial intelligence.

<style>
  .speaker-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 34px 26px;
    margin: 30px auto 20px auto;
  }

  .speaker-card {
    flex: 1 1 calc(33.33% - 30px);
    max-width: 260px;
    box-sizing: border-box;
    text-align: center;
  }

  .speaker-card img {
    width: 185px;
    height: 185px;
    max-width: 100%;
    aspect-ratio: 1 / 1;
    border-radius: 24%;
    margin-bottom: 12px;
    object-fit: cover;
    object-position: center;
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

  .speaker-info {
    font-size: 0.9em;
    line-height: 1.25;
  }

  /* .speaker-info strong {
    font-size: 1.2em;
    color: blue;
  }

  .speaker-info a {
    color: blue;
    text-decoration: none;
  }

  .speaker-info a:hover {
    text-decoration: underline;
  } */

  .speaker-info strong {
  font-size: 1.2em;
  color: #1f3a5f;
  font-weight: 700;
}

.speaker-info a {
  color: #1f3a5f;
  text-decoration: none;
}

.speaker-info a:hover {
  color: #2f6f9f;
  text-decoration: underline;
}

  @media (max-width: 900px) {
    .speaker-card {
      flex: 1 1 calc(50% - 24px);
      max-width: 240px;
    }

    .speaker-card img {
      width: 165px;
      height: 165px;
    }
  }

  @media (max-width: 560px) {
    .speaker-grid {
      gap: 28px;
    }

    .speaker-card {
      flex: 1 1 100%;
      max-width: 100%;
    }

    .speaker-card img {
      width: 145px;
      height: 145px;
      border-radius: 24%;
    }

    .speaker-info {
      font-size: 0.88em;
      max-width: 270px;
      margin: 0 auto;
    }

    .speaker-info strong {
      font-size: 1.1em;
    }
  }

  @keyframes blink {
    0% { opacity: 0; }
    33% { opacity: 1; }
    66% { opacity: 0; }
  }

  .dots::after {
    content: ' ...';
    animation: blink 1s infinite steps(1, start);
  }
</style>

<div class="speaker-grid">

  <div class="speaker-card">
    <img src="{{ site.baseurl }}/images/organizers/Joshua Tenenbaum.jpg" alt="Joshua Tenenbaum">
    <div class="speaker-info">
      <strong>
        <a href="https://cocosci.mit.edu/josh-tenenbaum/">Joshua Tenenbaum</a>
      </strong><br>
      MIT
    </div>
  </div>

  <div class="speaker-card">
    <img src="{{ site.baseurl }}/images/organizers/Ida_Momennejad_photo.jpg" alt="Ida Momennejad">
    <div class="speaker-info">
      <strong>
        <a href="https://www.momen-nejad.org/">Ida Momennejad</a>
      </strong><br>
      Microsoft Research
    </div>
  </div>

  <div class="speaker-card">
    <img src="{{ site.baseurl }}/images/organizers/tom oxley.avif" alt="Tom Oxley">
    <div class="speaker-info">
      <strong>
        <a href="https://findanexpert.unimelb.edu.au/profile/439055-thomas-oxley">Tom Oxley</a>
      </strong><br>
      Synchron
    </div>
  </div>

  <div class="speaker-card">
    <img src="{{ site.baseurl }}/images/organizers/Ila Fiete.png" alt="Ila Fiete">
    <div class="speaker-info">
      <strong>
        <a href="https://mcgovern.mit.edu/profile/ila-fiete/">Ila Fiete</a>
      </strong><br>
      MIT
    </div>
  </div>

  <div class="speaker-card">
    <img src="{{ site.baseurl }}/images/organizers/Ratan Murty.jpg" alt="Ratan Murty">
    <div class="speaker-info">
      <strong>
        <a href="https://www.murtylab.com/">Ratan Murty</a>
      </strong><br>
      Georgia Tech
    </div>
  </div>

  <div class="speaker-card">
    <img src="{{ site.baseurl }}/images/organizers/Adrienne Fairhall.png" alt="Adrienne Fairhall">
    <div class="speaker-info">
      <strong>
        <a href="https://fairhalllab.com/people/">Adrienne Fairhall</a>
      </strong><br>
      University of Washington
    </div>
  </div>

</div>

## Talk Titles

- **Joshua Tenenbaum:** “TBA”
- **Ida Momennejad:** “The Compositional Geometry of Reasoning in Brains and AI”
- **Tom Oxley:** “First-look: Foundation models of human motor control through scalable intracranial BCIs”
- **Ila Fiete:** “Structured memory for efficient generalization, transfer, and robustness to catastrophic forgetting in the brain”
- **Ratan Murty:** “In-silico replications and hypothesis testing for model benchmarking”
- **Adrienne Fairhall:** "TBA"

## Panelists

<p><strong>Watch this space. Planning for another exciting panel discussion on NeuroAI Transfer, Robustness, and Alignment, moderated by Patrick Mineault, is underway</strong><span class="dots"></span></p>
