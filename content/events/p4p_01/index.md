---
title: "P4P#1"
date: 2025-05-20
description: "the innaugral gathering"
---

<div class="card">
  <div class="hero" ></div>

  <div class="body">

  <h1>
    P4P
    <span>#1</span>
  </h1>

  _A cosy gathering of nerds who are active in art / tech / activism / systems in service of society._

  This is the first of a 6-month series. The format is still emerging but the invitation is to come and connect, share updates about projects, listen, offer support.

  <div class="details">

  **WHEN** - Tuesday 20th May, 5-8pm <br />
  **WHERE** - Southern Cross Garden Bar

  </div>

  <div class="art">

  Art: [Skyline Cascade](https://scryfall.com/card/bfz/246/skyline-cascade) by [Philip Straub](https://www.artstation.com/philipstraub52)
  </div>

  </div>
</div>

<style>
  .card {
    color: #333;

    h1 {
      color: #333; 
    }
  }
  .card {
    --radius: 10px;
    /* max-width: 800px; */
    background: white;
    box-shadow: 
      0 2.8px 2.2px rgba(0, 0, 0, 0.034),
      0 6.7px 5.3px rgba(0, 0, 0, 0.048),
      0 12.5px 10px rgba(0, 0, 0, 0.06),
      0 22.3px 17.9px rgba(0, 0, 0, 0.072),
      0 41.8px 33.4px rgba(0, 0, 0, 0.086),
      0 100px 80px rgba(0, 0, 0, 0.12);
    border-radius: var(--radius);

    display: grid;
    grid-template-rows: auto auto;

    .hero {
      height: 600px;
      background-image: url('./featured.jpg');
      background-size: cover;
      border-radius: var(--radius) var(--radius) 0 0;
    }

    .body {
      padding: 0 2rem 2rem 2rem;
      h1 {
        font-size: 3rem;
        padding-top: 2rem;
        padding-bottom: 0;
        border: none;
        margin-bottom: 0;
        span {
          font-size: 2rem;
          opacity: 0.9;
        }
      }

      .details {
        margin-top: 2rem;
        font-size: 1.4rem;

        strong {
          color: #111 !important;
        }
      }

      .art {
        font-size: 0.8rem;
        a {
          color: #111;
          text-decoration: underline;
        }
      }
    }
  }
</style>

<style>
  @media (max-width: 768px) {
    .card {
      margin-left: -2rem;
      margin-right: -2rem;
    }
  }
<style>
