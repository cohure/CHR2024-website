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
        padding: 20px;
    }

    .banner {
        background-color: #002147;
        color: white !important;
        padding: 20px;
        border-radius: 8px;
        display: flex;
        flex-direction: column;
        justify-content: flex-start; /* Changed to flex-start to prevent stretching */
        text-decoration: none;
        transition: all 0.3s ease;
        position: relative;
        min-height: 180px; /* Added minimum height to prevent collapse */
    }

    .banner:hover {
        background-color: #4b0033;
        color: white !important;
        transform: translateY(-2px); /* Added subtle lift effect on hover */
        box-shadow: 0 4px 12px rgba(0,0,0,0.15); /* Added shadow for depth */
    }

    .banner h2 {
        font-size: 1.5rem;
        margin-bottom: 10px;
        color: white !important;
        padding-right: 40px; /* Added padding to prevent overlap with arrow */
    }

    .banner p {
        font-size: 1rem;
        margin-bottom: 40px; /* Increased bottom margin to make space for arrow */
        color: white !important;
        padding-right: 40px; /* Added padding to prevent overlap with arrow */
    }

    .banner .arrow {
        position: absolute;
        bottom: 20px;
        right: 20px;
        width: 36px; /* Slightly larger */
        height: 36px; /* Slightly larger */
        border-radius: 50%;
        background-color: rgba(255, 255, 255, 0.9); /* Slightly transparent */
        color: #002147;
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 1.2rem;
        transition: all 0.3s ease;
        box-shadow: 0 2px 6px rgba(0,0,0,0.1); /* Added subtle shadow */
    }

    /* Improved arrow icon using pseudo-element */
    .banner .arrow::after {
        font-family: Arial, sans-serif;
        font-weight: bold;
        transform: translateX(-1px); /* Center the arrow visually */
    }

    .banner:hover .arrow {
        background-color: white;
        color: #4b0033;
        transform: translateX(5px); /* Arrow moves slightly right on hover */
    }

    /* Responsive design */
    @media (max-width: 480px) {
        .banner {
            min-height: 150px; /* Slightly smaller minimum height on mobile */
        }
        
        .banner h2 {
            font-size: 1.2rem;
        }

        .banner p {
            font-size: 0.9rem;
        }
        
        .banner .arrow {
            width: 32px; /* Slightly smaller on mobile */
            height: 32px;
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
        Join us on December 5th for the conference dinner at Restaurant Havnær in Aarhus Ø, where you can enjoy stunning views of Aarhus Bay and a menu inspired by Nordic and French culinary traditions.
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
            <p>Rent a bike, take the bus, hop onto "Letbanen" or grab a taxi - travel just as you would like!</p>
            <div class="arrow">&gt;</div>
        </a>
                <a href="/venue/sights-in-aarhus" class="banner">
            <h2>Sightseeing in Aarhus</h2>
            <p>Discover all the incredible sights that Aarhus has to offer and learn about the free ARos voucher that you will get by participating in CHR2024.</p>
            <div class="arrow">&gt;</div>
        </a>
</div>