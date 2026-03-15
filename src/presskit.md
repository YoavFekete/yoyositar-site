---
layout: layouts/base.njk
title: Press Kit
seoTitle: Press Kit | YoYo Sitar
description: Professional press kit for YoYo Sitar - bio, music, video, photos, practical info, and downloadable press assets for festivals, venues, media, and collaborators.
permalink: /presskit/index.html
bodyClass: presskit
ogImage: /assets/img/og/default2.jpg
ogImageAlt: YoYo Sitar performing live on stage.
ogImageWidth: 1536
ogImageHeight: 1024
---

<section class="epk-hero">
  <div class="epk-hero-copy">
    <p class="epk-kicker">Electronic Press Kit</p>
    <h1>Press Kit</h1>
    <p class="epk-lead">Contemporary sitar artist blending Indian raga, African string traditions, improvisation, and modern groove.</p>
    <div class="epk-actions">
      <a class="epk-button epk-button-primary" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener">Download Assets</a>
      <a class="epk-button epk-button-secondary" href="/contact/">Contact / Booking</a>
    </div>
  </div>
  <div class="epk-hero-meta">
    <div class="epk-stat">
      <span class="epk-stat-label">Performed in</span>
      <span class="epk-stat-value">India | Japan | Europe | Israel</span>
    </div>
    <div class="epk-stat">
      <span class="epk-stat-label">Current focus</span>
      <span class="epk-stat-value">Debut EP arriving in 2026</span>
    </div>
    <div class="epk-stat">
      <span class="epk-stat-label">Formats</span>
      <span class="epk-stat-value">Solo | Duo | Ensemble | Immersive sets</span>
    </div>
  </div>
</section>

<section class="epk-section">
  <div class="epk-section-head">
    <p class="epk-section-kicker">Short Bio</p>
    <h2>Artist Bio</h2>
  </div>
  <div class="epk-bio-card">
    <p>YoYo Sitar (Yoav Fekete) is a contemporary sitar artist whose work moves between Indian raga, West African string traditions, improvisation, and modern groove. After more than two decades of musical exploration across cultures, he has developed a language that feels rooted, spacious, and emotionally direct rather than stylistically combined on the surface. His journey has included deep study of Indian classical music, years inside Turkish and West African musical worlds, and a growing body of performances that range from intimate listening concerts to groove-oriented festival stages. Current projects include the cross-cultural Afro-Raga collaboration, classical-leaning raga programs, immersive sound journeys, and a debut EP scheduled for 2026.</p>
    <a class="epk-inline-link" href="/about/">Read full bio</a>
  </div>
</section>

<section class="epk-section">
  <div class="epk-section-head">
    <p class="epk-section-kicker">Key Highlights</p>
    <h2>At a Glance</h2>
  </div>
  <div class="epk-grid epk-grid-highlights">
    <article class="epk-card">
      <h3>Artistic identity</h3>
      <ul class="epk-list">
        <li>Contemporary sitar voice rooted in Indian raga and living improvisation</li>
        <li>Cross-cultural language shaped by African string traditions, rhythm, and groove</li>
      </ul>
    </article>
    <article class="epk-card">
      <h3>Performance range</h3>
      <ul class="epk-list">
        <li>Solo sitar concerts, duo and trio formats, expanded festival ensembles</li>
        <li>Adaptable for concert halls, festivals, cultural events, retreats, and intimate rooms</li>
      </ul>
    </article>
    <article class="epk-card">
      <h3>Collaborative work</h3>
      <ul class="epk-list">
        <li>Afro-Raga with kora player Tomer Yehieli</li>
        <li>Raga + Voice with vocalist Aakash Singh and classical-leaning ensemble formats</li>
      </ul>
    </article>
    <article class="epk-card">
      <h3>Current release arc</h3>
      <ul class="epk-list">
        <li>Debut EP in progress for 2026</li>
        <li><em>Evening Rise</em> currently featured as an early glimpse from that release cycle</li>
      </ul>
    </article>
  </div>
</section>

<section class="epk-section">
  <div class="epk-section-head">
    <p class="epk-section-kicker">Music</p>
    <h2>Featured Listening</h2>
  </div>
  <div class="epk-grid epk-grid-media">
    <article class="epk-card epk-audio-card">
      <p class="epk-audio-kicker">Featured track preview</p>
      <h3>Evening Rise</h3>
      <audio controls preload="none">
        <source src="/assets/music/intro_1_min.mp3" type="audio/mpeg" />
      </audio>
      <p class="epk-muted">First glimpse from the 2026 EP.</p>
    </article>
    <article class="epk-card epk-links-card">
      <h3>Streaming & artist links</h3>
      <div class="epk-link-stack">
        <a href="{{ site.social.spotify }}" target="_blank" rel="noopener">Spotify</a>
        <a href="{{ site.social.bandcamp }}" target="_blank" rel="noopener">Bandcamp</a>
        <a href="/music/">Music page</a>
      </div>
    </article>
  </div>
</section>

<section class="epk-section">
  <div class="epk-section-head">
    <p class="epk-section-kicker">Video</p>
    <h2>Featured Video</h2>
  </div>
  {% set videoId = "SRGkXtQMU0E" %}
  {% set videoTitle = "Freedom - official music video by YoYo Sitar" %}
  {% include "components/video.njk" %}
</section>

<section class="epk-section">
  <div class="epk-section-head">
    <p class="epk-section-kicker">Press Photos</p>
    <h2>Selected Images</h2>
  </div>
  <div class="epk-photo-grid">
    <figure class="epk-photo"><img src="/assets/img/home4.jpg" alt="YoYo Sitar portrait in a cinematic black-and-white setting." loading="lazy"></figure>
    <figure class="epk-photo"><img src="/assets/img/home5.jpg" alt="YoYo Sitar portrait with sitar in dramatic stage light." loading="lazy"></figure>
    <figure class="epk-photo"><img src="/assets/img/og/default2.jpg" alt="YoYo Sitar performing live on stage." loading="lazy"></figure>
    <figure class="epk-photo"><img src="/assets/img/og/afro-raga.jpg" alt="YoYo Sitar performing Afro-Raga live with kora." loading="lazy"></figure>
    <figure class="epk-photo"><img src="/assets/img/og/raga-voice2.jpg" alt="YoYo Sitar performing with a vocalist in desert concert setting." loading="lazy"></figure>
    <figure class="epk-photo"><img src="/assets/img/og/solo2.jpg" alt="YoYo Sitar in an intimate live sitar concert." loading="lazy"></figure>
  </div>
  <p class="epk-actions">
    <a class="epk-button epk-button-secondary" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener">Download Hi-Res Photos</a>
  </p>
</section>

<section class="epk-section">
  <div class="epk-section-head">
    <p class="epk-section-kicker">Notable Mentions</p>
    <h2>Projects, Context, and Collaborations</h2>
  </div>
  <div class="epk-grid epk-grid-quotes">
    <article class="epk-card">
      <h3>Live contexts</h3>
      <p>Performed in India, Japan, Europe, and Israel across festivals, cultural events, listening concerts, and immersive gatherings.</p>
    </article>
    <article class="epk-card">
      <h3>Collaborative line</h3>
      <p>Current collaborations and project formats include Afro-Raga with Tomer Yehieli, Raga + Voice, solo sitar concerts, and adaptable ensemble configurations.</p>
    </article>
    <article class="epk-card">
      <h3>Musical background</h3>
      <p>Deep study of Indian classical music alongside long-form immersion in Turkish and West African musical traditions informs the project's cross-cultural depth.</p>
    </article>
  </div>
</section>

<section class="epk-section">
  <div class="epk-section-head">
    <p class="epk-section-kicker">Practical Info</p>
    <h2>Booking Snapshot</h2>
  </div>
  <div class="epk-grid epk-grid-practical">
    <article class="epk-card">
      <h3>Available formats</h3>
      <p>Solo sitar, duo, trio, expanded festival ensemble, raga-based concert, Afro-Raga collaboration, and immersive sound journey formats.</p>
    </article>
    <article class="epk-card">
      <h3>Genres / tags</h3>
      <p>Indian raga | world fusion | Afro-Raga | improvised music | meditative groove | cross-cultural strings.</p>
    </article>
    <article class="epk-card">
      <h3>Booking suitability</h3>
      <p>Festivals, concert halls, cultural centers, listening rooms, retreats, conscious events, and curated collaborative programs.</p>
    </article>
    <article class="epk-card">
      <h3>Technical approach</h3>
      <p>Flexible setups from simple stereo or line-input configurations to expanded staged formats. Full rider and stage information available on request.</p>
    </article>
  </div>
</section>

<section class="epk-section">
  <div class="epk-section-head">
    <p class="epk-section-kicker">Downloads</p>
    <h2>Press Assets</h2>
  </div>
  <div class="epk-grid epk-grid-downloads">
    <a class="epk-download-card" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener"><strong>Short Bio</strong><span>Quick reference copy for programs and press.</span></a>
    <a class="epk-download-card" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener"><strong>Full Bio</strong><span>Long-form background and artistic story.</span></a>
    <a class="epk-download-card" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener"><strong>Press Photos</strong><span>Hi-res image selection for media use.</span></a>
    <a class="epk-download-card" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener"><strong>Logo Pack</strong><span>Brand marks for posters, press, and promo.</span></a>
    <a class="epk-download-card" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener"><strong>Album Artwork</strong><span>Release visuals and cover assets.</span></a>
    <a class="epk-download-card" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener"><strong>Tech Rider / Stage Plot</strong><span>Technical information for presenters and venues.</span></a>
    <a class="epk-download-card" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener"><strong>Full Press Folder</strong><span>Complete collection of downloadable press materials.</span></a>
  </div>
</section>

<section class="epk-section epk-contact">
  <div class="epk-section-head">
    <p class="epk-section-kicker">Contact</p>
    <h2>Press & Booking</h2>
  </div>
  <div class="epk-contact-card">
    <p>For booking, festival enquiries, collaborations, and media requests, use the contact page and include context, dates, and territory if relevant.</p>
    <div class="epk-actions">
      <a class="epk-button epk-button-primary" href="/contact/">Contact / Booking</a>
      <a class="epk-button epk-button-secondary" href="https://drive.google.com/drive/folders/1okhIQFjavOFf0ZoTv-CxDTQxbddhsLye" target="_blank" rel="noopener">Open Full Press Folder</a>
    </div>
  </div>
</section>
