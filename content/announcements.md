---
title: "Announcements"
date: 2021-02-19T16:05:25+01:00
---

<style>
    div.announcements {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
        grid-column-gap: 24px;
        grid-row-gap: 24px;
    }
    .announce {
        /*border: 1px solid;*/
    }

.announce .content {
    padding: 0 0rem 1rem 0rem;
}

    .announce img {
        width: 100%;
        aspect-ratio: 1.7/1;
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
    }
</style>

<div class="announcements">
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
    <div class="announce">
        <img src="..." >
        <div class="content">
            <h3>Lauren-Klein</h3>
            <p>
    Lauren-Klein is a distinguished Research Professor and Associate Professor in the Departments of Quantitative Theory and Methods and English at Emory University, where I also direct the Digital Humanities Lab and serve as PI of the  Atlanta Interdisciplinary AI Network.
            </p>
            <a class="link-button" href="">Read More</a>
        </div>
    </div>
-->
</div>
