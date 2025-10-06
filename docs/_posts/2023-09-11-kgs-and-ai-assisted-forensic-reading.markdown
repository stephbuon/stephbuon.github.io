---
layout: post
title: 'Who is the "Working Class" Socialist James Bond? Exploring Propaganda through Knowledge Graphs and AI-Assisted "Forensic Reading" in Bulgarian Spy Fiction'
description: The Cold War between the "free world" and the Communist Bloc involved multiple fronts, including intense literary warfare. In the bloc, authors crafted characters that reflected traits and ideals promoted by those regimes. To deepen our understanding of these works and their ideological underpinnings, we employ an original method we call "AI-assisted forensic reading," using advanced natural language processing, knowledge graphs, and artificial intelligence. Our approach uncovers new knowledge in the target literature by illuminating how these authors construct meaning, disseminate propaganda, and mirror idealized traits or real-life events, likely under the influence or direction of intelligence agency leaders.
image:  '/images/whole-corpus-topic-models.jpg'
tags:   [Russia, Spy Novels, Government Data, Knowledge Graphs, Social Networks]
---

<h2 id="interactive-gallery">Interactive Gallery</h2>
<p>Click "Load Graph" to render a visualization.</p>

<!--
<input id="graphSearch" type="text" placeholder="Search graphs..." style="
  width: 100%; max-width: 400px; padding: .6rem .8rem; margin: 1rem 0;
  border: 1px solid #ccc; border-radius: 8px; font-size: 1rem;
">
-->

<style>
.graph-section { margin-bottom: 2.5rem; }
.graph-block {
  border: 1px solid #eee; border-radius: 12px; padding: 1rem; margin-bottom: 1rem;
  background: #fff; transition: box-shadow .2s ease;
}
.graph-block:hover { box-shadow: 0 4px 14px rgba(0,0,0,.08); }
.graph-header { display: flex; align-items: center; justify-content: space-between; gap: 1rem; }
.graph-title { font-size: 1.05rem; font-weight: 600; margin: 0; }
.load-btn { padding: .4rem .8rem; border: 0; background: #007acc; color: #fff; border-radius: 6px; cursor: pointer; font-size: .9rem; }
.load-btn:hover { background: #005fa3; }
.graph-holder {
  margin-top: .6rem; height: 680px; border: 1px solid #ddd; border-radius: 8px;
  background: #fafafa; display: flex; align-items: center; justify-content: center;
  color: #888; font-size: .9rem;
}
</style>

<!-- Momchilovo -->
<section class="graph-section">
  <h3><em>The Momchilovo Affair</em> Network Graphs</h3>
  {% for g in site.data.graphs %}{% if g.title contains "Momchilovo" %}
  <div class="graph-block" data-title="{{ g.title | downcase }}" data-src="{{ g.path | relative_url }}">
    <div class="graph-header">
      <div class="graph-title">{{ g.title }}</div>
      <button class="load-btn" type="button">Load Graph</button>
    </div>
    <div class="graph-holder">Graph not loaded</div>
  </div>
  {% endif %}{% endfor %}
</section>

<!-- Nobody -->
<section class="graph-section">
  <h3><em>Mr. Nobody</em> Network Graphs</h3>
  {% for g in site.data.graphs %}{% if g.title contains "Nobody" %}
  <div class="graph-block" data-title="{{ g.title | downcase }}" data-src="{{ g.path | relative_url }}">
    <div class="graph-header">
      <div class="graph-title">{{ g.title }}</div>
      <button class="load-btn" type="button">Load Graph</button>
    </div>
    <div class="graph-holder">Graph not loaded</div>
  </div>
  {% endif %}{% endfor %}
</section>

<!-- Topic Models -->
<section class="graph-section">
  <h3>Topic Models</h3>
  {% for g in site.data.graphs %}{% if g.title contains "Topic" %}
  <div class="graph-block" data-title="{{ g.title | downcase }}" data-src="{{ g.path | relative_url }}">
    <div class="graph-header">
      <div class="graph-title">{{ g.title }}</div>
      <button class="load-btn" type="button">Load Graph</button>
    </div>
    <div class="graph-holder">Graph not loaded</div>
  </div>
  {% endif %}{% endfor %}
</section>

<script>
// search (optional)
const searchInput = document.getElementById('graphSearch');
if (searchInput) {
  searchInput.addEventListener('input', () => {
    const q = searchInput.value.trim().toLowerCase();
    document.querySelectorAll('.graph-block').forEach(b => {
      const t = b.getAttribute('data-title') || '';
      b.style.display = t.includes(q) ? '' : 'none';
    });
  });
}
// click-to-load iframes
document.addEventListener('click', (e) => {
  if (!e.target.matches('.load-btn')) return;
  const block = e.target.closest('.graph-block');
  const holder = block.querySelector('.graph-holder');
  const src = block.getAttribute('data-src');
  if (!src || holder.querySelector('iframe')) return;

  const iframe = document.createElement('iframe');
  iframe.src = src;
  iframe.loading = 'lazy';
  iframe.style.width = '100%';
  iframe.style.height = '100%';
  iframe.style.border = '0';

  holder.innerHTML = '';
  holder.appendChild(iframe);
  e.target.textContent = 'Loaded';
  e.target.disabled = true;
  e.target.style.background = '#aaa';
});
</script>
