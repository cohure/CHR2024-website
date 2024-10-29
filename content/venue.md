---
title: "Venue"
date: 2021-02-19T16:05:25+01:00
---

<!--html settings for banner-->
<style>
.banner-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 0px;
}

.banner {
    background-color: #002147;
    color: white !important;
    padding: 25px;  /* increase overall padding */
    border-radius: 10px;
    display: grid;
    grid-template-rows: auto auto 1fr;  /* control spacing */
    text-decoration: none;
    transition: all 0.3s ease;
    position: relative;
    height: 260px;
    gap: 20px;  /* gap between grid rows */
    text-decoration: none !important;
}

.banner:hover {
    background-color: #4b0033;
    color: white !important;
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.banner h2 {
    font-size: 1.1rem;
    margin: 0;
    color: white !important;
    padding-right: 40px;
    line-height: 1.3;
    max-height: 2.6em;  /* limit to two lines */
}

.banner-content {
    /* will contain the paragraph */
    align-self: start;
}

.banner p {
    font-size: 0.9rem;
    margin: 0;
    color: white !important;
    padding-right: 20px;
    line-height: 1.5;
}

.banner-footer {
    align-self: end;
    position: relative;
}

.banner .arrow {
    position: absolute;
    right: 20px;  
    bottom: 20px;
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

.banner .arrow::after {
    font-family: Arial, sans-serif;
    font-weight: bold;
    transform: translateX(-1px);
}

.banner:hover .arrow {
    background-color: white;
    color: #4b0033;
    transform: translateX(5px);
}

@media (max-width: 480px) {
    .banner {
        max-height: 160px;  /* max height for mobile */
        min-height: 100px;
        padding: 15px;  /* reduced padding */
        gap: 20px;  /* reduced gap */
    }

    .banner h2 {
        font-size: 1.1rem;  /* smaller font size */
        max-height: 2.2em;  /* constrain to two lines */
        -webkit-line-clamp: 2;
    }

    .banner p {
        font-size: 0.85rem;  /* slightly smaller font */
    }

    .banner .arrow {
        width: 28px;
        height: 28px;
    }
}
</style>


<!--WRITTEN CONTENT STARTS HERE-->
The CHR2024 Conference will be held on December 4-6 with workshops taking place on the December 3rd.
The conference will take place in Aarhus, Denmark at Aarhus University, in their historical buildings located in the city center, close to the urban environment and its vibrant atmosphere as well as nature, including parks, forest and the coastline.

<div class="banner-grid">
    <a href="/venue/conference-dinner" class="banner">
        <h2>The Conference Dinner</h2>
        <p>
        Join us on for the conference dinner at Restaurant Havnær with stunning views of Aarhus Bay and a menu inspired by Nordic and French culinary traditions.
        </p>
        <div class="arrow">&gt;</div>
        </a>
        <a href="/venue/accomodation-in-aarhus" class="banner">
            <h2>Accomodation in Aarhus</h2>
            <p>Aarhus offers a range of excellent hotels. Gain an overview and see the exclusive discounts for the CHR2024 conference.</p>
            <div class="arrow">&gt;</div>
        </a>
        <a href="/venue/travelling-to-aarhus" class="banner">
            <h2>Travelling to Aarhus</h2>
            <p>Going to Aarhus by plane, train, ferry or something else? Read more about the many travel options that lead you to CHR2024.</p>
            <div class="arrow">&gt;</div>
        </a>
        <a href="/venue/getting-around-aarhus" class="banner">
            <h2>Getting around in Aarhus</h2>
            <p>Walk around, rent a bike, take the bus or grab a taxi - get information on how to travel around Aarhus just as you would like.</p>
            <div class="arrow">&gt;</div>
        </a>
                <a href="/venue/sights-in-aarhus" class="banner">
            <h2>Sightseeing in Aarhus</h2>
            <p>Discover Aarhus before and after CHR2024 with our curated recommendations for must-see experiences.
            </p>
            <div class="arrow">&gt;</div>
        </a>
        </a>
                <a href="/venue/culinary-delights-aarhus" class="banner">
            <h2>Dining in Aarhus</h2>
            <p>Aarhus’ diverse dining scene has something for every palate, from gourmet experiences to casual favourites.
            </p>
            <div class="arrow">&gt;</div>
        </a>
</div>