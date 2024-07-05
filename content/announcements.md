---
title: "Announcements"
date: 2021-02-19T16:05:25+01:00
---

<style>
    div.announcements {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(min(400px, 100%), 1fr));
        grid-column-gap: 24px;
        grid-row-gap: 24px;
    }
    .announce {
        /*border: 1px solid;*/
        display: flex;
        flex-direction: column;
    }

    .announce .content {
        padding: 0 0rem 1rem 0rem;
        display: flex;
        flex-direction: column;
        flex-grow: 1;
    }

    .announce .content h3 {
        margin-bottom: 0px;
    }
    .announce img {
        width: 100%;
        aspect-ratio: 2/1;
        object-fit: cover;
        object-position: 100% 0;
    }

    p {
        font-size: 1rem;
    }

    .link-button {
        display: inline-block;
        padding: 0.5rem 1rem;
        border: 1px solid;
        border-radius: 24px;
        margin-top: auto;
        align-self: flex-start;
    }
</style>

<div class="announcements">
    <div class="announce">
        <img src="/images/announce/CHR2024-extension.jpg" alt="Call for Papers">
        <div class="content">
            <h3>CFP Deadline Extension</h3>
            <p>
New submission deadline: July 15, 2024. We invite original research papers from a wide range of topics, 
including – but not limited to – the following: Applications of statistical methods and machine learning to process, 
enrich and analyse...
            </p>
            <a class="link-button" href="/cfp">Read More</a>
        </div>
    </div>
    <div class="announce">
        <img src="/images/announce/lauren-klein.jpg" >
        <div class="content">
            <h3>Keynote Lauren Klein</h3>
            <p>
    We are happy to announce that Lauren Klein, Winship Distinguished Research Professor and Associate Professor in the 
departments of Quantitative Theory & Methods and English at Emory University, will give a keynote speech at the 
Computational Humanities Research 2024 Conference...
            </p>
            <a class="link-button" href="/announcements/lauren-klein">Read More</a>
        </div>
    </div>
    <div class="announce">
        <img src="/images/announce/CHR2024-CFP-website.jpg" alt="Call for Papers">
        <div class="content">
            <h3>Call for Papers</h3>
            <p>
We invite original research papers from a wide range of topics, including – but
not limited to – the following: Applications of statistical methods and machine learning to process, enrich and analyse 
humanities data, including new media and cultural heritage data...
            </p>
            <a class="link-button" href="/cfp">Read More</a>
        </div>
    </div>
<!--

-->
</div>
