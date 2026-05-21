---
title: "Dissertation Defense"
date: 2026-05-20
summary: "03 June 2026 @ 10:00am PST (Location TBD)"
tags:
  - Human-AI Collaboration
  - AI-Assisted Decision-Making
  - Dissertation
  - Defense
  - Ph.D. Candidate
links:
  - type: github
    url: https://forms.gle/3rkREyqCNNc52oDa9
    label: Sign-Up for Notifications
authors:
  - me
featured: true
sharing: false
---

## Defense Information

{{< button url="https://forms.gle/3rkREyqCNNc52oDa9" align="center" style="outline" icon="academic-cap-solid" new_tab="true" >}}Click to Sign-Up for Notifications{{< /button >}}

<b>Date</b>: 03 June 2026 @ 10am PST
<br />
<b>Location</b>: TBD

## Countdown

<div id="countdown-container">
  <div id="countdown">
    <div><span id="days">00</span><small>Days</small></div>
    <div><span id="hours">00</span><small>Hours</small></div>
    <div><span id="minutes">00</span><small>Minutes</small></div>
    <div><span id="seconds">00</span><small>Seconds</small></div>
  </div>
</div>

<style>
  #countdown-container {
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: Arial, sans-serif;
    margin: 20px 0;
  }

  #countdown {
    display: flex;
    gap: 20px;
  }

  #countdown div {
    text-align: center;
  }

  #countdown span {
    display: block;
    font-size: 5rem;
    font-weight: bold;
    color: #fff;
  }

  #countdown small {
    font-size: 1rem;
    color: #777;
  }
</style>

<script>
  // 🔧 CHANGE THIS DATE/TIME (YYYY-MM-DDTHH:MM:SS)
  const targetDate = new Date("2026-06-03T10:00:00-07:00");

  function updateCountdown() {
    const now = new Date();
    const diff = targetDate - now;

    if (diff <= 0) {
      document.getElementById("countdown").innerHTML = "⏰ Time's up!";
      return;
    }

    const days = Math.floor(diff / (1000 * 60 * 60 * 24));
    const hours = Math.floor((diff / (1000 * 60 * 60)) % 24);
    const minutes = Math.floor((diff / (1000 * 60)) % 60);
    const seconds = Math.floor((diff / 1000) % 60);

    document.getElementById("days").textContent = String(days).padStart(2, "0");
    document.getElementById("hours").textContent = String(hours).padStart(2, "0");
    document.getElementById("minutes").textContent = String(minutes).padStart(2, "0");
    document.getElementById("seconds").textContent = String(seconds).padStart(2, "0");
  }

  updateCountdown();
  setInterval(updateCountdown, 1000);
</script>
