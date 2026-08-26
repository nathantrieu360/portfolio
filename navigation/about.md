---
layout: post
title: About Me
permalink: /about/
comments: false
---

## As a Conversation Starter

I have lived in California my whole life. It is where I have grown as a student,
runner, teammate, and community leader.

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

  .about-highlight-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 10px;
    margin: 1rem 0;
  }

  .about-highlight {
    padding: 12px;
    border: 1px solid color-mix(in srgb, var(--text, #fff) 18%, transparent);
    border-radius: 6px;
    text-align: center;
  }

  .about-highlight strong {
    display: block;
    color: var(--blue, #4da3ff);
    font-size: 1.35rem;
  }

  .about-highlight span {
    color: var(--text-muted, #aaa);
    font-size: 0.85rem;
  }

  .about-note {
    padding: 0.75rem 1rem;
    margin: 1rem 0;
    border-left: 3px solid var(--orange, #ed8936);
    background: var(--bg-1, rgba(128, 128, 128, 0.08));
  }

  .about-list li {
    margin-bottom: 0.8rem;
    line-height: 1.6;
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

<div class="about-highlight-grid" aria-label="Athletic highlights">
  <div class="about-highlight">
    <strong>17:03</strong>
    <span>Cross-country 5K personal record</span>
  </div>
  <div class="about-highlight">
    <strong>4:49</strong>
    <span>1600-meter personal record</span>
  </div>
  <div class="about-highlight">
    <strong>2×</strong>
    <span>Most Improved award recipient</span>
  </div>
  <div class="about-highlight">
    <strong>Varsity</strong>
    <span>Cross country and track & field</span>
  </div>
</div>

<div class="about-note">
My favorite part of running is not a single time or finish. It is helping build
a team where experienced athletes pass down encouragement, practical advice,
and a sense of belonging to the next group of runners.
</div>

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

### How I Try to Lead

<ul class="about-list">
  <li><strong>Make people feel included.</strong> A strong team gives new members a reason to return and room to contribute.</li>
  <li><strong>Improve through consistency.</strong> Small actions repeated over time matter more than one impressive moment.</li>
  <li><strong>Turn ideas into action.</strong> Leadership means planning the details, adapting when needed, and following through.</li>
</ul>
