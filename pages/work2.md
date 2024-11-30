---
layout: page
title: Work Experience
permalink: /portfolio2/
subtitle: ""
feature-img: "assets/img/pexels/"
position: 3
---

<style>
    /* Background color for the page */
    body {
        background-color: red;
    }

    /* Style for the section titles */
    .textbox {
        display: flex;
        justify-content: space-between;
        background-color: white;
        line-height: 40px;
        margin-bottom: 5px;
    }

    .title-container {
        margin-left: -0.8em;
        margin-top: -0.3em;
        display: flex;
        align-items: center;
        margin-bottom: -5px;
    }

    .title-container i {
        margin-top: -15px;
        margin-right: 5px;
        font-size: 26px;
        color: #abb8a0;
    }

    .title-container p {
        font-weight: bold;
        font-family: 'Garamond';
        font-size: 20px;
        color: #abb8a0;
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
        font-size: 17px;
        font-family: 'Avenir Next LT Pro Regular', sans-serif;
        margin-left: 1.2em;
        color: black;
        margin-top: 20px;
        margin-bottom: 20px;
    }

    .main-content ul li {
        font-family: 'Avenir Next LT Pro Regular', sans-serif;
        margin-left: 8px;
        margin-top: 12px;
        margin-bottom: 12px;
    }

    :root {
        --gradient-line-width: 100%; /* Define the width of the gradient line */
    }

    .gradient-line::before {
        content: '';
        position: absolute;
        top: 54px;
        left: 0px;
        width: var(--gradient-line-width);
        height: 3px;
        background: linear-gradient(to right, rgba(62,121,180,.6) 78%, rgba(200,144,98,1) 23%); 
        border-radius: 10px;
    }

    .additional-column {
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: flex-start;
        padding: 0px;
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
        padding-right: -10px;
        margin-left: 10px;
        position: relative; /* Added to allow for relative positioning */
        top: -20px; /* Moves the date upwards */
    }

    .additional-column span.location {
        font-size: 16px;
        color: rgba(200, 144, 98, 1);
        margin-left: 10px;
        padding-bottom: 17px;
        padding-right: -15px;
        margin-top: 10px;
        position: relative; /* Added to allow for relative positioning */
        top: -10px; /* Moves the location upwards */
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
            background: rgba(62, 121, 180, .2);
            border-radius: 10px;
        }
    }
</style>

<body>
    <!-- Your content here -->
</body>
