---
title: "Analysis of Attention Mechanism and Its Recent Variance in Transformer"
collection: publications
category: ml_nlp
permalink: /publication/paper3
status: published
excerpt: 'Conducted a comparative study of attention variants (Linear, External, FLASH) in Transformers using PyTorch, highlighting runtime efficiency and optimization effects across datasets.'
date: 2023-10-19
venue: '4th International Conference on Signal Processing and Machine Learning'
paperurl: 'https://www.ewadirect.com/proceedings/ace/article/view/10938/pdf'
---

**Abstract:** Transformer is a machine learning model based on attention mechanism, which is widely used. When the Transformer model was first proposed, it gradually developed many variants and was promoted and applied in many fields, becoming an important research part in the areas of deep learning. However, the critical attention mechanism of Transformers has issues such as square complexity that affect computational speed and data processing efficiency. In order to meet the needs of data processing and related computing, there have been endless efforts to improve the attention mechanism in Transformers in different work areas. This article mainly provides a brief overview of the recent research progress on the attention mechanism in Transformers. Select representative studies from several directions of attention improvement work to introduce, in order to explore the latest research trends in its improvement work and lay a foundation for pointing out potential research directions for future research work and further improving the performance of Transformers.

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

<div class="thumb-grid">
  {% for i in (1..5) %}
  <div class="thumb">
    <img src="/images/publication/paper3/f{{ i }}.png" alt="Figure {{ i }}" loading="lazy">
  </div>
  {% endfor %}
</div>