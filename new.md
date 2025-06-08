---
title: "News: on my mind"
permalink: /news/
author_profile: true
---

<style>
    /* 新闻列表容器 */
    .news-list {
        display: flex;
        flex-direction: column;
        gap: 2.5rem; /* 卡片之间的垂直间距 */
        max-width: 800px; /* 限制最大宽度，提升阅读体验 */
        margin: 2rem auto; /* 页面居中 */
    }
    /* 单个新闻卡片的样式 */
    .news-card {
        display: flex;
        gap: 1.5rem; /* 图片和文字之间的间距 */
        align-items: flex-start; /* 顶部对齐 */
        border-bottom: 1px solid #eee;
        padding-bottom: 2.5rem;
    }
    .news-list > .news-card:last-child {
        border-bottom: none; /* 最后一张卡片不需要下边框 */
    }
    /* 图片容器样式 */
    .news-image {
        flex: 0 0 120px; /* 固定图片容器宽度为120px */
    }
    .news-image img {
        width: 100%;
        height: auto;
        border-radius: 8px; /* 图片圆角 */
        display: block;
    }
    /* 文字内容容器样式 */
    .news-content {
        flex: 1; /* 占据剩余所有空间 */
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
        margin: 0;
        color: #333;
        line-height: 1.6;
    }

    /* 响应式设计：在小屏幕上（宽度小于600px） */
    @media (max-width: 600px) {
        .news-card {
            flex-direction: column; /* 将左右布局变为上下布局 */
        }
        .news-image {
            flex-basis: auto; /* 取消固定宽度 */
            width: 100%; /* 图片容器宽度变为100% */
            margin-bottom: 1rem;
        }
    }
</style>

<div class="news-list">

    <div class="news-card">
        <div class="news-image">
            <img src="{{ '/images/news/ica-2025-logo.png' | relative_url }}" alt="ICA 2025 会议 Logo">
        </div>
        <div class="news-content">
            <p class="date">June 07, 2025</p>
            <h3>Paper Accepted by ICA 2025</h3>
            <p>
                Excited to share that our paper, "Love the way you are: examine the attribute of human-AI intimate relationships," has been accepted for presentation at the 75th ICA Annual Conference in Denver, U.S. See you there!
            </p>
        </div>
    </div>
    <div class="news-card">
        <div class="news-content">
            <p class="date">May 20, 2025</p>
            <h3>New Role as Assistant Editor</h3>
            <p>
                Honored to start my new journey as an Assistant Editor for the journal <em>Big Data & Society</em> (SSCI, Q1). Looking forward to contributing to the academic community.
            </p>
        </div>
    </div>
    </div>
