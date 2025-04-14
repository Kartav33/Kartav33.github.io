---
layout: home
title: Home
landing-title: 'Hi, my name is <i>Kartav</i>!'
description: null
image: null
author: null
show_tile: false
---
Please follow along the link to see the timeline of all of my scientific visits to various institutions and organizations.  

<!-- Mini Gallery Section -->
<style>
    .mini-gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
        padding: 30px 0;
    }

    .mini-gallery img {
        width: 300px;
        height: 200px;
        object-fit: cover;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
        transition: transform 0.3s ease;
    }

    .mini-gallery img:hover {
        transform: scale(1.05);
    }

    .see-more {
        position: relative;
        cursor: pointer;
        overflow: hidden;
    }

    .see-more::before {
        content: "View Full Gallery →";
        position: absolute;
        bottom: 0;
        left: 0;
        width: 100%;
        height: 100%;
        color: white;
        background: rgba(0, 0, 0, 0.6);
        font-weight: bold;
        font-size: 1.1rem;
        display: flex;
        align-items: center;
        justify-content: center;
        text-align: center;
        opacity: 1; /* Always visible */
        border-radius: 10px;
    }

    @media (max-width: 768px) {
        .mini-gallery img {
            width: 90%;
            height: auto;
        }
    }
</style>

<section class="mini-gallery">
    <img src="{{ '/assets/images/visit/su-a.jpg' | relative_url }}" alt="Visit 1">
    <img src="{{ '/assets/images/visit/upc-a.jpg' | relative_url }}" alt="Visit 2">
    <img src="{{ '/assets/images/visit/iucaa-c.JPEG' | relative_url }}" alt="Visit 3">
    <img src="{{ '/assets/images/visit/iisc-poster.jpg' | relative_url }}" alt="Visit 4">
    <img src="{{ '/assets/images/visit/icts-d.jpg' | relative_url }}" alt="Visit 5">
    <!-- Last image styled differently for navigation -->
    <a href="{{ '/gallery.html' | relative_url }}" class="see-more">
        <img src="{{ '/assets/images/visit/iia-c.jpg' | relative_url }}" alt="See More">
    </a>
</section>

PS: This website will always be under construction. Feel free to share any sugesstions.
