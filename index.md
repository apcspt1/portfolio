---
layout: page
title: My Good Brain
hide: true
hide_title: true
show_reading_time: false
---

<style>
  .mgb-home { --ink: #e6eef8; --muted: #e1e1e6; --accent: #3b82f6; --accent-hover: #60a5fa; --panel: #2b2b2b; --panel-border: rgba(255,255,255,.06); position: relative; left: 50%; width: 100vw; margin-left: -50vw; background: #121212; color: var(--ink); }
  .mgb-home * { box-sizing: border-box; }
  .mgb-home__hero { display: grid; place-items: center; padding: clamp(4rem, 10vw, 7rem) 1.5rem clamp(2.5rem, 6vw, 4rem); color: var(--ink); text-align: center; }
  .mgb-home__hero-copy { max-width: 50rem; margin: 0 auto; }
  .mgb-home__hero h1 { margin: 0 0 1rem; color: #fff; font-size: clamp(2.2rem, 6vw, 3.4rem); font-weight: 800; line-height: 1.2; }
  .mgb-home__hero p { max-width: 46rem; margin: auto; color: var(--muted); font-size: 1.15rem; line-height: 1.6; }
  .mgb-home__section { padding: clamp(3rem, 7vw, 6rem) clamp(1.1rem, 5vw, 4rem); }
  .mgb-home__inner { width: min(100%, 70rem); margin: 0 auto; }
  .mgb-home__mission { display: grid; grid-template-columns: minmax(0, 1.4fr) minmax(14rem, .8fr); gap: clamp(2rem, 6vw, 5rem); align-items: center; }
  .mgb-home .mgb-home__section h2 { margin: 0 0 1rem; color: var(--ink) !important; font-size: clamp(1.8rem, 4vw, 2.8rem); line-height: 1.15; }
  .mgb-home .mgb-home__section p { color: var(--muted) !important; font-size: 1.05rem; line-height: 1.75; }
  .mgb-home__quote { margin: 0; padding: 1.6rem; border: 1px solid var(--panel-border); border-left: 4px solid var(--accent); border-radius: 1rem; background: var(--panel); color: var(--ink); font-size: clamp(1.25rem, 2.4vw, 1.8rem); line-height: 1.4; }
  .mgb-home__quote cite { display: block; margin-top: 1rem; font-size: 1rem; font-style: normal; }
  .mgb-home__button { display: inline-block; margin-top: .75rem; padding: .85rem 1.35rem; border: 1px solid var(--accent); border-radius: .75rem; background: #14294b; color: var(--ink) !important; font-weight: 700; text-decoration: none; transition: background .2s ease, border-color .2s ease; }
  .mgb-home__button:hover { background: var(--accent); border-color: var(--accent-hover); color: #fff !important; }
  .mgb-home__features, .mgb-home__blog { background: transparent; }
  .mgb-home__grid { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 1.25rem; }
  .mgb-home__card { overflow: hidden; border: 1px solid var(--panel-border); border-radius: 1rem; background: var(--panel); box-shadow: 0 8px 26px rgba(0,0,0,.2); }
  .mgb-home__card img { display: block; width: 100%; aspect-ratio: 4 / 3; object-fit: cover; }
  .mgb-home__card-copy { padding: 1.4rem; }
  .mgb-home__card h3 { margin: 0 0 .5rem; color: var(--ink) !important; font-size: 1.35rem; line-height: 1.25; }
  .mgb-home__card p { margin: .4rem 0 1rem; }
  .mgb-home__card a:not(.mgb-home__button) { color: #4bbaff; font-weight: 700; }
  .mgb-home__features .mgb-home__card a:hover { color: #000 !important; }
  .mgb-home__news { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 1rem; }
  .mgb-home__news article { padding: 1.4rem; border: 1px solid var(--panel-border); border-radius: .8rem; background: var(--panel); }
  .mgb-home__news h3 { margin: 0 0 .65rem; color: var(--ink) !important; font-size: 1.25rem; }
  .mgb-home__news a { color: #4bbaff; font-weight: 700; }
  .mgb-home__news a:hover,
  .mgb-home__card a:hover { padding: 0 .15rem; border-radius: .2rem; background: var(--accent-hover); color: #000 !important; }
  .mgb-home__blog .mgb-home__card img { aspect-ratio: 16 / 10; }
  .mgb-home__donate { background: var(--panel); border-top: 1px solid var(--panel-border); border-bottom: 1px solid var(--panel-border); text-align: center; }
  .mgb-home__donate p { max-width: 46rem; margin: 0 auto 1rem; }
  @media (max-width: 760px) { .mgb-home__mission { grid-template-columns: 1fr; } .mgb-home__grid, .mgb-home__news { grid-template-columns: 1fr; } }
</style>

<div class="mgb-home">
  <section class="mgb-home__hero" aria-labelledby="mgb-home-title">
    <div class="mgb-home__hero-copy">
      <h1 id="mgb-home-title">My Good Brain</h1>
      <p>An Arts-Based Nonprofit Organization for Youth Mental Wellness</p>
    </div>
  </section>

  <section class="mgb-home__section">
    <div class="mgb-home__inner mgb-home__mission">
      <div>
        <h2>Bridging Psychology &amp; Art</h2>
        <p>My Good Brain is an arts-based nonprofit focused on promoting mental wellness among school-aged youth.</p>
        <p>Through the vehicle of art and play, we aim to teach children from a young age through adolescence how to practice healthy coping strategies for mental and emotional wellness.</p>
        <a class="mgb-home__button" href="https://www.mygoodbrain.org/our-mission">Our Mission</a>
      </div>
      <blockquote class="mgb-home__quote">“Art is as natural as sunshine and as vital as nourishment.”<cite>— MaryAnn F. Kohl</cite></blockquote>
    </div>
  </section>

  <section class="mgb-home__section mgb-home__features">
    <div class="mgb-home__inner mgb-home__grid">
      <article class="mgb-home__card">
        <img src="https://images.squarespace-cdn.com/content/v1/5ffdf49e3d30d07ea498ac3b/90ab2abe-a907-4e62-bd39-8c2b770fcd45/AdobeStock_671974002.jpeg?format=1500w" alt="Art materials ready for a creative activity" loading="lazy">
        <div class="mgb-home__card-copy"><h3>Homeschool &amp; Enrichment Families</h3><p>Your enrichment funds can come here.</p><a href="{{ '/community/programs/' | relative_url }}">Learn more →</a></div>
      </article>
      <article class="mgb-home__card">
        <img src="https://images.squarespace-cdn.com/content/v1/5ffdf49e3d30d07ea498ac3b/ab267415-4074-4f70-9c17-9ff3b8d82f0e/AdobeStock_494897619.jpeg" alt="Family enjoying an art activity together" loading="lazy">
        <div class="mgb-home__card-copy"><h3>Building Resilient Families Through Art</h3><p>A free resource for San Diego veterans and parents of young children.</p><a href="{{ '/community/programs/' | relative_url }}">Learn more →</a></div>
      </article>
      <article class="mgb-home__card">
        <img src="https://images.squarespace-cdn.com/content/v1/5ffdf49e3d30d07ea498ac3b/1773180586469-4EBY4RXTNIE56GQ9QB6B/unsplash-image-fXkoHG4dYxA.jpg" alt="Creative supplies for expressive art" loading="lazy">
        <div class="mgb-home__card-copy"><h3>Immigration &amp; Family Support Resources</h3><p>Resources to help youth, families, and communities better understand and support the mental health impacts of immigration-related experiences.</p><a href="{{ '/community/programs/' | relative_url }}">Learn more →</a></div>
      </article>
    </div>
  </section>

  <section class="mgb-home__section">
    <div class="mgb-home__inner">
      <h2>News &amp; Updates</h2>
      <div class="mgb-home__news">
        <article><h3>NEW: Scrap Lab</h3><p>Check out our new art class: Scrap Lab! A drop-in upcycling and recycling art class where kids ages 4–12 build, invent, and create freely using recycled and reclaimed materials every Tuesday from 10:00 AM to 12:00 PM at our Liberty Station studio.</p><a href="{{ '/community/events/' | relative_url }}">Join Us →</a></article>
        <article><h3>MGB Family Membership is here!</h3><p>Save money on toddler classes by getting a 10-class pack or Family Membership plan!</p><a href="{{ '/community/events/' | relative_url }}">Sign Up →</a></article>
        <article><h3>Sunday Art Club - Mother's Day Edition</h3><p>Sunday Art Club is back for a special Mother's Day edition! This month we're making handmade gifts for mom using the art of quilling — rolled paper art that looks intricate and impressive but is completely beginner-friendly.</p><a href="{{ '/community/events/' | relative_url }}">Join Us →</a></article>
      </div>
    </div>
  </section>

  <section class="mgb-home__section mgb-home__blog">
    <div class="mgb-home__inner">
      <h2>From the Blog</h2>
      <div class="mgb-home__grid">
        <article class="mgb-home__card"><img src="https://images.squarespace-cdn.com/content/v1/5ffdf49e3d30d07ea498ac3b/1789183399965-1LTFSI8FY7XBDRYTD7TK/unsplash-image-Zzgmde4_lYU.jpg?format=300w" alt="Comfort object" loading="lazy"><div class="mgb-home__card-copy"><h3>Why Comfort Objects Help Kids Through Transitions</h3><p>Small objects can provide children with a sense of safety and resilience as they move through new experiences.</p><a href="https://www.mygoodbrain.org/blog/why-comfort-objects-help-kids-through-transitions">Read more →</a></div></article>
        <article class="mgb-home__card"><img src="https://images.squarespace-cdn.com/content/v1/5ffdf49e3d30d07ea498ac3b/1783978382982-8JKKBCKZJCZ6FBDMS1F4/Screenshot+2026-07-13+at+2.32.02%E2%80%AFPM.png?format=300w" alt="Illustration for How Perfect is Perfect?" loading="lazy"><div class="mgb-home__card-copy"><h3>How Perfect is Perfect?</h3><a href="https://www.mygoodbrain.org/blog/how-perfect-is-perfect">Read more →</a></div></article>
        <article class="mgb-home__card"><img src="https://images.squarespace-cdn.com/content/v1/5ffdf49e3d30d07ea498ac3b/1783572536018-K8QAK55P4U0EEPYR2CJY/header.png?format=300w" alt="From Burnt Out to Back on Track" loading="lazy"><div class="mgb-home__card-copy"><h3>From Burnt Out to Back on Track</h3><p>Riya shares her experience navigating burnout and getting back on track as a high school student, one small step at a time!</p><a href="https://www.mygoodbrain.org/blog/burnt-out-to-back-on-track">Read more →</a></div></article>
      </div>
    </div>
  </section>

  <section class="mgb-home__section mgb-home__donate">
    <div class="mgb-home__inner">
      <h2>Make a donation.</h2>
      <p>Change happens when people and communities work together. Donate generously to help us reach more children in California who need better resources for mental health.</p>
      <a class="mgb-home__button" href="https://www.mygoodbrain.org/donate">Donate</a>
    </div>
  </section>
</div>
