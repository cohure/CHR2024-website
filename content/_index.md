---
title: "CHR 2024"
date: 2019-12-15T11:12:14+01:00
---
<style>
  /* Card row layout */
  .card-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem; /* Small consistent gap */
    justify-content: flex-start; /* Align cards to the left */
    align-items: stretch; /* Make sure all cards are the same height */
  }

  .card-col {
    display: flex;
    flex-grow:1;
    margin-bottom: 1rem; /* vertical margin between cards */
    max-width: 400px;
    width: 100%;
  }

  .card {
    display: flex;
    flex-direction: column;
    flex-grow: 1;
    
    border: 2px solid #ccc;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease; /* Adding a smooth hover effect */
  }

  .card.image img{
    width: 80% !important;

  }

  .card:hover {
    transform: translateY(-5px); /* hiver lift effect */
  }

  .card-title {
    font-size: 20px !important; /* make size a bit bigger (override) */
    padding: 4px;
  }

  /* hide read more by default (on bigger screens) */
  .read-more {
  display: none;
  }

  /* show mobile read more since hover does not work */
  @media (hover: none) {
    .read-more {
      display: inline-block;
      margin-top: auto;
      align-self: flex-start;
      padding: 0.5rem 1rem;
      border: 1px solid;
      border-radius: 24px;
      text-decoration: none;
    }
  }
</style>

<h2 class="center"><b><span style="text-align:center";>Fifth Conference on</br> Computational Humanities Research</span></b></h2>

<h3 class="center">
    <b><span style="text-align:center; font-size:1.3em;"> <!-- make a little bigger than H3 -->
    December 4-6, 2024
    </span></b>
    </h3>

<h3 class="center">
    <b><span style="text-align:center;">
        <a href="https://events.au.dk/chr2024/">REGISTRATION</a> IS NOW OPEN
    </span></b>
</h3>
</br>

The Computational Humanities Research (CHR) community is an international and
interdisciplinary community that supports researchers with an interest in computational
approaches to the humanities. 

The 2024 edition of the Computational Humanities Research conference will take
place on **December 4-6, 2024** at Aarhus University, Denmark. Expect more
details about CHR2024 soon!


### Keynote Speakers 

We are very honoured and pleased that Lauren Klein and Leon Derczynski have agreed to give keynote lectures at CHR2024.
<div class="card-row">
  <div class="card-col">
    <div class="card">
      <div class="card-image">
        <a href="/announcements/lauren-klein">
          <img class="speaker-img" src="/images/announce/lauren-klein.jpg" alt="Card Image">
        </a>
      </div>
      <div class="card-content">
        <span class="card-title">Lauren Klein</span>
        <a href="/announcements/lauren-klein" class="read-more">Read More</a>
      </div>
    </div>
  </div>

  <div class="card-col">
    <div class="card">
      <div class="card-image">
        <a href="/announcements/leon-derczynski">
          <img class="speaker-img" src="/images/announce/leon-derczynski-square-med-forweb.jpg" alt="Card Image">
        </a>
      </div>
      <div class="card-content">
        <span class="card-title">Leon Derczynski</span>
        <a href="/announcements/leon-derczynski" class="read-more">Read More</a>
      </div>
    </div>
  </div>
</div>
