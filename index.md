---
layout: home
title: Home
---

<style>
  .intro {
    max-width: 34rem;
    color: #555;
  }

  .app-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(15rem, 1fr));
    gap: 1rem;
    margin: 2rem 0 1.5rem;
    padding: 0;
    list-style: none;
  }

  .app-card {
    border: 1px solid #e2e2e2;
    border-radius: 10px;
    padding: 1.1rem 1.25rem 1.25rem;
    background: #fbfbfb;
  }

  .app-card h2 {
    margin: 0 0 .6rem;
    font-size: 1.05rem;
    line-height: 1.3;
    letter-spacing: normal;
  }

  .app-card ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .app-card li + li {
    margin-top: .3rem;
  }

  .app-card a {
    font-size: .95rem;
  }

  .legacy {
    font-size: .9rem;
    color: #666;
    border-top: 1px solid #e2e2e2;
    padding-top: 1rem;
  }

  @media (prefers-color-scheme: dark) {
    .intro,
    .legacy {
      color: #b0b0b0;
    }

    .app-card {
      border-color: #333;
      background: #1c1c1c;
    }

    .legacy {
      border-top-color: #333;
    }
  }
</style>

<p class="intro">Legal documents and support pages for the apps I publish on the App Store and Google Play. Pick an app to find its privacy policy, terms, or how to get in touch.</p>

<ul class="app-grid">
  <li class="app-card">
    <h2>Fortune Cookie</h2>
    <ul>
      <li><a href="/fortune-cookie/privacy-policy">Privacy Policy</a></li>
    </ul>
  </li>

  <li class="app-card">
    <h2>Measure Height</h2>
    <ul>
      <li><a href="/measure-height/privacy-policy">Privacy Policy</a></li>
    </ul>
  </li>

  <li class="app-card">
    <h2>Progress Tracker &amp; Goals</h2>
    <ul>
      <li><a href="/progress-tracker/privacy-policy">Privacy Policy</a></li>
      <li><a href="/progress-tracker/terms-and-conditions">Terms and Conditions</a></li>
    </ul>
  </li>

  <li class="app-card">
    <h2>Quick Math Solver</h2>
    <ul>
      <li><a href="/quick-math-solver/privacy-policy">Privacy Policy</a></li>
      <li><a href="/quick-math-solver/terms-and-conditions">Terms and Conditions</a></li>
    </ul>
  </li>

  <li class="app-card">
    <h2>QuickGeo</h2>
    <ul>
      <li><a href="/quick-geo/privacy-policy">Privacy Policy</a></li>
      <li><a href="/quick-geo/support">Support</a></li>
    </ul>
  </li>

  <li class="app-card">
    <h2>Reflexo</h2>
    <ul>
      <li><a href="/reflexo/privacy-policy">Privacy Policy</a></li>
    </ul>
  </li>
</ul>

<p class="legacy">Quick Math Solver was released as <strong>Speed Math</strong>. Its earlier <a href="/speed-math/terms-and-conditions">Terms and Conditions</a> stay published so links from that period keep working.</p>
