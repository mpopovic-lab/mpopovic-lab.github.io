---
layout: single
title: Team
permalink: /team/
author_profile: false
classes: wide
---

<p class="team-intro">Our team works across MPI-PKS in Dresden and the Ruđer Bošković Institute in Zagreb. The coloured affiliation labels show where each member is based.</p>

<div class="team-roster">
  <article class="team-person">
    <img class="team-avatar team-photo" src="{{ '/assets/images/team/rocio-besana.jpg' | relative_url }}" alt="Profile image placeholder for Rocio Besana">
    <div class="team-person__body">
      <h2>Rocio Besana</h2>
      <p>PhD student</p>
      <div class="team-affiliations" aria-label="Affiliation">
        <span class="team-affiliation team-affiliation--mpi">MPI-PKS · Dresden</span>
      </div>
    </div>
  </article>

  <article class="team-person">
    <img class="team-avatar team-photo" src="{{ '/assets/images/team/kartik-chhajed.jpg' | relative_url }}" alt="Kartik Chhajed">
    <div class="team-person__body">
      <h2>Kartik Chhajed</h2>
      <p>PhD student</p>
      <div class="team-affiliations" aria-label="Affiliation">
        <span class="team-affiliation team-affiliation--mpi">MPI-PKS · Dresden</span>
      </div>
    </div>
  </article>

  <article class="team-person">
    <img class="team-avatar team-photo" src="{{ '/assets/images/team/pawel-korzeb.jpg' | relative_url }}" alt="Pawel Korzeb">
    <div class="team-person__body">
      <h2>Pawel Korzeb</h2>
      <p>PhD student</p>
      <div class="team-affiliations" aria-label="Affiliation">
        <span class="team-affiliation team-affiliation--mpi">MPI-PKS · Dresden</span>
      </div>
    </div>
  </article>

  <article class="team-person">
    <img class="team-avatar team-photo" src="{{ '/assets/images/photo_cbg.jpg' | relative_url }}" alt="Marko Popović">
    <div class="team-person__body">
      <h2>Marko Popović</h2>
      <p>Group leader</p>
      <div class="team-affiliations" aria-label="Affiliations">
        <span class="team-affiliation team-affiliation--mpi">MPI-PKS · Dresden</span>
        <span class="team-affiliation team-affiliation--irb">IRB · Zagreb</span>
      </div>
    </div>
  </article>

  <article class="team-person">
    <img class="team-avatar team-photo" src="{{ '/assets/images/team/vincenzo-schimmenti.jpg' | relative_url }}" alt="Vincenzo Schimmenti">
    <div class="team-person__body">
      <h2>Vincenzo Schimmenti</h2>
      <p>Postdoctoral researcher · Humboldt Fellow</p>
      <div class="team-affiliations" aria-label="Affiliation">
        <span class="team-affiliation team-affiliation--mpi">MPI-PKS · Dresden</span>
      </div>
    </div>
  </article>

  <article class="team-person">
    <img class="team-avatar team-photo" src="{{ '/assets/images/team/suganthan-senthilkumar.jpg' | relative_url }}" alt="Suganthan S">
    <div class="team-person__body">
      <h2>Suganthan S</h2>
      <p>PhD student</p>
      <div class="team-affiliations" aria-label="Affiliation">
        <span class="team-affiliation team-affiliation--mpi">MPI-PKS · Dresden</span>
      </div>
    </div>
  </article>

  <article class="team-person">
    <img class="team-avatar team-photo" src="{{ '/assets/images/team/ali-tahaei.jpg' | relative_url }}" alt="Ali Tahaei">
    <div class="team-person__body">
      <h2>Ali Tahaei</h2>
      <p>PhD student</p>
      <div class="team-affiliations" aria-label="Affiliation">
        <span class="team-affiliation team-affiliation--mpi">MPI-PKS · Dresden</span>
      </div>
    </div>
  </article>

  <article class="team-person">
    <img class="team-avatar team-photo" src="{{ '/assets/images/team/sifan-yin.jpg' | relative_url }}" alt="Sifan Yin">
    <div class="team-person__body">
      <h2>Sifan Yin</h2>
      <p>Marie Curie Fellow</p>
      <div class="team-affiliations" aria-label="Affiliation">
        <span class="team-affiliation team-affiliation--mpi">MPI-PKS · Dresden</span>
      </div>
    </div>
  </article>
</div>

<a class="team-page-link" href="https://www.pks.mpg.de/order-and-disorder-in-driven-systems/people">MPI-PKS group page <span aria-hidden="true">→</span></a>

<style>
.team-intro {
  max-width: 760px;
  margin: 0 0 2rem;
  color: #4f5b56;
  font-size: 1.02rem;
}
.team-roster {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: .8rem;
}
.team-person {
  display: flex;
  align-items: center;
  gap: 1rem;
  min-height: 96px;
  padding: 1rem 1.05rem;
  border: 1px solid #dfe5e2;
  border-radius: 8px;
  background: #fff;
}
.team-person__body {
  min-width: 0;
}
.team-person h2 {
  margin: 0;
  font-size: 1rem;
  line-height: 1.25;
}
.team-person__body > p {
  margin: .18rem 0 .5rem;
  color: #68736d;
  font-size: .8rem;
  line-height: 1.35;
}
.team-avatar {
  display: block;
  flex: 0 0 58px;
  width: 58px;
  height: 58px;
  border-radius: 50%;
}
.team-photo {
  object-fit: cover;
  object-position: 50% 32%;
  border: 1px solid #d8dfdb;
  filter: grayscale(100%);
}
.team-affiliations {
  display: flex;
  flex-wrap: wrap;
  gap: .35rem .75rem;
}
.team-affiliation {
  --affiliation-color: #68736d;
  display: inline-flex;
  align-items: center;
  color: #5f6a65;
  font-size: .72rem;
  font-weight: 600;
  line-height: 1.3;
}
.team-affiliation::before {
  content: "";
  width: .48rem;
  height: .48rem;
  margin-right: .35rem;
  border-radius: 50%;
  background: var(--affiliation-color);
}
.team-affiliation--mpi { --affiliation-color: #9a6a19; }
.team-affiliation--irb { --affiliation-color: #196b63; }
.team-page-link {
  display: inline-flex;
  gap: .35rem;
  align-items: center;
  margin-top: 1.35rem;
  color: #1f5a43;
  font-size: .82rem;
  font-weight: 700;
  text-decoration: none;
}
.team-page-link:hover { text-decoration: underline; }
@media (max-width: 760px) {
  .team-roster { grid-template-columns: 1fr; }
}
</style>
