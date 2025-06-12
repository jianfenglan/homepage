---
title: "News: on my mind"
permalink: /news/
author_profile: true
---
<style>
    /* 强制拓宽本页面的主内容区域 */
    .page__inner-wrap {
        max-width: 1600px !important;
    }
    /* 新闻列表容器 */
    .news-list {
        display: grid;
        grid-template-columns: 1fr;
        gap: 2rem;
        margin: 2rem 0; /* 调整外边距 */
    }
    /* 单个新闻卡片的样式 */
    .news-card {
        display: flex;
        flex-direction: column; 
        gap: 1rem;
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
    .news-image {
        width: 100%; 
    }
    .news-image img {
        width: 100%;
        height: auto;
        /* --- 这里是关键改动 --- */
        max-height: 400px; /* 为图片设置一个最大高度 */
        object-fit: cover;   /* 确保图片在容器内不变形，而是被优雅地裁剪 */
        /* --- 改动结束 --- */
        border-radius: 8px;
        display: block;
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
</style>

<div class="news-list">

    <div class="news-card">
        <div class="news-image">
            <img src="{{ '/images/news/NCA.png' | relative_url }}">
        </div>
        <div class="news-content">
            <p class="date">November 22, 2024 | New Orleans</p>
            <h3>NCA 2024</h3>
            <p>
                My journey at NCA begins with magic! I'm thrilled to have so many friends by my side.
            </p>
            <p>
                I would especially like to thank Dr. Patrick, and Dr. Dongjing for including me at The Tenth Annual U.S.-China Communication Scholars Summit and for providing the opportunity to share my latest work.
            </p>
            <p>
                This year, I'm honored to serve as the Student Committee Chair for ACCS and as the Graduate Student Representative for CATF division in NCA. Feel free to reach out with any suggestions or for more information.
            </p>
        </div>
    </div>

    <div class="news-card">
        <div class="news-image">
            <img src="{{ '/images/news/ICA2024.png' | relative_url }}">
        </div>
        <div class="news-content">
            <p class="date">June 23, 2024 | Gold Coast</p>
            <h3>ICA 2024</h3>
            <p>
                I thoroughly enjoyed my time in Australia. Cozy was the word I used most frequently during my stay.
            </p>
            <p>
                This year, I and my colleague Kelsie, Christina and Zhi shared two papers about AIGC regulation, emerging media usage and body image issues of adolescents in China.
            </p>
            <p>
                Academic research not only provided a sense of achievement but also fostered valuable friendships. Delighted to meet everyone here!
            </p>
        </div>
    </div>

    <div class="news-card">
        <div class="news-image">
            <img src="{{ '/images/news/SICSS.png' | relative_url }}">
        </div>
        <div class="news-content">
            <p class="date">June 7, 2024 | NUS, Singapore</p>
            <h3>SICSS-Singapore</h3>
            <p>
                This summer, I'm really honored to attend SICSS-Singapore at beautiful National University of Singapore. Five days' talks and discussions were beyond insightful and full of joy. Special thanks to Han Li, Rongxin, Anita, Jinyuan, Xuejiao and Renwen for their uncompromising care and careful organization.
            </p>
            <p>
                Also, thanks to the speakers' generous sharing about their research, it was so inspiring. I highly recommend you sign up for the future SICSS-Singapore event and you won't regret for this decision.
            </p>
        </div>
    </div>

    <div class="news-card">
        <div class="news-image">
            <img src="{{ '/images/news/ICA2023.png' | relative_url }}">
        </div>
        <div class="news-content">
            <p class="date">May 25, 2023 | Toronto</p>
            <h3>ICA 2023</h3>
            <p>
                This is my inaugural experience of attending ICA!
            </p>
            <p>
                I was eager to engage in discourse, to gain insight, and to pursue academic inquiry. Fortunately, I received considerable assistance and support. I regard this academic excursion as a pivotal experience in my life, one that also initiated a new phase.
            </p>
        </div>
    </div>

</div>
