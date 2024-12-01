---
layout: page
title: Work Experience
permalink: /portfolio2/
subtitle: ""
feature-img: "assets/img/pexels/"
position: 3
---



<style>
    /* Style for the section titles */
    .textbox {
        display: flex;
        font-weight: bold;
        font-family: 'Garamond';
        font-size: 20px;
        color: #abb8a0;
        margin-left: 0.1em;
    }

    :root {
        --gradient-line-width: 100%; /* Define the width of the gradient line */
    }

    .gradient-line::before {
        content: '';
        position: absolute;
        top: 54px;
        left: 0;
        width: var(--gradient-line-width);
        height: 3px;
        background: linear-gradient(to right, rgba(62, 121, 180, 0.6) 78%, rgba(200, 144, 98, 1) 23%);
        border-radius: 10px;
    }

    .additional-column {
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        padding: 0;
        font-size: 17px;
        width: calc(var(--gradient-line-width) * 0.2); /* 20% of the gradient line width */
        border-radius: 20px;
        margin-right: -10px;
        position: relative;
    }

    .additional-column span.date {
        font-size: 17px;
        color: rgba(200, 144, 98, 1);
        margin-top: -25px; /* Adjusted to bring the date closer to the location */
        margin-left: 10px;
        position: relative; /* Added to allow for relative positioning */
        top: -20px; /* Moves the date upwards */
    }

    .additional-column span.location {
        font-size: 16px;
        color: rgba(200, 144, 98, 1);
        margin-left: 10px;
        padding-bottom: 17px;
        margin-top: 10px;
        position: relative; /* Added to allow for relative positioning */
        top: -10px; /* Moves the location upwards */
    }

    /* Responsive adjustments for smaller screens */
    @media only screen and (max-width: 600px) {
        .gradient-line::before {
            top: 50px;
            left: 10px;
            width: 98%;
            height: 3px;
            background: rgba(62, 121, 180, 0.2);
            border-radius: 10px;
        }
    }
</style>

<body>
    <section>
        <div class="textbox">
            <div class="title-container">
                <i class="fa fa-briefcase"></i>
                <h3>Computational Research on Materials</h3>
            </div>
        </div>
        <br>
        <div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <h4>Postdoctoral Researcher</h4>
                </div>
                <ul>
                    <li style="list-style-type: none; color: gray; font-size: 15px;">Key Responsibilities</li>
                    <li>Python-based simulation of materials properties at micron and nanometer scales.</li>
                    <li>Developing computational models to optimize energy loss in quantum topological materials, incorporating statistical, electrical, quantum, and topological features.</li>
                </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date">10.2021 - 06.2023</span>
                <span class="location">University of Antwerp</span>
            </div>
        </div>
        <div style="height: 30px;"></div>
        <div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <h4>Doctoral Researcher</h4>
                </div>
                <ul>
                    <li style="list-style-type: none; color: gray; font-size: 15px;">Key Responsibilities</li>
                    <li>High-performance computing (HPC) and simulation with the VASP package.</li>
                    <li>Mathematical modeling and computer simulation based on Mathematica and Python.</li>
                    <li>Data visualization, analysis, and reporting findings to scientific journals.</li>
                </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date">03.2017 - 10.2021</span>
                <span class="location">University of Antwerp</span>
            </div>
        </div>
    </section>
    <!-- Additional sections follow a similar structure -->
</body>
