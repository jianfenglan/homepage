---
title: "News: on my mind"
permalink: /news/
author_profile: true
---

<style>
    /* 新闻列表容器 */
    .news-list {
        display: grid; /* 使用grid布局更灵活 */
        grid-template-columns: 1fr; /* 始终保持单列 */
        gap: 2rem; /* 卡片之间的垂直间距 */
        max-width: 800px;
        margin: 2rem auto;
    }

    /* 【卡片化修改】
      这是主要修改部分，我们借鉴了 Exploration 页面的卡片样式 
    */
    .news-card {
        display: flex;
        gap: 1.5rem;
        align-items: center; /* 垂直居中对齐图片和文字，效果更好 */
        
        /* --- 卡片化样式 --- */
        background: white; /* 为卡片设置白色背景 */
        border: 1px solid #e9e9e9;
        border-radius: 16px; /* 更圆润的边角 */
        padding: 1.5rem; /* 在卡片内部增加留白 */
        box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .news-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 20px rgba(0,0,0,0.12);
    }

    /* 图片容器样式 */
    .news-image {
        flex: 0 0 180px; /* 图片宽度，你可以根据喜好调整 */
        width: 180px;
    }
    .news-image img {
        width: 100%;
        height: auto;
        border-radius: 8px;
        display: block;
    }

    /* 文字内容容器样式 */
    .news-content {
        flex: 1;
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

    /* 【两端对齐修改】 
    */
    .news-content p {
        margin: 0 0 1em 0; /* 为段落之间增加下间距 */
        color: #333;
        line-height: 1.7; /* 为两端对齐文本增加行高，提升可读性 */
        text-align: justify; /* --- 实现两端对齐 --- */
    }
    .news-content p:last-of-type {
        margin-bottom: 0; /* 移除最后一个段落的下间距 */
    }

    /* 响应式设计 */
    @media (max-width: 600px) {
        .news-card {
            flex-direction: column; /* 上下图文布局 */
            padding: 1rem;
        }
        .news-image {
            width: 100%;
            margin-bottom: 1rem;
        }
    }
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
