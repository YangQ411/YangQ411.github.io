---
title: "Thermodynamics and Phase Transition in Central Charge Criticality of Charged Gauss-Bonnet AdS Black Holes"
collection: publications
category: physics
permalink: /publication/paper2
excerpt: 'Introduces central charge into Gauss-Bonnet AdS black hole thermodynamics and reveals new phase transition phenomena through holographic analysis.'
date: 2023-03-09
venue: 'Nuclear Physics B'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0550321323001633?ref=pdf_download&fr=RR-2&rr=986d13eb286f5e39'
---

**Abstract:** In this paper, we investigate the thermodynamics of D-dimensional charged Gauss-Bonnet black holes in anti-de Sitter spacetime. By considering the variations of the cosmological constant, the Newton's constant and the Gauss-Bonnet coupling constant in bulk, one can rewrite the first law of thermodynamics in a holographic form, where the contributions of thermodynamical variables in bulk and the boundary field theory are both included. Based on this approach, we study the phase transition in the central charge criticality when $D = 4$, 5, and 6. Besides, a triple point where the small/intermediate/large black holes can coexist is found in D = 6.

<!-- 画廊样式：响应式网格 + 卡片效果 -->
<style>
.thumb-grid{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 14px;
  justify-items: center;
  align-items: start;
  margin: 8px 0 24px;
}
.thumb{
  width: 100%;
  max-width: 220px;
  border: 1px solid #e4e4e4;
  border-radius: 8px;
  overflow: hidden;
  background: #fff;
  box-shadow: 0 0 0 rgba(0,0,0,0);
  transition: box-shadow .2s ease, transform .2s ease;
  text-decoration: none;
}
.thumb:hover{ box-shadow: 0 6px 16px rgba(0,0,0,.08); transform: translateY(-2px); }
.thumb img{
  width: 100%;
  height: 120px;          /* 统一缩略图高度；若想不裁剪可把 cover 改为 contain */
  object-fit: cover;
  display: block;
}
.thumb-caption{
  font-size: 0.85rem;
  color: #666;
  text-align: center;
  padding: 6px 8px 8px;
}
</style>

<!-- 画廊（把 1..12 改为你的张数；文件名按 f1.jpg…fN.jpg） -->
<div class="thumb-grid">
  {% for i in (1..10) %}
  <div class="thumb">
    <img src="/images/publication/paper2/f{{ i }}.jpg" alt="Figure {{ i }}" loading="lazy">
  </div>
  {% endfor %}
</div>