---
layout: post
title: About Me
permalink: /about/
comments: false
---

## As a Conversation Starter

I have lived in California my whole life. It is where I have grown as a student,
runner, teammate, and community leader. My family is from Vietnam.

<style>
  .about-location-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 10px;
    max-width: 220px;
    margin: 1rem 0 1.5rem;
  }

  .about-location-card {
    text-align: center;
  }

  .about-location-card img {
    width: 100%;
    height: 100px;
    object-fit: contain;
  }

  .about-location-card p {
    margin: 5px 0;
  }

  .about-location-card .about-greeting {
    color: var(--text-muted, #888);
    font-size: 0.9rem;
  }

  .about-list li {
    margin-bottom: 0.8rem;
    line-height: 1.6;
  }

  .image-gallery {
    display: flex;
    flex-wrap: nowrap;
    overflow-x: auto;
    gap: 10px;
    padding-bottom: 10px;
  }

  .image-gallery img {
    flex: 0 0 auto;
    width: auto;
    height: 180px;
    max-width: none;
    object-fit: contain;
    border-radius: 5px;
  }
</style>

<div class="about-location-grid" id="about_location_grid">
  <!-- California is added here with JavaScript. -->
</div>

<script>
  (function () {
    const container = document.getElementById("about_location_grid");
    const imageSource = "https://upload.wikimedia.org/wikipedia/commons/";
    const locations = [
      {
        flag: "0/01/Flag_of_California.svg",
        greeting: "My home for life",
        description: "California"
      },
      {
        flag: "2/21/Flag_of_Vietnam.svg",
        greeting: "My family is from Vietnam",
        description: "Vietnam"
      }
    ];

    for (const location of locations) {
      const card = document.createElement("div");
      card.className = "about-location-card";

      const flag = document.createElement("img");
      flag.src = imageSource + location.flag;
      flag.alt = "Flag of " + location.description;

      const description = document.createElement("p");
      description.textContent = location.description;

      const greeting = document.createElement("p");
      greeting.className = "about-greeting";
      greeting.textContent = location.greeting;

      card.appendChild(flag);
      card.appendChild(description);
      card.appendChild(greeting);
      container.appendChild(card);
    }
  })();
</script>

### Running and Athletics

Distance running has taught me that meaningful progress comes from consistency,
patience, and trust in a team. I began cross country with a 25:20 5K and worked
down to 17:03. That journey shaped how I compete, respond to setbacks, and
encourage younger runners who are still discovering what they can do.

### Clubs and Leadership

I am most energized by leadership that creates something real: a meeting people
look forward to, an event that serves a community, or a space where someone feels
comfortable sharing an interest.

<ul class="about-list">
  <li>
    🎧 <strong>Underground Rap Club — Co-founder and President.</strong>
    Built a school community of more than 20 music fans who share recommendations,
    discover emerging artists, and study the trends and culture behind the music.
    Leading the club has taught me how to turn an unusual idea into an organized,
    welcoming group.
  </li>
  <li>
    🏁 <strong>San Diego Milk Mile Association — Founder and Event Organizer.</strong>
    Created an annual community race that combines competition, fun, and charitable
    giving. I manage planning, registration, budgeting, promotion, volunteers, and
    race-day logistics to move the event from an idea to the starting line.
  </li>
  <li>
    ♟️ <strong>Chess Club and Instruction — Vice President and Volunteer Instructor.</strong>
    Support a school team that placed fifth at the San Diego County championship and
    teach younger players through library lessons and camps. Chess has helped me practice
    patient decision-making and explain complex ideas clearly.
  </li>
</ul>

### Photos

Scroll to the right for more.

<div class="image-gallery" aria-label="Photo gallery">
  <img src="{{site.baseurl}}/images/about/nathan/photo-01.jpg" alt="Nathan at school" loading="lazy">
  <img src="{{site.baseurl}}/images/about/nathan/photo-02.jpg" alt="Nathan in a casual setting" loading="lazy">
  <img src="{{site.baseurl}}/images/about/nathan/photo-03.jpg" alt="Nathan with friends" loading="lazy">
  <img src="{{site.baseurl}}/images/about/nathan/photo-04.jpg" alt="Nathan with a student group" loading="lazy">
  <img src="{{site.baseurl}}/images/about/nathan/photo-05.jpg" alt="Nathan at a club meeting" loading="lazy">
  <img src="{{site.baseurl}}/images/about/nathan/photo-06.jpg" alt="Nathan during a school activity" loading="lazy">
  <img src="{{site.baseurl}}/images/about/nathan/photo-07.jpg" alt="Nathan at a music event" loading="lazy">
  <img src="{{site.baseurl}}/images/about/nathan/photo-08.jpg" alt="Nathan at a classroom activity" loading="lazy">
  <img src="{{site.baseurl}}/images/about/nathan/photo-09.jpg" alt="Nathan with classmates" loading="lazy">
  <img src="{{site.baseurl}}/images/about/nathan/photo-10.jpg" alt="Nathan with club members" loading="lazy">
</div>
