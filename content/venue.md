---
title: "Venue"
---

<!--html settings for banner-->
<style>
/* define banner for about page */
.banner-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 0px;
}

/* special case for 4 elements - 2x2 */
.banner-grid.four-items {
    grid-template-columns: repeat(2, 1fr);
}

/* special case for 6 elements - 3x3 */
.banner-grid.six-items {
    grid-template-columns: repeat(3, 1fr);
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

/* ensure banners - whether four-item or not, is a list on mobile */
    .banner-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 0px;
}

.banner-grid.four-items {
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}
}
</style>


<!--WRITTEN CONTENT STARTS HERE-->
The CHR2024 Conference will be held on <span style="font-weight: 700;">December 4-6</span> with workshops taking place on the December 3rd. The conference will take place in <span style="font-weight:700;">Aarhus, Denmark at Aarhus University</span>, in their historical buildings located in the city center, close to the vibrant urban environment as well as nature, including parks, forest and the coastline. 

The main address of the CHR2024 conference is [Bartholins Allé 8, 8000 Aarhus C](https://maps.app.goo.gl/9sM2wLpzXuNjrWNr8), where the registration and breakfast take place on the first day.

<div class="space" style="padding-top:1%;"></div>

<h3 style="font-weight:bold;">Conference Information</h3>

Need tips on public transport in Aarhus or details about the conference dinner? Get all practical information about CHR2024: 

<div class="banner-grid four-items">
    <a href="/venue/finding-the-venue" class="banner" aria-label="Press to get an overview of the buildings for CHR2024">
        <h2>Finding the Venue</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
    <a href="/venue/getting-around-aarhus" class="banner" aria-label="Press to find out how to get around Aarhus">
        <h2>Getting around in Aarhus</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
    <a href="/venue/conference-dinner" class="banner" aria-label="Press to learn more about the Conference Dinner at Restaurant Havnær">
        <h2>About the Conference Dinner</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
    <a href="/venue/conference-dinner#conference-dinner-transport" class="banner" aria-label="Press to learn more about how to get to the conference dinner">
        <h2>Get to the Conference Dinner</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
    <a href="https://eduroam.au.dk/en/" class="banner" aria-label="Press to learn more about WIFI at the conference venue">
        <h2>WIFI AT THE VENUE</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
</div>

<div class="space" style="padding-top:2%;"></div>


<h3 style="font-weight:bold;">Explore Aarhus</h3>

Discover Aarhus's incredible sights and culinary delights with our curated recommendations:

<div class="banner-grid">
    <a href="/venue/sights-in-aarhus" class="banner" aria-label="Press to explore sights and attractions in Aarhus">
        <h2>Sightseeing in Aarhus</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
    <a href="/venue/culinary-delights-aarhus" class="banner" aria-label="Press to explore dining options in Aarhus">
        <h2>Dining in Aarhus</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
</div>

<div class="space" style="padding-top:2%;"></div>

<h3 style="font-weight:bold;">Booking Your Stay</h3>

Looking for a hotel near fellow conference attendees? Not sure how to reach Aarhus by train, bus, or plane? Learn more here:
<div class="banner-grid">
    <a href="/venue/accomodation-in-aarhus" class="banner" aria-label="Press to view accommodation options in Aarhus">
        <h2>Accommodation in Aarhus</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
    <a href="/venue/travelling-to-aarhus" class="banner" aria-label="Press to learn about travel options to Aarhus">
        <h2>Travelling to Aarhus</h2>
        <div class="banner-footer">
            <div class="arrow" aria-hidden="true">→</div>
        </div>
    </a>
</div>

<div class="space" style="padding-top:3%;"></div>