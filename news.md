---
title: "News: on my mind"
permalink: /news/
author_profile: true
---

<style>
    /* 新闻列表容器 */
    .news-list {
        display: grid;
        grid-template-columns: 1fr;
        gap: 2rem;
        max-width: 800px; /* 卡片最大宽度，可以根据喜好调整 */
        margin: 2rem auto;
    }

    /* 新闻卡片样式 */
    .news-card {
        display: flex;
        /* --- 改动 1: 改变主轴方向，变为“上图下文” --- */
        flex-direction: column; 
        gap: 1rem; /* 图片和文字之间的垂直间距 */
        
        /* 卡片化样式保持不变 */
        background: white;
        border: 1px solid #e9e9e9;
        border-radius: 16px;
        padding: 1.5rem;
        box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .news-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 20px rgba(0,0,0,0.12);
    }

    /* 图片容器样式 */
    .news-image {
        /* --- 改动 2: 让图片容器宽度变为100% --- */
        width: 100%; 
    }
    .news-image img {
        width: 100%;
        height: auto;
        border-radius: 8px;
        display: block;
    }

    /* 文字内容容器样式 */
    .news-content {
        /* flex: 1; 在这个布局下不再是必需的 */
    }
    .news-content .date {
        font-size: 0.85em;
        color: #888;
        margin-bottom: 0.5rem;
    }
    .news-content h3 {
        margin: 0 0 0.75rem 0;
        font-size: 1.3em;
        line-height: 1.3;
    }
    .news-content p {
        margin: 0 0 1em 0;
        color: #333;
        line-height: 1.7;
        text-align: justify;
    }
    .news-content p:last-of-type {
        margin-bottom: 0;
    }

    /* 响应式部分不再需要单独设置，因为桌面端已经采用了移动端的上下布局 */
</style>

<div class="news-list">

    <div class="news-card">
        <div class="news-image">
            <img src="{{ '/images/news/Apple.png' | relative_url }}" alt="Training seminar at Apple">
        </div>
        <div class="news-content">
            <p class="date">April 11, 2025 | Shanghai</p>
            <h3>Meet Apple Friends</h3>
            <p>
                It was a great honor to deliver this engaging professional training seminar alongside my colleague Jaagi and my friend Masha for the advertising team at Apple.
            </p>
            <p>
                We had a fruitful discussion on topics such as social identity, conflict management, and groupthink, and participated in a number of interactive activities that were both enjoyable and thought-provoking.
            </p>
            <p>
                Engaging with professionals outside of academia also offered fresh perspectives and inspiring new insights.
            </p>
        </div>
    </div>
    
    </div>
