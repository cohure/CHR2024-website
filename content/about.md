---
title: "About"
---
<style>
.banner-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 0px;
}

.banner {
    background-color: #002147;
    color: white;
    padding: 15px;  /* minimal padding */
    border-radius: 10px;
    display: flex;
    flex-direction: row; /* row to place arrow beside text */
    align-items: center;
    justify-content: space-between; /* space between text and arrow */
    text-decoration: none;
    transition: all 0.3s ease;
    height: 100%;  /* controlled height */
    width: 100%; /* fixed width for consistency */
    text-decoration: none !important;
}

.banner h2 {
    font-size: 1.2rem;
    margin: 0;
    color: white;
    text-align: left; /* align text to left for better flow */
}

.banner .arrow {
    margin-left: 10px;
    width: 36px;
    height: 36px;
    border-radius: 50%;
    background-color: rgba(255, 255, 255, 0.9);
    color: #002147;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    transition: all 0.3s ease;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

.banner:hover {
    background-color: #4b0033;
}

.banner:hover .arrow {
    background-color: white;
    color: #4b0033;
}

@media (max-width: 480px) {a
    .banner h2 {
        font-size: 1rem;
    }

    .banner .arrow {
        width: 28px;
        height: 28px;
    }
}

</style>


<!-- WRITTEN CONTENT STARTS HERE -->
The Computational Humanities Research (CHR) community is an international and interdisciplinary community that supports researchers with an interest in computational approaches to the humanities. Learn more about the people behind CHR2024 and the organisation of CHR:
<div class="space" style="padding-top:0.5%;"></div>
<div class="banner-grid">
    <a href="/people" class="banner" aria-label="View People section">
        <h2>People</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
    <a href="/contact" class="banner" aria-label="View Community section">
        <h2>Community</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
    <a href="/archive" class="banner" aria-label="View Archive section">
        <h2>Archive</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
</div>