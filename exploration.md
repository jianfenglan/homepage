---
title: "Exploration"
permalink: /exploration/
author_profile: true
---

<style>
    .gallery-grid {
        display: grid;
        /* 1. 改为单列布局 */
        grid-template-columns: 1fr; 
        /* 适当增大了图片间的垂直间距 */
        gap: 2.5rem; 
        padding: 1rem 0;
        /* 为了在大屏幕上显示效果更好，设定一个最大宽度并居中 */
        max-width: 800px;
        margin: 0 auto;
    }
    .gallery-card {
        border: 1px solid #e0e0e0;
        border-radius: 12px;
        overflow: hidden;
        box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .gallery-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }
    .gallery-card img {
        width: 100%;
        /* 2. 移除了固定的 height: 220px; 让图片高度自适应 */
        object-fit: cover;
        display: block;
    }
    .gallery-caption {
        padding: 1rem;
        text-align: center;
        font-size: 0.9em;
        color: #555;
    }
    .gallery-caption h3 {
        margin: 0 0 0.5rem 0;
        font-size: 1.2em;
        color: #333;
    }
</style>

<div class="gallery-grid">
    <div class="gallery-card">
        <img src="{{ '/images/Wakayama.png' | relative_url }}">
        <div class="gallery-caption">
            <h3>Wakayama·Japan</h3>
            <p>11 March, 2025</p>
        </div>
    </div>

    <div class="gallery-card">
        <img src="{{ '/images/Osaka.png' | relative_url }}">
        <div class="gallery-caption">
            <h3>Osaka·Japan</h3>
            <p>10 March, 2025</p>
        </div>
    </div>

    <div class="gallery-card">
        <img src="{{ '/images/你的照片名3.jpg' | relative_url }}" alt="日本·京都清水寺">
        <div class="gallery-caption">
            <h3>日本 · 京都</h3>
            <p>秋日的清水寺，红枫如火。</p>
        </div>
    </div>

    <div class="gallery-card">
        <img src="{{ '/images/你的照片名4.jpg' | relative_url }}" alt="冰岛·极光">
        <div class="gallery-caption">
            <h3>冰岛 · 雷克雅未克</h3>
            <p>追逐欧若拉的夜晚，终生难忘。</p>
        </div>
    </div>
</div>
