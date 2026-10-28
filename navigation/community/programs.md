---
layout: post
title: My Good Brain - Community Programs Hub
permalink: /community/programs/
---

<div class="mgb-programs-container">
  
  <div class="mgb-hero-header">
    <h1>Community Programs Hub</h1>
    <p>Explore our active wellness initiatives, workshops, and youth support networks in San Diego.</p>
  </div>

  <div class="mgb-controls">
    <input type="text" id="mgbSearchInput" class="mgb-search-bar" placeholder="🔍 Search programs..." onkeyup="filterPrograms()" />
    
    <div class="mgb-filter-tags">
      <button class="mgb-filter-btn active" onclick="filterCategory('all', this)">All Programs</button>
      <button class="mgb-filter-btn" onclick="filterCategory('Youth', this)">Youth & Kids</button>
      <button class="mgb-filter-btn" onclick="filterCategory('Family', this)">Family Outreach</button>
      <button class="mgb-filter-btn" onclick="filterCategory('Workshops', this)">Workshops & Kits</button>
      <button class="mgb-filter-btn" onclick="filterCategory('Media', this)">Media & Arts</button>
    </div>
  </div>

  <div class="mgb-cards-grid" id="mgbGrid">
    
    <div class="mgb-card" data-category="Family" data-title="San Diego Military Families">
      <div>
        <span class="mgb-card-category">Family Outreach</span>
        <h3 class="mgb-card-title">San Diego Military Families</h3>
        <p class="mgb-card-desc">Specialized arts-based wellness sessions designed to support military youth and families.</p>
      </div>
      <a href="https://www.mygoodbrain.org/military-families" target="_blank" class="ocs-btn ocs-btn--primary">Visit Program &rarr;</a>
    </div>

    <div class="mgb-card" data-category="Family" data-title="Homeschool & Charter Families">
      <div>
        <span class="mgb-card-category">Family Outreach</span>
        <h3 class="mgb-card-title">Homeschool & Charter Families</h3>
        <p class="mgb-card-desc">Flexible art therapy and expressive learning curriculums for homeschool networks.</p>
      </div>
      <a href="https://www.mygoodbrain.org/enrichment" target="_blank" class="ocs-btn ocs-btn--primary">Visit Program &rarr;</a>
    </div>

    <div class="mgb-card" data-category="Workshops" data-title="MGB Tool Kit">
      <div>
        <span class="mgb-card-category">Workshops & Kits</span>
        <h3 class="mgb-card-title">MGB Tool Kit</h3>
        <p class="mgb-card-desc">Hands-on creative toolkits filled with mindfulness activities and art supplies.</p>
      </div>
      <a href="https://www.mygoodbrain.org/mgbtoolkit" target="_blank" class="ocs-btn ocs-btn--primary">Request Kit &rarr;</a>
    </div>

    <div class="mgb-card" data-category="Workshops" data-title="Art x Mental Wellness Workshops">
      <div>
        <span class="mgb-card-category">Workshops & Kits</span>
        <h3 class="mgb-card-title">Art x Mental Wellness Workshops</h3>
        <p class="mgb-card-desc">Guided interactive sessions connecting artistic expression with emotional learning.</p>
      </div>
      <a href="https://www.mygoodbrain.org/library-workshops" target="_blank" class="ocs-btn ocs-btn--primary">View Schedule &rarr;</a>
    </div>

    <div class="mgb-card" data-category="Youth" data-title="Kids at Heart">
      <div>
        <span class="mgb-card-category">Youth & Kids</span>
        <h3 class="mgb-card-title">Kids at Heart</h3>
        <p class="mgb-card-desc">Community gatherings fostering peer connection and emotional resilience through play.</p>
      </div>
      <a href="https://www.mygoodbrain.org/kidsatheart" target="_blank" class="ocs-btn ocs-btn--primary">Explore Program &rarr;</a>
    </div>

    <div class="mgb-card" data-category="Youth" data-title="Little Sound Minds">
      <div>
        <span class="mgb-card-category">Youth & Kids</span>
        <h3 class="mgb-card-title">Little Sound Minds</h3>
        <p class="mgb-card-desc">Early childhood mindfulness initiatives introducing music, movement, and art.</p>
      </div>
      <a href="https://www.mygoodbrain.org/little-sound-minds" target="_blank" class="ocs-btn ocs-btn--primary">Explore Program &rarr;</a>
    </div>

    <div class="mgb-card" data-category="Youth" data-title="Little Mess Club">
      <div>
        <span class="mgb-card-category">Youth & Kids</span>
        <h3 class="mgb-card-title">Little Mess Club</h3>
        <p class="mgb-card-desc">Sensory art play sessions encouraging children to explore emotions freely.</p>
      </div>
      <a href="https://www.mygoodbrain.org/little-mess-club" target="_blank" class="ocs-btn ocs-btn--primary">Explore Program &rarr;</a>
    </div>

    <div class="mgb-card" data-category="Media" data-title="Podcast">
      <div>
        <span class="mgb-card-category">Media & Arts</span>
        <h3 class="mgb-card-title">My Good Brain Podcast</h3>
        <p class="mgb-card-desc">Discussions and interviews highlighting youth mental health and art stories.</p>
      </div>
      <a href="https://www.mygoodbrain.org/podcast" target="_blank" class="ocs-btn ocs-btn--primary">Listen Now 🎧</a>
    </div>

    <div class="mgb-card" data-category="Media" data-title="Sunday Art Club">
      <div>
        <span class="mgb-card-category">Media & Arts</span>
        <h3 class="mgb-card-title">Sunday Art Club</h3>
        <p class="mgb-card-desc">Weekly drop-in art clubs where kids and teens collaborate in a safe space.</p>
      </div>
      <a href="https://www.mygoodbrain.org/sunday-art-club" target="_blank" class="ocs-btn ocs-btn--primary">Join Session &rarr;</a>
    </div>

    <div class="mgb-card" data-category="Media" data-title="Teen Creative Arts">
      <div>
        <span class="mgb-card-category">Media & Arts</span>
        <h3 class="mgb-card-title">Teen Creative Arts</h3>
        <p class="mgb-card-desc">A dedicated space for adolescents to express self-identity and relieve stress.</p>
      </div>
      <a href="https://www.mygoodbrain.org/teen-creative-arts" target="_blank" class="ocs-btn ocs-btn--primary">Explore Program &rarr;</a>
    </div>

  </div>
</div>

<script>
let currentCategory = 'all';

function filterPrograms() {
  const query = document.getElementById('mgbSearchInput').value.toLowerCase();
  const cards = document.querySelectorAll('.mgb-card');

  cards.forEach(card => {
    const title = card.getAttribute('data-title').toLowerCase();
    const category = card.getAttribute('data-category');
    const matchesSearch = title.includes(query);
    const matchesCategory = (currentCategory === 'all' || category === currentCategory);

    card.style.display = (matchesSearch && matchesCategory) ? 'flex' : 'none';
  });
}

function filterCategory(category, btnElement) {
  currentCategory = category;
  document.querySelectorAll('.mgb-filter-btn').forEach(btn => btn.classList.remove('active'));
  btnElement.classList.add('active');
  filterPrograms();
}
</script>