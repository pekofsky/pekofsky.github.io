---
layout: page
title: Projects
permalink: /projects/
---

### My best projects and work from classes and personal endeavors


<h2><a href="/projects/436proj/">US Migration Flows Visualization Project</a></h2>

<div class="collapsible-paragraph">
  <p class="collapsible-text">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam eu turpis molestie, dictum est a, mattis tellus. Sed dignissim, metus nec fringilla accumsan, risus sem sollicitudin lacus, ut interdum tellus elit sed risus. Maecenas eget condimentum velit, sit amet feugiat lectus.
  </p>
  <button class="toggle-btn" onclick="toggleParagraph(this)">Show more</button>
</div>
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

This report explores US migration data from the years 2016 through 2020. All versions also include a link to a hosted shiny app.


<h2><a href="/projects/studyhabits/">Exploration of Simulated Student Habits Data</a></h2>

This project is a brief exploration of a realistic simulated dataset of student habits, and it includes one of my favorite visualizations I have made.


<h2><a href="/projects/2020tweets/">Sentiment Analysis and Topic Modeling of Tweets</a></h2>

This research paper uses sentiment analysis and topic modeling to investigate tweets surrounding the 2020 presidential election.


<h2><a href="/projects/240proj/">NYC Crime Analysis</a></h2>

This report provides visualizations and details statistical analysis done with New York City crime data.