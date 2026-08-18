---
title: "Group Photos Through the Years"
permalink: /group-photos/
layout: single
author_profile: true
---

<p class="photo-archive-intro">
A look back at the Hamann Group over the years.
</p>

<style>
.photo-archive-intro {
  margin-bottom: 2rem;
}

.photo-archive-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 2rem;
  margin-top: 1.5rem;
}

.group-photo {
  margin: 0;
}

.group-photo img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 12px;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.10);
}

.group-photo figcaption {
  margin-top: 0.6rem;
  font-size: 1rem;
  font-weight: 600;
  text-align: center;
  color: var(--global-text-color, #333333);
}

@media screen and (max-width: 760px) {
  .photo-archive-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="photo-archive-grid">

  <figure class="group-photo">
    <img src="{{ '/images/hamann-group-2022.jpg' | relative_url }}"
         alt="Hamann Group, 2022">
    <figcaption>2022</figcaption>
  </figure>

  <figure class="group-photo">
    <img src="{{ '/images/hamann-group-2019.jpg' | relative_url }}"
         alt="Hamann Group, 2019">
    <figcaption>2019</figcaption>
  </figure>

  <figure class="group-photo">
    <img src="{{ '/images/hamann-group-2017.jpg' | relative_url }}"
         alt="Hamann Group, 2017">
    <figcaption>2017</figcaption>
  </figure>

  <figure class="group-photo">
    <img src="{{ '/images/hamann-group-2014.jpg' | relative_url }}"
         alt="Hamann Group, 2014">
    <figcaption>2014</figcaption>
  </figure>

  <figure class="group-photo">
    <img src="{{ '/images/hamann-group-2012.jpg' | relative_url }}"
         alt="Hamann Group, 2012">
    <figcaption>2012</figcaption>
  </figure>

  <figure class="group-photo">
    <img src="{{ '/images/hamann-group-2011.jpg' | relative_url }}"
         alt="Hamann Group, 2011">
    <figcaption>2011</figcaption>
  </figure>

</div>
