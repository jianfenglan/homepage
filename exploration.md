---
title: "Exploration"
permalink: /exploration/
author_profile: true
---

<style>
    .gallery-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        gap: 1.5rem; /* 网格间距 */
        padding: 1rem 0;
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
        height: 220px;
        object-fit: cover; /* 保证图片不变形 */
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
        <img src="{{ '/images/Wakayama.png' | relative_url }}" alt="和歌山">
        <div class="gallery-caption">
            <h3>Wakayama</h3>
            <p>11 March, 2025</p>
        </div>
    </div>

    <div class="gallery-card">
        <img src="/assets/images/explorations/你的照片名2.jpg" alt="法国·巴黎铁塔">
        <div class="gallery-caption">
            <h3>法国 · 巴黎</h3>
            <p>塞纳河畔的日落，与铁塔的浪漫邂逅。</p>
        </div>
    </div>

    <div class="gallery-card">
        <img src="/assets/images/explorations/你的照片名3.jpg" alt="日本·京都清水寺">
        <div class="gallery-caption">
            <h3>日本 · 京都</h3>
            <p>秋日的清水寺，红枫如火。</p>
        </div>
    </div>

    <div class="gallery-card">
        <img src="/assets/images/explorations/你的照片名4.jpg" alt="冰岛·极光">
        <div class="gallery-caption">
            <h3>冰岛 · 雷克雅未克</h3>
            <p>追逐欧若拉的夜晚，终生难忘。</p>
        </div>
    </div>
</div>
