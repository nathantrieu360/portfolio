---
layout: post
title: About Me
permalink: /about/
comments: false
---

<style>
  .about-page {
    --about-accent: var(--blue, #38bdf8);
    --about-warm: var(--orange, #f97316);
    color: var(--text, #f8fafc);
  }

  .about-hero {
    position: relative;
    overflow: hidden;
    padding: clamp(2rem, 6vw, 4.5rem);
    margin-bottom: 2rem;
    border: 1px solid color-mix(in srgb, var(--about-accent) 35%, transparent);
    border-radius: 24px;
    background:
      radial-gradient(circle at 90% 10%, color-mix(in srgb, var(--about-accent) 28%, transparent), transparent 35%),
      linear-gradient(135deg, var(--bg-1, #111827), var(--bg-2, #1e293b));
  }

  .about-eyebrow {
    margin: 0 0 0.6rem;
    color: var(--about-accent);
    font-size: 0.82rem;
    font-weight: 800;
    letter-spacing: 0.14em;
    text-transform: uppercase;
  }

  .about-hero h1 {
    max-width: 760px;
    margin: 0;
    font-size: clamp(2.25rem, 7vw, 4.75rem);
    line-height: 0.98;
    letter-spacing: -0.045em;
  }

  .about-intro {
    max-width: 720px;
    margin: 1.35rem 0 0;
    color: var(--text-muted, #cbd5e1);
    font-size: clamp(1rem, 2vw, 1.18rem);
    line-height: 1.75;
  }

  .about-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.65rem;
    margin-top: 1.5rem;
  }

  .about-tag {
    padding: 0.45rem 0.8rem;
    border: 1px solid color-mix(in srgb, var(--about-accent) 45%, transparent);
    border-radius: 999px;
    background: color-mix(in srgb, var(--about-accent) 10%, transparent);
    font-size: 0.86rem;
    font-weight: 700;
  }

  .about-section {
    margin: 2.8rem 0;
  }

  .about-section-heading {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    margin-bottom: 1rem;
  }

  .about-section-heading span {
    color: var(--about-accent);
    font-size: 0.85rem;
    font-weight: 800;
    letter-spacing: 0.12em;
    text-transform: uppercase;
  }

  .about-section-heading::after {
    flex: 1;
    height: 1px;
    background: color-mix(in srgb, var(--text, #f8fafc) 18%, transparent);
    content: "";
  }

  .about-lead {
    max-width: 820px;
    font-size: 1.08rem;
    line-height: 1.75;
  }

  .about-stats,
  .about-leadership-grid,
  .about-values {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
    gap: 1rem;
  }

  .about-stat,
  .about-card,
  .about-value {
    border: 1px solid color-mix(in srgb, var(--text, #f8fafc) 14%, transparent);
    border-radius: 18px;
    background: var(--bg-1, #111827);
  }

  .about-stat {
    padding: 1.2rem;
  }

  .about-stat strong {
    display: block;
    color: var(--about-accent);
    font-size: 1.8rem;
    line-height: 1.1;
  }

  .about-stat span {
    display: block;
    margin-top: 0.4rem;
    color: var(--text-muted, #cbd5e1);
    font-size: 0.9rem;
  }

  .about-running-story {
    padding: 1.4rem 1.5rem;
    margin-top: 1rem;
    border-left: 4px solid var(--about-warm);
    border-radius: 0 14px 14px 0;
    background: color-mix(in srgb, var(--about-warm) 8%, var(--bg-1, #111827));
    line-height: 1.75;
  }

  .about-card {
    padding: 1.35rem;
    transition: transform 180ms ease, border-color 180ms ease;
  }

  .about-card:hover {
    transform: translateY(-4px);
    border-color: color-mix(in srgb, var(--about-accent) 55%, transparent);
  }

  .about-card-icon {
    display: inline-grid;
    width: 2.5rem;
    height: 2.5rem;
    place-items: center;
    border-radius: 12px;
    background: color-mix(in srgb, var(--about-accent) 13%, transparent);
    font-size: 1.2rem;
  }

  .about-card h3 {
    margin: 1rem 0 0.25rem;
    font-size: 1.1rem;
  }

  .about-role {
    margin: 0 0 0.8rem;
    color: var(--about-accent);
    font-size: 0.82rem;
    font-weight: 800;
    letter-spacing: 0.05em;
    text-transform: uppercase;
  }

  .about-card p:last-child {
    margin-bottom: 0;
    color: var(--text-muted, #cbd5e1);
    line-height: 1.65;
  }

  .about-values {
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  }

  .about-value {
    padding: 1.2rem;
  }

  .about-value strong {
    display: block;
    margin-bottom: 0.35rem;
    color: var(--about-warm);
  }

  .about-value p {
    margin: 0;
    color: var(--text-muted, #cbd5e1);
    line-height: 1.6;
  }

  @media (max-width: 600px) {
    .about-hero {
      border-radius: 18px;
    }

    .about-stats {
      grid-template-columns: repeat(2, 1fr);
    }
  }
</style>

<div class="about-page">
  <section class="about-hero">
    <p class="about-eyebrow">Student-athlete · Organizer · Community builder</p>
    <h1>Hi, I'm Nathan Trieu.</h1>
    <p class="about-intro">
      I turn the things I care about into opportunities for people to improve and belong.
      Whether I am training with teammates, introducing students to new music, teaching
      chess, or organizing a race, I enjoy bringing people together around a shared goal.
    </p>
    <div class="about-tags" aria-label="Areas of focus">
      <span class="about-tag">Cross Country</span>
      <span class="about-tag">Track & Field</span>
      <span class="about-tag">Student Leadership</span>
      <span class="about-tag">Community Events</span>
    </div>
  </section>

  <section class="about-section" aria-labelledby="running-heading">
    <div class="about-section-heading">
      <span id="running-heading">Running & Athletics</span>
    </div>
    <p class="about-lead">
      Distance running has taught me that meaningful progress is usually the result of
      consistency, patience, and trust in a team. I began cross country with a 25:20 5K
      and worked down to 17:03. That journey shaped how I compete, respond to setbacks,
      and encourage younger runners who are still discovering what they can do.
    </p>

    <div class="about-stats" aria-label="Athletic highlights">
      <div class="about-stat">
        <strong>17:03</strong>
        <span>Cross-country 5K personal record</span>
      </div>
      <div class="about-stat">
        <strong>4:49</strong>
        <span>1600-meter personal record</span>
      </div>
      <div class="about-stat">
        <strong>2×</strong>
        <span>Most Improved award recipient</span>
      </div>
      <div class="about-stat">
        <strong>Varsity</strong>
        <span>Cross country and track & field</span>
      </div>
    </div>

    <div class="about-running-story">
      My favorite part of running is not a single time or finish. It is the process of
      helping build a team where experienced athletes pass down encouragement, practical
      advice, and a sense of belonging to the next group of runners.
    </div>
  </section>

  <section class="about-section" aria-labelledby="leadership-heading">
    <div class="about-section-heading">
      <span id="leadership-heading">Clubs & Leadership</span>
    </div>
    <p class="about-lead">
      I am most energized by leadership that creates something real: a meeting people
      look forward to, an event that serves a community, or a space where someone feels
      comfortable sharing an interest.
    </p>

    <div class="about-leadership-grid">
      <article class="about-card">
        <span class="about-card-icon" aria-hidden="true">🎧</span>
        <h3>Underground Rap Club</h3>
        <p class="about-role">Co-founder & President</p>
        <p>
          Built a school community of more than 20 music fans who share recommendations,
          discover emerging artists, and study the trends and culture behind the music.
          Leading the club has taught me how to turn an unusual idea into an organized,
          welcoming group.
        </p>
      </article>

      <article class="about-card">
        <span class="about-card-icon" aria-hidden="true">🏁</span>
        <h3>San Diego Milk Mile Association</h3>
        <p class="about-role">Founder & Event Organizer</p>
        <p>
          Created an annual community race that combines competition, fun, and charitable
          giving. I manage planning, registration, budgeting, promotion, volunteers, and
          race-day logistics to move the event from an idea to the starting line.
        </p>
      </article>

      <article class="about-card">
        <span class="about-card-icon" aria-hidden="true">♟️</span>
        <h3>Chess Club & Instruction</h3>
        <p class="about-role">Vice President & Volunteer Instructor</p>
        <p>
          Support a school team that placed fifth at the San Diego County championship
          and teach younger players through library lessons and camps. Chess has helped
          me practice patient decision-making and explain complex ideas clearly.
        </p>
      </article>
    </div>
  </section>

  <section class="about-section" aria-labelledby="values-heading">
    <div class="about-section-heading">
      <span id="values-heading">How I Try to Lead</span>
    </div>
    <div class="about-values">
      <div class="about-value">
        <strong>Make people feel included.</strong>
        <p>A strong team gives new members a reason to return and room to contribute.</p>
      </div>
      <div class="about-value">
        <strong>Improve through consistency.</strong>
        <p>Small actions repeated over time matter more than one impressive moment.</p>
      </div>
      <div class="about-value">
        <strong>Turn ideas into action.</strong>
        <p>Leadership means planning the details, adapting when needed, and following through.</p>
      </div>
    </div>
  </section>
</div>
