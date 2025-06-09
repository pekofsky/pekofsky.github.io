---
layout: page
title: Projects
permalink: /projects/
---

---

My best projects and work from classes and personal endeavors

---

<!-- <h2><a href="/projects/436proj/">US Migration Flows Visualization Project</a></h2> -->
## US Migration Flows Visualization Project  
[View HTML](/assets/436proj.html){:target="_blank" rel="noopener noreferrer"} | [View PDF](/assets/436proj.pdf){:target="_blank" rel="noopener noreferrer"} | <a href="/assets/436proj.html" download>Download HTML</a> | <a href="/assets/436proj.pdf" download>Download PDF</a>

<div class="collapsible-paragraph">
  <p class="collapsible-text">
    This report explores <a href="https://www.census.gov/topics/population/migration/guidance/migration-flows.html">US migration data</a> from the years 2016 through 2020. All versions also include a link to a hosted shiny app.

    <u><b>My Contributions:</b></u>

    <u><b>Note:</b></u> This report looks much better in HTML.
  </p>
  <button class="toggle-btn" onclick="toggleParagraph(this)">Show more</button>
</div>

---

<!-- <h2><a href="/projects/studyhabits/">Exploration of Simulated Student Habits Data</a></h2> -->
## Exploration of Simulated Student Habits Data  
[View HTML](/assets/studyhabits.html){:target="_blank" rel="noopener noreferrer"} | [View PDF](/assets/studyhabits.pdf){:target="_blank" rel="noopener noreferrer"} | <a href="/assets/studyhabits.html" download>Download HTML</a> | <a href="/assets/studyhabits.pdf" download>Download PDF</a>

<div class="collapsible-paragraph">
  <p class="collapsible-text">
    This project is a brief exploration of a realistic simulated dataset of student habits, and it includes one of my favorite visualizations I have made.

    Note: This project looks much better in HTML.
  </p>
  <button class="toggle-btn" onclick="toggleParagraph(this)">Show more</button>
</div>

---

<!-- <h2><a href="/projects/2020tweets/">Sentiment Analysis and Topic Modeling of Tweets</a></h2> -->
## Sentiment Analysis and Topic Modeling of Tweets  
[View PDF](/assets/2020tweets.pdf){:target="_blank" rel="noopener noreferrer"} | <a href="/assets/2020tweets.pdf" download>Download PDF</a>

<div class="collapsible-paragraph">
  <p class="collapsible-text">
    This research paper uses sentiment analysis and topic modeling to investigate tweets surrounding the 2020 presidential election.
  </p>
  <button class="toggle-btn" onclick="toggleParagraph(this)">Show more</button>
</div>

---

## Deep Learning for Classifying Images of Egyptian Monuments
[View PDF](/assets/453proj.pdf){:target="_blank" rel="noopener noreferrer"} | <a href="/assets/453proj.pdf" download>Download PDF</a>

<div class="collapsible-paragraph">
  <p class="collapsible-text">
    This report details explorations in image recognition through deep learning.
  </p>
  <button class="toggle-btn" onclick="toggleParagraph(this)">Show more</button>
</div>

---

<!-- <h2><a href="/projects/240proj/">NYC Crime Analysis</a></h2> -->
## NYC Crime Analysis  
[View HTML](/assets/240proj.html){:target="_blank" rel="noopener noreferrer"} | [View PDF](/assets/240proj.pdf){:target="_blank" rel="noopener noreferrer"} | <a href="/assets/240proj.html" download>Download HTML</a> | <a href="/assets/240proj.pdf" download>Download PDF</a>

<div class="collapsible-paragraph">
  <p class="collapsible-text">
    This report provides visualizations and details statistical analysis done with New York City crime data.

    Note: This report looks much better in HTML.
  </p>
  <button class="toggle-btn" onclick="toggleParagraph(this)">Show more</button>
</div>

<!-- Only ONE script and style block at the end of the file -->
<script>
function toggleParagraph(btn) {
  const para = btn.previousElementSibling;
  para.classList.toggle('expanded');
  btn.textContent = para.classList.contains('expanded') ? 'Show less' : 'Show more';
}
</script>
<style>
.collapsible-text {
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  overflow: hidden;
  transition: max-height 0.3s;
  max-height: 3em; /* Adjust based on line height */
}
.collapsible-text.expanded {
  -webkit-line-clamp: unset;
  max-height: 100em;
}
.toggle-btn {
  background: none;
  border: none;
  color: #007acc;
  cursor: pointer;
  padding: 0;
  font: inherit;
  margin-top: 0.5em;
}
</style>