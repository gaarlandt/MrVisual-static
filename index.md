---
title: "Mr. Visual - AI Foto's en Renders"
layout: "layout.njk"
---

<section class="hero">
    <div class="hero-content">
        <h1>Welkom bij Mister Visual</h1>
        <p>Wij creëren hoogwaardige 3D renders en optimaliseren uw foto's met AI.</p>
        <div class="hero-buttons">
            <a href="{{ '/renders/' | url }}" class="btn">Ontdek 3D Renders</a>
            <a href="{{ '/ai-fotos/' | url }}" class="btn btn-secondary">Ontdek AI Foto's</a>
        </div>
    </div>
</section>

<section class="portfolio-carousel-section">
    <div class="container">
        <h2 style="text-align: center;">Onze Projecten</h2>
        <h3 style="text-align: center;">Een selectie van ons recente werk</h3>
    </div>
    <!-- Slider main container -->
    <div class="swiper-container">
        <!-- Additional required wrapper -->
        <div class="swiper-wrapper">
            <!-- Slides -->
            <div class="swiper-slide">
                <img src="{{ '/images/Bennekom-Project-Garden.jpg' | url }}" alt="Project Bennekom">
                <div class="slide-text-overlay">
                    <h4>Project Bennekom</h4>
                    <p>Tuinontwerp</p>
                </div>
            </div>
            <div class="swiper-slide">
                <img src="{{ '/images/Luxembourg-Project-Pool.webp' | url }}" alt="Project Luxembourg">
                <div class="slide-text-overlay">
                    <h4>Project Luxembourg</h4>
                    <p>Zwembad Visualisatie</p>
                </div>
            </div>
            <div class="swiper-slide">
                <img src="{{ '/images/Jall-Lounge-03.jpg' | url }}" alt="Jall Lounge">
                <div class="slide-text-overlay">
                    <h4>Jall Lounge</h4>
                    <p>Interieur Render</p>
                </div>
            </div>
            <div class="swiper-slide">
                <img src="{{ '/images/plattegrond.jpg' | url }}" alt="Plattegrond">
                <div class="slide-text-overlay">
                    <h4>Plattegrond</h4>
                    <p>3D Plattegrond</p>
                </div>
            </div>
            <div class="swiper-slide">
                <img src="{{ '/images/drone.jpg' | url }}" alt="Drone Integratie">
                <div class="slide-text-overlay">
                    <h4>Drone Integratie</h4>
                    <p>Exterieur</p>
                </div>
            </div>
        </div>
        <!-- If we need pagination -->
        <div class="swiper-pagination"></div>
    </div>
</section>

<section class="intro">
    <div class="container">
        <h2>Onze Diensten</h2>
        <div class="intro-grid">
            <div class="intro-card">
                <img src="{{ '/images/Funda foto product.jpeg' | url }}" alt="AI Foto">
                <h3>AI Foto Optimalisatie</h3>
                <p>Verbeter uw vastgoedfoto's met onze geavanceerde AI-technologie. Maak van een standaard foto een droomplaatje.</p>
                <a href="{{ '/ai-fotos/' | url }}" class="btn">Meer informatie</a>
            </div>
            <div class="intro-card">
                <img src="{{ '/images/Foto realistisch product.jpeg' | url }}" alt="3D Render">
                <h3>Fotorealistische 3D Renders</h3>
                <p>Breng uw projecten tot leven met onze verbluffende, fotorealistische 3D-renders. Perfect voor architectuur, interieur en productvisualisatie.</p>
                <a href="{{ '/renders/' | url }}" class="btn">Meer informatie</a>
            </div>
        </div>
    </div>
</section>