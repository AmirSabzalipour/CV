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
        margin-bottom: -5px;
    }

    .title-container {
        margin-left: 0.4em;
        margin-top: -0.1em;
        display: flex;
        align-items: center;
        margin-bottom: -5px;
    }

    .title-container i {
        margin-right: 5px;
        color: #abb8a0;
    }

    .title-container p {
        font-weight: bold;
        font-family: 'Garamond', serif;
        font-size: 23px;
        color: #abb8a0;
        margin-left: .2em;
    }

    /* Style for the subsections */
    .textbox2 {
        background-color: #f0f0f0;
            border: 1px solid white;
            border-radius: 30px 30px 30px 30px;
            padding: 1px ;
            margin:0;
            box-shadow: 0 2px 2px white;
            position: relative; 
            display: flex;/* Ensure rensure gradient line is positioned relative to this container */
    }

    .main-content {
        flex: 1;
    }

    .main-content p {
        font-weight: bold;
        font-family: 'Garamond', serif;
        font-size: 20px;
        color: rgba(62, 121, 180, 1);
        margin-left: 1.2em;
    }

    .main-content ul {
        font-size: 15px;
        font-family: 'Avenir Next LT Pro Regular', sans-serif;
        margin-left: 1.7em;
        color: black;
    }

    .main-content ul li {
        margin-bottom: 10px;
    }

    .gradient-line::before {
        content: '';
        position: absolute;
        top: 47px;
        left: 10px;
        width: 98%;
        height: 3px;
        background: linear-gradient(to right, rgba(62, 121, 180, 0.6) 80%, rgba(64, 130, 109, 1) 20%);
        border-radius: 10px;
    }

    .additional-column {
        padding: -10px;
        width: 200px;
        height: 100px;
        position: relative;
    }

    .additional-column p {
        font-family: 'Avenir Next LT Pro';
        font-size: 15px;
        color: gray;
        position: absolute;
        top: -4px;
        left: -10px;
    }

    .additional-column span {
        font-family: 'Avenir Next LT Pro';
        font-size: 15px;
        color: rgba(200, 144, 98, 1);
    }

    .additional-column span.date {
        font-family: 'Avenir Next LT Pro'; 
        font-size: 15px;
        color: rgba(200,144,98,1); 
        /* position: absolute;  */
        top: 0px; 
        left: -20px;
        
    }

    .additional-column span.location {
        top: 50px;
        left: 6px;
        /* position: absolute; */
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
        }

        .title-container p {
            font-size: 18px; /* Adjusted font size for smaller screens */
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

        /* Add gradient line to textbox2 for small screens */
        .textbox2 .gradient-line::before {
            top: 47px; /* Adjust this value to fit your design */
            left: 10px;
            width: 98%;
            height: 3px;
            background: linear-gradient(to right, rgba(62, 121, 180, 0.6) 80%, rgba(64, 130, 109, 1) 20%);
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

<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Postdoctoral Researcher</p>
                </div>
                <ul>
                    <li>Python-based modeling and simulation of electrical resistivity at micron and nanometer scales.</li>
                    <li>Developing computational models to optimize energy loss in quantum topological materials, incorporating statistical, electrical, quantum and topological features.</li>
                </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <p></p>
                <p><span class="date">10.2021-06.2023</span></p>
                <p><span class="location">University of Antwerp</span></p>
            </div>
        </div>
