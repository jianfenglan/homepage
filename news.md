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
            <img src="{{ '/images/news/Apple.png' | relative_url }}" >
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
            <img src="{{ '/images/news/Hongyi.png' | relative_url }}">
        </div>
        <div class="news-content">
            <p class="date">December 3, 2023 | CQU, Chongqing</p>
            <h3>Hongyi Forum</h3>
            <p>
                What a great honor!
            </p>
            <p>
                I was invited to share my research at Chongqing University, School of Journalism, where I received my B.A. degree.
            </p>
            <p>
                Guess who also won the third-place award in this forum?
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
