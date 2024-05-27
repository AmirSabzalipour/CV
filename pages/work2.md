---
layout: page
title: Work Experience2
permalink: /portfolio2/
subtitle: ""
feature-img: "assets/img/pexels/"
position: 6
---

<style>
    /* Style for the section titles */
    .textbox {
        display: flex;
        justify-content: space-between;
        background-color: white;
        line-height: 40px;
        margin-bottom: 5px;
    }

    .title-container {
        margin-left: -0.4em;
        margin-top: -0.3em;
        display: flex;
        align-items: center;
        margin-bottom: -5px;
    }

    .title-container i {
        margin-top: -15px;
        margin-right: 5px;
        font-size: 25px;
        color: rgba(62, 121, 180, .5);
    }

    .title-container p {
        font-weight: bold;
        font-family: 'Garamond';
        font-size: 20px;
        color: rgba(62, 121, 180, 1);
        margin-left: .1em;
    }

    /* Style for the subsections */
    .textbox2 {
        background-color: #f0f0f0;
        border: 1px solid white;
        border-radius: 30px;
        padding: -2px;
        margin: 0;
        box-shadow: 0 2px 2px white;
        position: relative;
        display: flex;
        align-items: center;
        width: 100%;
    }

    .main-content {
        flex: 1;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
    }

    .main-content p {
        font-weight: bold;
        font-family: 'Garamond';
        font-size: 20px;
        color: rgba(62, 121, 180, 1);
        margin-left: 1em;
        margin-top: 27px; /* Adjust vertical position */
        margin-bottom: -10px; /* Adjust vertical position */
    }

    .main-content ul {
        font-size: 15px;
        font-family: 'Avenir Next LT Pro Regular', sans-serif;
        margin-left: 1.7em;
        color: black;
        margin-top: 20px;
        margin-bottom: 20px;
    }

    .main-content ul li {
        margin-left: 12px;
        margin-top: 12px;
        margin-bottom: 12px;
    }

    .gradient-line::before {
        content: '';
        position: absolute;
        top: 54px;
        left: 0px;
        width: 100%;
        height: 3px;
        background: rgba(62, 121, 180, .5);
        border-radius: 10px;
    }

   .additional-column {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    padding: 0px;
    width: 160px;
    border-radius: 10px;
    margin-right: 20px; /* Adjusted to move the column to the right */
}

.additional-column p,
.additional-column span {
    font-family: 'Avenir Next LT Pro';
    font-size: 15px;
    color: inherit;
    margin: 5px 0 5px 0;
    padding: 0 5px 0 10px;
}

.additional-column span.date {
    color: rgba(200, 144, 98, 1);
    margin-top: -20px; /* Adjusted to bring the date closer to the location */
    padding-right: 10px;
}

.additional-column span.location {
    color: rgba(200, 144, 98, 1);
    margin-left: 0;
    padding-bottom: 0;
    padding-right: 5px;
}


    /* Responsive adjustments for smaller screens */
    @media only screen and (max-width: 600px) {
        .title-container {
            flex-direction: column;
            align-items: flex-start;
            margin-left: 0;
            margin-top: 0;
            margin-bottom: 0;
        }

        .title-container i {
            margin-right: 0;
            margin-bottom: 5px;
            margin-top: -20px;
        }

        .title-container p {
            font-size: 18px;
            margin-left: 0;
        }

        .textbox2 {
            flex-direction: column;
            align-items: flex-start;
        }

        .main-content p {
            font-size: 16px;
            margin-left: 0;
        }

        .main-content ul {
            margin-left: 1em;
        }

        .additional-column {
            width: 100%;
            height: auto;
            margin-top: 10px;
        }

        .additional-column p, .additional-column span {
            position: static;
            margin-top: 5px;
        }

        .textbox2 .gradient-line::before {
            top: 47px;
            left: 10px;
            width: 98%;
            height: 3px;
            background: rgba(62, 121, 180, .5);;
            border-radius: 10px;
        }
    }
</style>

<body>
    <section>
        <div class="textbox">
            <div class="title-container">
                <i class="fa fa-briefcase"></i>
                <p>Computational Research on Materials</p>
            </div>
        </div>
        <br>
        <div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Postdoctoral Researcher</p>
                </div>
                <ul>
                    <li>Python-based modeling and simulation of electrical resistivity at micron and nanometer scales.</li>
                    <li>Developing computational models to optimize energy loss in quantum topological materials, incorporating statistical, electrical, quantum, and topological features.</li>
                </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date">10.2021 - 06.2023</span>
                <span class="location">University of Antwerp</span>
            </div>
        </div>
        <br>

<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Doctoral Researcher</p>
                </div>
                <ul>
                    <li>Simulations of materials using VASP package on a High-performance computing (HPC) cluster.</li>
                    <li>Conducting numeric and analytical computations utilizing the Wolfram Language and Python.</li>
                    <li>Data visualization, analysis of observed behavior, and reporting findings to scientific journals.</li>
                </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date">03.2017 - 10.2021</span>
                <span class="location">University of Antwerp</span>
            </div>
        </div>
        <br>

<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Visiting Researcher</p>
                </div>
                <ul>
                    <li>Statistical and dynamical study of anomalous electrical properties of semiconductors under thermodynamic fluctuation and with magnetic impurities.</li>
                </ul>
                <p style="font-family: 'Avenir Next LT Pro'; font-weight: normal; font-size: 14px; color: gray; margin-top: -20px;">IPM : Institute for Research in Fundamental Sciences, Tehran</p>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date">03.2016 - 02.2017</span>
                <span class="location">IPM</span>
            </div>
        </div>
        <br>

<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Visiting Researcher</p>
                </div>
                <ul>
                    <li>Nanoscale simulations of 2D materials using Quantum ESPRESSO package.</li>
                </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date">03.2015 - 02.2016</span>
                <span class="location">Another Institution</span>
            </div>
        </div>
    </section>
</body>
