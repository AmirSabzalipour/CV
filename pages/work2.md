---
layout: page
title: Experience2
permalink: /portfolio2/
subtitle: ""
feature-img: "assets/img/pexels/"
position: 6
---

<style>
    /* Reset default margin and padding */
    body {
        margin: 0;
        padding: 10px;
        background-image: url('assets/img/header/education.jpg');
        background-repeat: no-repeat;
        background-position: center center;
        background-size: cover; /* Ensure the background image covers the entire viewport */
    }
    .textbox {
        background-color: #f0f0f0;
        border: 1px solid white;
        border-radius: 30px;
        padding: 10px;
        margin: 0;
        box-shadow: 0 2px 2px white;
        position: relative;
        display: flex; /* Ensure relative positioning for absolute positioning of pseudo-element */
    }

    .textbox::before {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        width: 100%; /* Take up the full width of the box */
        height: 8px; /* Thickness of the strip */
        border-radius: 20px; /* Ensure rounded corners on the top */
    }

    .textbox h3 {
        color: #333;
        font-size: 12px;
        margin-bottom: 10px;
    }

    .textbox p {
        color: #666;
        font-size: 18px;
        line-height: 1.6;
    }

    .responsive-text {
        font-size: 23px; /* Global font size for .responsive-text */
        font-family: 'Garamond';
        color: #abb8a0;
    }

    .main-content .position-title {
        font-weight: bold;
        font-family: 'Garamond';
        font-size: 20px; /* Default font size for large screens */
        color: rgba(62, 121, 180, 1);
        margin-left: 0.9em;
    }

    @media only screen and (max-width: 600px) {
        /* Adjust styles for small screens */
        .textbox {
            flex-direction: column;
            align-items: flex-start;
            padding: 3px;
        }

        .textbox > div {
            margin-left: 0;
            margin-top: 0;
            margin-bottom: 0;
        }

        .textbox i {
            margin-right: 0;
        }

        .textbox p {
            font-size: 6px; /* Adjusted font size for paragraphs on small screens */
            margin-left: 0;
            margin-top: 2px;
        }

        .responsive-text {
            font-size: 18px; /* Smaller font size for smaller screens */
        }

        .main-content .position-title {
            font-size: 15px; /* Adjusted font size for Postdoctoral Researcher on small screens */
        }

        /* Remove styles for additional column */
        .textbox .additional-column {
            display: none;
        }
    }
</style>


<section>
    <div class="textbox" style="display: flex; justify-content: space-between; border: 0.5px solid white; background-color: white; line-height: 40px; margin-bottom: -5px;">
        <div style="margin-left: 0.4em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: -5px;">
            <i class="fa fa-briefcase" style="margin-right: 5px; color: #abb8a0;"></i> <!-- Icon -->
            <p class="responsive-text" style="font-weight: bold; margin-left: 0.2em;"> Computational Research on Materials</p> <!-- Text -->
        </div>
    </div>
        <div class="textbox" style="display: flex; justify-content: space-between; line-height: 90px; margin-bottom: 10px;">
    <div class="main-content" style="flex: 1;">
        <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;">
            <p class="position-title">Postdoctoral Researcher</p>
        </div>
        <ul style="font-size: 15px; font-family: 'Avenir Next LT Pro Regular', sans-serif; margin-left: 1.7em; color: black;">
            <li style="margin-bottom: 10px;">Python-based modeling and simulation of electrical resistivity at micron and nanometer scales.</li>
            <li style="margin-bottom: 10px;">Developing computational models to optimize energy loss in quantum topological materials, incorporating statistical, electrical, quantum and topological features.</li>
        </ul>
        <div style="::before; content: ''; position: absolute; top: 47px; left: 10px; width: 98%; height: 2.5px; background: linear-gradient(to right, rgba(62, 121, 180, 0.6) 79.5%, rgba(200, 144, 98, 1) 20.5%); border-radius: 10px;"> </div>
    </div>
    <div class="additional-column" style="width: 160px; height: 100px; position: relative;">
        <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray; position: absolute; top: 0; left: 0;"> </span></p>
        <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200, 144, 98, 1); position: absolute; top: 5px; left: 10px;">10.2021 - 06.2023</span></p>
        <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200, 144, 98, 1); position: absolute; top: 50px; left: 6px;">University of Antwerp</span></p>
    </div>
</div>
    <div class="textbox" style="display: flex; justify-content: space-between; line-height: 90px; margin-bottom: 10px;">
        <div class="main-content" style="flex: 1;">
            <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                <p style="font-weight: bold; font-family: 'Garamond'; font-size: 20px; color: rgba(62, 121, 180, 1); margin-left: 0.9em;">Doctoral Researcher</p>
            </div>
            <ul style="font-size: 15px; font-family: 'Avenir Next LT Pro Regular', sans-serif; margin-left: 1.7em; color: black;">
                <li style="margin-bottom: 10px;">Simulations of materials using VASP package on a High-performance computing (HPC) cluster.</li>
                <li style="margin-bottom: 10px;">Conducting numeric and analytical computations utilizing the Wolfram Language and Python.</li>
                <li style="margin-bottom: 10px;">Data visualization, analysis of observed behavior, and reporting findings to scientific journals.</li>
            </ul            >
            <div style="::before; content: ''; position: absolute; top: 47px; left: 10px; width: 98%; height: 3px; background: linear-gradient(to right, rgba(62, 121, 180, 0.6) 80%, rgba(64, 130, 109, 1) 20%); border-radius: 10px;"> </div>
        </div>
        <div class="additional-column" style="width: 160px; height: 100px; position: relative;">
            <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray; position: absolute; top: 0; left: 0;"> </span></p>
            <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(64, 130, 109, 1); position: absolute; top: 5px; left: 10px;">03.2017 - 10.2021</span></p>
            <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(64, 130, 109, 1); position: absolute; top: 50px; left: 6px;">University of Antwerp</span></p>
        </div>
    </div>
    <div class="textbox" style="display: flex; justify-content: space-between; line-height: 90px; margin-bottom: 10px;">
        <div class="main-content" style="flex: 1;">
            <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                <p style="font-weight: bold; font-family: 'Garamond'; font-size: 20px; color: rgba(62, 121, 180, 1); margin-left: 0.9em;">Visiting Researcher</p>
            </div>
            <ul style="font-size: 15px; font-family: 'Avenir Next LT Pro Regular', sans-serif; margin-left: 1.7em; color: black;">
                <li style="margin-bottom: 10px;">Statistical and dynamical study of anomalous electrical properties of semiconductors via simulation and analysis.</li>
                <li style="margin-bottom: 10px;">Designing effective visualization methods for understanding electrical properties of materials using Python libraries.</li>
            </ul>
            <div style="::before; content: ''; position: absolute; top: 47px; left: 10px; width: 98%; height: 3px; background: linear-gradient(to right, rgba(62, 121, 180, 0.6) 70%, rgba(200, 144, 98, 1) 30%); border-radius: 10px;"> </div>
        </div>
        <div class="additional-column" style="width: 160px; height: 100px; position: relative;">
            <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray; position: absolute; top: 0; left: 0;"> </span></p>
            <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200, 144, 98, 1); position: absolute; top: 5px; left: 10px;">09.2018 - 12.2018</span></p>
            <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200, 144, 98, 1); position: absolute; top: 50px; left: 6px;">University of Freiburg</span></p>
        </div>
    </div>
</section>
