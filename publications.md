---
title: "Publications: on the record"
permalink: /publications/
author_profile: true
---

<style>
    /* 出版物列表的容器 */
    .publication-list {
        display: grid; /* 使用grid布局，方便控制间距 */
        grid-template-columns: 1fr; /* 始终为单列 */
        gap: 1rem; /* 卡片之间的间距 */
        counter-reset: pub-counter; /* 【核心】初始化一个名为 "pub-counter" 的计数器 */
        margin-top: 1rem; /* 标题和列表间的距离 */
    }

    /* 单个出版物卡片的样式 */
    .publication-card {
        display: flex; /* 使用flex布局，为了将序号和文字内容分开 */
        align-items: flex-start; /* 顶部对齐 */
        gap: 1em; /* 序号和文字之间的间距 */
        
        /* --- 卡片化样式 --- */
        background: white;
        border: 1px solid #e9e9e9;
        border-radius: 12px;
        padding: 1.25rem 1.5rem;
        box-shadow: 0 2px 8px rgba(0,0,0,0.06);
        transition: transform 0.2s ease, box-shadow 0.2s ease;
        line-height: 1.6; /* 增加行高，提升可读性 */
    }

    .publication-card:hover {
        transform: translateY(-4px);
        box-shadow: 0 6px 16px rgba(0,0,0,0.1);
    }
    
    /* 【核心】使用 ::before 伪元素来生成和显示自动序号 */
    .publication-card::before {
        counter-increment: pub-counter; /* 让计数器+1 */
        content: counter(pub-counter) "."; /* 显示计数器的值，并在后面加个点 */
        
        /* 序号的样式 */
        font-weight: 600;
        font-size: 1.1em;
        color: #888;
        min-width: 2em; /* 给序号留出固定空间，让排版更整齐 */
        text-align: right;
    }
    
    /* 包裹主要文字内容的容器 */
    .publication-content {
        flex: 1;
    }
</style>

<h3>Journal Articles｜期刊论文</h3>
<div class="publication-list">

    <div class="publication-card">
        <div class="publication-content">
            Mou, Y.\*, <strong>Lan, J.</strong>\*, & Huang, Y. (2023). Good night versus goodbye? comparing the mourning Remarks of virtual and human uploaders through a data-mining approach. <em>New Media & Society</em>, Online first. (*co-first author)
        </div>
    </div>

    <div class="publication-card">
        <div class="publication-content">
            牟怡, <strong>蓝剑锋</strong>. (2023). 机器写作中的性别刻板印象:基于实验研究的实然探讨. <em>中国网络传播研究</em>, (1)1:236-266.
        </div>
    </div>

    <div class="publication-card">
        <div class="publication-content">
            <strong>Lan, J.</strong>, Huang, Y. (2025). Performing Intimacy: Curating the Self- presentation in Human–AI Relationships. <em>Emerging Media</em>, Online first.
        </div>
    </div>

</div>

<hr />

<h3>Conference Papers｜会议论文</h3>
<div class="publication-list"> <div class="publication-card">
        <div class="publication-content">
            <strong>Lan, J.</strong>, Mou, Y., Huang, Y. (2023). Good night vs. goodbye? comparing the mourning remarks for virtual and human uploaders by a data-mining approach. <em>73rd ICA Annual Conference</em>, Toronto, Canada.
        </div>
    </div>

    <div class="publication-card">
        <div class="publication-content">
            <strong>Lan, J.</strong>, Huang Y., Mou Y. (2024). Examining the impact of social media use on Chinese male adolescent’s body image: a cross-platform perspective. <em>74th ICA Annual Conference</em>, Gold Coast, Australia.
        </div>
    </div>
    
    <div class="publication-card">
        <div class="publication-content">
            Jin, Q., <strong>Lan, J.</strong>, Lin, Z. (2024). Share my face: understanding privacy paradox and third-person effect of artificial intelligence generated content (AIGC) applications. <em>74th ICA Annual Conference</em>, Gold Coast, Australia.
        </div>
    </div>
    
    <div class="publication-card">
        <div class="publication-content">
            Mou, Y., <strong>Lan, J.</strong>, Lu, J., Wang, J. (2024). Emerging Media Use and Acceptance of Digital Immortality: A Cluster Analysis among Chinese Young Generations. <em>NCA 2024</em>, New Orleans, U.S.
        </div>
    </div>

    <div class="publication-card">
        <div class="publication-content">
            <strong>Lan, J.</strong>, Huang Y. (2025). Love the way you are: examine the attribute of human-AI intimate relationships. <em>75th ICA Annual Conference</em>, Denver, U.S.
        </div>
    </div>

    <div class="publication-card">
        <div class="publication-content">
            Mou, Y., Li, J., <strong>Lan, J.</strong> (2025). A Cross-Cultural Diachronic Examination of Audiences’ Attitudes Toward Digital Immortality in Science Fiction. <em>IAMCR 2025</em>, Singapore.
        </div>
    </div>

    <div class="publication-card">
        <div class="publication-content">
            <strong>Lan, J.</strong>, Huang, Y. (2025). Reconfiguring Sociality: Human-AI Intimacy, Narcissistic Dynamics, and Replika. <em>Society for Social Studies of Science (4S) 2025</em>, Seattle, U.S.
        </div>
    </div>
    
    <div class="publication-card">
        <div class="publication-content">
            Huang, Y., <strong>Lan, J.</strong> (2025). Media Metaphors and Social Meaning of ‘Internet’ in Taiwan (1995-2023). <em>AEJMC 2025</em>, San Francisco, U.S. <strong>[Second Runner Up (3rd Place) Student Paper Award]</strong>
        </div>
    </div>

</div>
