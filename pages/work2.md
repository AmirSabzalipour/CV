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
        color:rgba(62, 121, 180, .5);
    }

    .title-container p {
        font-weight: bold;
        font-family: 'Avenir Next LT Pro', serif;
        font-size: 20px;
        color: rgba(62, 121, 180, 1);
        margin-left: .1em;
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
            display: flex;
            align-items: center;
            width: 99%; ;
    }

    .main-content {
    flex: 1;
    display: flex; 
    flex-direction: column; 
    align-items: flex-start;
    }

    .main-content p {
    font-weight: bold;
    font-family: 'Avenir Next LT Pro';
    font-size: 17px;
    color:  #87ceeb;   
    margin-left: 1em;
    margin-top: 20px; /* Adjust vertical position */
    margin-bottom: -10px; /* Adjust vertical position */
}

.main-content ul {
   font-size: 16px;
    font-family: 'Avenir Next LT Pro Regular', sans-serif;
    margin-left: 1.7em;
     color: black;
    margin-top: 20px; 
    margin-bottom: 10px; 
}

    .main-content ul li {
        margin-left: 12px;
    }

    .gradient-line::before {
        content: '';
        position: absolute;
        top: 52px;
        left: 10px;
        width: 98%;
        height: 3px;
        background: rgba(62, 121, 180, .5);
        /* linear-gradient(to right, rgba(200,144,98,.6) 80%,  rgba(200,144,98,.6) 20%);  */
        border-radius: 10px;
    }

.additional-column {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    padding: 10px;
    width: 170px;
    height: auto;
}

.additional-column p,
.additional-column span {
    font-family: 'Avenir Next LT Pro';
    font-size: 15px;
    color: inherit;

}

/* Assuming you want to position the date span exactly at the top of the additional-column */
.additional-column span.date {
    position: absolute;
    top: 20px; /* Positions the date at the very top of the additional-column */
    left: 750px; /* Aligns the date to the left edge of the additional-column */
    margin-bottom: 10px; 
    font-family: 'Avenir Next LT Pro'; 
    font-size: 16px; 
    color:rgba(220,144,98,1);/* Adds some space below the date */
}


/* Other elements in the additional-column can remain as they are, unless you need to adjust their positions as well */
.additional-column p:not(.date) {
    margin-top:-3px; 
     color:rgba(220,144,98,1);
     font-size: 17px; 
    /* Adds some space above the first paragraph after the date */
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
<br>
<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: 0.1em;  margin-bottom: 0.1em;display: flex; align-items: center; margin-bottom: 5px;"><br>
                    <p>Postdoctoral Researcher</p>
                </div >
                <ul>
                    <li >Python-based modeling and simulation of electrical resistivity at micron and nanometer scales.</li>
                    <li>Developing computational models to optimize energy loss in quantum topological materials, incorporating statistical, electrical, quantum and topological features.</li><br>
                </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <p></p>
                <p><span class="date">10.2021 - 06.2023</span></p>
                <p><span class="location; font-size: 40px; ">University of Antwerp</span></p>
            </div>
        </div>
