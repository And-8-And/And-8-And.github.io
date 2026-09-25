---
layout: archive
title: "Portfólió"
permalink: /portfolio/
author_profile: true
---

<p>Ebben a galériában az egyetemi életem legfontosabb pillanatait mutatom be.</p>

<style>
  .portfolio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    margin-top: 25px;
  }
  .portfolio-card {
    background-color: #2c3e50;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    display: flex;
    flex-direction: column;
  }
  .portfolio-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    display: block;
  }
  .portfolio-card .caption {
    padding: 15px;
    font-size: 0.95rem;
    color: #ecf0f1;
    line-height: 1.4;
  }
</style>

<div class="portfolio-grid">
  <div class="portfolio-card">
    <img src="/images/umfst1.jpg" alt="Egyetemi főépület az őszi fák lombjai között">
    <div class="caption">
      Egy napsütéses őszi délután az egyetem főépülete előtt, két előadás között.
    </div>
  </div>

  <div class="portfolio-card">
    <img src="/images/umfst2.jpg" alt="Laboratóriumi munka hallgatókkal">
    <div class="caption">
      Közös munka a Webfejlesztés laboron, egy komplex projekt megoldása közben.
    </div>
  </div>

  <div class="portfolio-card">
    <img src="/images/umfst3.jpg" alt="Hallgatók megbeszélést tartanak az egyetemi aulában">
    <div class="caption">
      A félévzáró szakmai nap, ahol rengeteg új ötletet cseréltünk a szaktársakkal.
    </div>
  </div>
</div>