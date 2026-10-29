---
layout: post
title: My Good Brain - Community Programs Hub
permalink: /community/programs/
---

<div class="ocs__container">
  
  <div class="ocs__card">
    <h1>Community Programs Hub</h1>
    <p class="ocs__description">Explore our active wellness initiatives, workshops, and youth support networks in San Diego.</p>
  </div>

  <div class="ocs__card">
    <label for="mgbSearchInput">Search programs</label>
    <input type="search" id="mgbSearchInput" class="mediumInput" placeholder="Search programs..." oninput="filterPrograms()" />
    
    <div class="ocs__links">
      <button type="button" class="ocs__btn pill accent fill" aria-pressed="true" onclick="filterCategory('all', this)">All Programs</button>
      <button type="button" class="ocs__btn pill" aria-pressed="false" onclick="filterCategory('Youth', this)">Youth &amp; Kids</button>
      <button type="button" class="ocs__btn pill" aria-pressed="false" onclick="filterCategory('Family', this)">Family Outreach</button>
      <button type="button" class="ocs__btn pill" aria-pressed="false" onclick="filterCategory('Workshops', this)">Workshops &amp; Kits</button>
      <button type="button" class="ocs__btn pill" aria-pressed="false" onclick="filterCategory('Media', this)">Media &amp; Arts</button>
    </div>
  </div>

  <div class="ocs__grid ocs__grid--card cols-3" id="mgbGrid">
    
    <div class="ocs__grid-cell" data-category="Family" data-title="San Diego Military Families">
      <div>
        <span class="ocs__badge">Family Outreach</span>
        <h3 class="ocs__hub-card-title">San Diego Military Families</h3>
        <p class="ocs__card-description">Specialized arts-based wellness sessions designed to support military youth and families.</p>
      </div>
      <a href="https://www.mygoodbrain.org/military-families" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">Visit Program &rarr;</a>
    </div>

    <div class="ocs__grid-cell" data-category="Family" data-title="Homeschool & Charter Families">
      <div>
        <span class="ocs__badge">Family Outreach</span>
        <h3 class="ocs__hub-card-title">Homeschool &amp; Charter Families</h3>
        <p class="ocs__card-description">Flexible art therapy and expressive learning curriculums for homeschool networks.</p>
      </div>
      <a href="https://www.mygoodbrain.org/enrichment" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">Visit Program &rarr;</a>
    </div>

    <div class="ocs__grid-cell" data-category="Workshops" data-title="MGB Tool Kit">
      <div>
        <span class="ocs__badge">Workshops &amp; Kits</span>
        <h3 class="ocs__hub-card-title">MGB Tool Kit</h3>
        <p class="ocs__card-description">Hands-on creative toolkits filled with mindfulness activities and art supplies.</p>
      </div>
      <a href="https://www.mygoodbrain.org/mgbtoolkit" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">Request Kit &rarr;</a>
    </div>

    <div class="ocs__grid-cell" data-category="Workshops" data-title="Art x Mental Wellness Workshops">
      <div>
        <span class="ocs__badge">Workshops &amp; Kits</span>
        <h3 class="ocs__hub-card-title">Art x Mental Wellness Workshops</h3>
        <p class="ocs__card-description">Guided interactive sessions connecting artistic expression with emotional learning.</p>
      </div>
      <a href="https://www.mygoodbrain.org/library-workshops" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">View Schedule &rarr;</a>
    </div>

    <div class="ocs__grid-cell" data-category="Youth" data-title="Kids at Heart">
      <div>
        <span class="ocs__badge">Youth &amp; Kids</span>
        <h3 class="ocs__hub-card-title">Kids at Heart</h3>
        <p class="ocs__card-description">Community gatherings fostering peer connection and emotional resilience through play.</p>
      </div>
      <a href="https://www.mygoodbrain.org/kidsatheart" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">Explore Program &rarr;</a>
    </div>

    <div class="ocs__grid-cell" data-category="Youth" data-title="Little Sound Minds">
      <div>
        <span class="ocs__badge">Youth &amp; Kids</span>
        <h3 class="ocs__hub-card-title">Little Sound Minds</h3>
        <p class="ocs__card-description">Early childhood mindfulness initiatives introducing music, movement, and art.</p>
      </div>
      <a href="https://www.mygoodbrain.org/little-sound-minds" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">Explore Program &rarr;</a>
    </div>

    <div class="ocs__grid-cell" data-category="Youth" data-title="Little Mess Club">
      <div>
        <span class="ocs__badge">Youth &amp; Kids</span>
        <h3 class="ocs__hub-card-title">Little Mess Club</h3>
        <p class="ocs__card-description">Sensory art play sessions encouraging children to explore emotions freely.</p>
      </div>
      <a href="https://www.mygoodbrain.org/little-mess-club" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">Explore Program &rarr;</a>
    </div>

    <div class="ocs__grid-cell" data-category="Media" data-title="Podcast">
      <div>
        <span class="ocs__badge">Media &amp; Arts</span>
        <h3 class="ocs__hub-card-title">My Good Brain Podcast</h3>
        <p class="ocs__card-description">Discussions and interviews highlighting youth mental health and art stories.</p>
      </div>
      <a href="https://www.mygoodbrain.org/podcast" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">Listen Now</a>
    </div>

    <div class="ocs__grid-cell" data-category="Media" data-title="Sunday Art Club">
      <div>
        <span class="ocs__badge">Media &amp; Arts</span>
        <h3 class="ocs__hub-card-title">Sunday Art Club</h3>
        <p class="ocs__card-description">Weekly drop-in art clubs where kids and teens collaborate in a safe space.</p>
      </div>
      <a href="https://www.mygoodbrain.org/sunday-art-club" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">Join Session &rarr;</a>
    </div>

    <div class="ocs__grid-cell" data-category="Media" data-title="Teen Creative Arts">
      <div>
        <span class="ocs__badge">Media &amp; Arts</span>
        <h3 class="ocs__hub-card-title">Teen Creative Arts</h3>
        <p class="ocs__card-description">A dedicated space for adolescents to express self-identity and relieve stress.</p>
      </div>
      <a href="https://www.mygoodbrain.org/teen-creative-arts" target="_blank" rel="noopener noreferrer" class="ocs__btn accent fill">Explore Program &rarr;</a>
    </div>

  </div>
</div>

<script>
let currentCategory = 'all';

function filterPrograms() {
  const query = document.getElementById('mgbSearchInput').value.toLowerCase();
  const cards = document.querySelectorAll('#mgbGrid [data-category]');

  cards.forEach(card => {
    const title = card.dataset.title.toLowerCase();
    const category = card.getAttribute('data-category');
    const matchesSearch = title.includes(query);
    const matchesCategory = (currentCategory === 'all' || category === currentCategory);

    card.hidden = !(matchesSearch && matchesCategory);
  });
}

function filterCategory(category, btnElement) {
  currentCategory = category;
  document.querySelectorAll('.ocs__links .ocs__btn').forEach(btn => {
    const selected = btn === btnElement;
    btn.classList.toggle('accent', selected);
    btn.classList.toggle('fill', selected);
    btn.setAttribute('aria-pressed', String(selected));
  });
  filterPrograms();
}
</script>