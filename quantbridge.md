---
title: QuantBridge
layout: page
---

# QuantBridge

**QuantBridge** is an applied quantitative webinar series co-founded by [Kingsford Onyina](https://kingsfordonyina.github.io){:target="_blank" rel="noopener"} (UNC Charlotte), [Vanessa Owusu Ansah](https://www.linkedin.com/in/nessa-owusu-ansah){:target="_blank" rel="noopener"} (Lancaster University), and **Danny Turkson** (UNC Chapel Hill).

The series supports early-career researchers working with quasi-experimental methods, with sessions particularly relevant for scholars in economics, public policy, sociology, social work, political science, and related disciplines. Each topic is covered in two sessions: a theory session and a live software application session.

---

### Program Schedule --- 2026

<div class="qb-special">
<strong>Call for Papers &mdash; Fall 2026</strong><br>
Applied Quantitative Webinar Series &mdash; Submission Deadline: August 1, 2026, 11:59 PM EST.
<a href="/assets/call_for_papers.pdf" target="_blank" rel="noopener" class="btn-pdf">Submission Instructions (PDF)</a>
</div>

<div class="qb-phase">
<h4 style="font-size:1.05rem;border-bottom:1px solid #e8e8e8;padding-bottom:.35rem;margin-bottom:.9rem">Phase I &mdash; February &ndash; April 2026</h4>

<div class="qb-session">
<h4>Session 1 &mdash; Canonical Difference-in-Differences (DiD)</h4>
<p><strong>Theory:</strong> Saturday, February 7 &nbsp;|&nbsp; <strong>Application:</strong> Saturday, February 21 &nbsp;|&nbsp; 1:00&ndash;2:00 PM (ET)</p>
<p><strong>Facilitator:</strong> Olanrewaju Yusuff (Georgia State University)</p>
</div>

<div class="qb-session">
<h4>Session 2 &mdash; Staggered Difference-in-Differences (DiD)</h4>
<p><strong>Theory:</strong> Friday, March 6 &nbsp;|&nbsp; <strong>Application:</strong> Thursday, March 20</p>
<p><strong>Facilitator:</strong> Dr. Augustine Denteh (Davidson College)</p>
</div>

<div class="qb-session">
<h4>Session 3 &mdash; Continuous Difference-in-Differences (DiD)</h4>
<p><strong>Theory:</strong> Saturday, April 4 &nbsp;|&nbsp; <strong>Application:</strong> Friday, April 18</p>
<p><strong>Facilitator:</strong> TBD</p>
</div>
</div>

<div class="qb-phase">
<h4 style="font-size:1.05rem;border-bottom:1px solid #e8e8e8;padding-bottom:.35rem;margin-bottom:.9rem">Phase II &mdash; June &ndash; August 2026</h4>

<div class="qb-session">
<h4>Session 5 &mdash; Instrumental Variables (IV)</h4>
<p><strong>Theory &amp; Application:</strong> Friday, July 24 &nbsp;|&nbsp; 6:00 PM (ET)</p>
<p><strong>Facilitator:</strong> Dr. Isaac Koomson (The University of Queensland, Australia)</p>
</div>

<div class="qb-session">
<h4>Session 6 &mdash; Capacity Development: Publishing in High Impact Journals</h4>
<p><strong>Date:</strong> Friday, July 31 &nbsp;|&nbsp; 1:00 PM (ET)</p>
<p><strong>Facilitator:</strong> Dr. Jessica Leight (International Food Policy Research Institute (IFPRI))</p>
</div>

<div class="qb-session">
<h4>Session 4 &mdash; Regression Discontinuity Design (RDD)</h4>
<p><strong>Theory &amp; Application:</strong> Friday, August 7 &nbsp;|&nbsp; 12:00 PM (ET)</p>
<p><strong>Facilitator:</strong> Dr. Samuel Obeng (University of Warwick, UK)</p>
</div>
</div>

---

### Upcoming Sessions

<div class="qb-carousel" id="qbCarousel">
  <button class="qb-carousel-btn prev" onclick="qbSlide(-1)" aria-label="Previous">&#8249;</button>
  <div class="qb-carousel-track" id="qbTrack">
    <img src="/assets/img/qb_iv_july24.jpg"       alt="Instrumental Variables: Theory & Application — Friday, July 24, 6PM EST. Facilitator: Isaac Koomson, PhD, The University of Queensland, Australia.">
    <img src="/assets/img/qb_capacity_july31.jpeg" alt="Capacity Development — Friday, July 31, 1PM EST. Facilitator: Jessica Leight, PhD, International Food Policy Research Institute, USA.">
    <img src="/assets/img/qb_rdd_aug7.jpg"        alt="Regression Discontinuity: Theory & Application — Friday, August 7, 12PM EST. Facilitator: Samuel Obeng, PhD, University of Warwick, UK.">
  </div>
  <button class="qb-carousel-btn next" onclick="qbSlide(1)" aria-label="Next">&#8250;</button>
  <div class="qb-carousel-dots" id="qbDots">
    <button class="active" onclick="qbGoTo(0)" aria-label="Slide 1"></button>
    <button onclick="qbGoTo(1)" aria-label="Slide 2"></button>
    <button onclick="qbGoTo(2)" aria-label="Slide 3"></button>
  </div>
</div>

<script>
(function(){
  var current = 0;
  var total = 3;
  function update(){
    var track = document.getElementById('qbTrack');
    var dots  = document.getElementById('qbDots').querySelectorAll('button');
    track.style.display = 'flex';
    track.style.transform = 'translateX(-' + (current * 100) + '%)';
    track.style.transition = 'transform .4s ease';
    dots.forEach(function(d,i){ d.classList.toggle('active', i===current); });
  }
  window.qbSlide = function(dir){
    current = (current + dir + total) % total;
    update();
  };
  window.qbGoTo = function(i){
    current = i;
    update();
  };
  setInterval(function(){ window.qbSlide(1); }, 5000);
})();
</script>

---

### Session Recordings

<div class="video-grid">

  <div class="video-card">
    <div class="yt-thumb">
      <iframe src="https://www.youtube.com/embed/gd83ryRqXV4" title="Introduction to Difference-in-Differences (DiD) - February Edition" allowfullscreen loading="lazy"></iframe>
    </div>
    <div class="yt-info">
      <p>Introduction to Difference-in-Differences (DiD)</p>
      <span>February Edition &mdash; Session 1</span>
    </div>
  </div>

  <div class="video-card">
    <div class="yt-thumb">
      <iframe src="https://www.youtube.com/embed/iJVZGWZQj1c" title="Staggered Difference-in-Differences (DiD) - March Edition" allowfullscreen loading="lazy"></iframe>
    </div>
    <div class="yt-info">
      <p>Staggered Difference-in-Differences (DiD)</p>
      <span>March Edition &mdash; Session 2 (Theory)</span>
    </div>
  </div>

  <div class="video-card">
    <div class="yt-thumb">
      <iframe src="https://www.youtube.com/embed/LfCr4N0yBtw" title="Staggered DiD - Implementation in Stata/R" allowfullscreen loading="lazy"></iframe>
    </div>
    <div class="yt-info">
      <p>Staggered DiD &mdash; Implementation (Stata/R)</p>
      <span>March Edition &mdash; Session 2 (Application)</span>
    </div>
  </div>

</div>

---

### About QuantBridge

QuantBridge grew out of a shared commitment among its co-founders to making rigorous applied econometrics accessible to early-career scholars globally. The February 2026 edition attracted 150+ participants from over 17 countries, reflecting the breadth of interest in these methods across disciplines and regions.

For more information, to get involved, or to support this initiative, feel free to reach out at [dturkson@unc.edu](mailto:dturkson@unc.edu).
