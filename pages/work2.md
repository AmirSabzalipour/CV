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
        color: Black;
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

    .gradient-line::before {
        content: '';
        position: absolute;
        top: 54px;
        left: 0px;
        width: 100%;
        height: 3px;
        background: rgba(62, 121, 180, .2);
        border-radius: 10px;
    }

   .additional-column {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    padding: 0px;
    font-size: 17px;
    width: 160px;
    border-radius: 20px;
    margin-right: -10px;
    position: relative; /* Added to allow for relative positioning */
}

.additional-column span.date {
    font-size: 17px;
    color: rgba(200, 144, 98, 1);
    margin-top: -25px; /* Adjusted to bring the date closer to the location */
    padding-right: -10px;
    margin-left: -20px;
    position: relative; /* Added to allow for relative positioning */
    top: -20px; /* Moves the date upwards */
}

.additional-column span.location {
    font-size: 16px;
    color: rgba(200, 144, 98, 1);
    margin-left: -20px;
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
            background: rgba(62, 121, 180, .2);;
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
                    <li style="list-style-type: none; color: #a5a65f ;font-size: 15px;">Key Responsibilities</li>
                     <li>Python-based simulation of materials properties at micron and nanometer scales.</li>
                    <li>Developing computational models to optimize energy loss in quantum topological materials, incorporating statistical, electrical, quantum, and topological features.</li>
                </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date" style="margin-top: -70px;" >10.2021 - 06.2023</span>
                <span class="location" style="margin-top: 10px;">University of Antwerp</span>
            </div>
        </div>
        <br>

<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Doctoral Researcher</p>
                </div>
                <ul>
                    <li style="list-style-type: none;  color: #a5a65f ;font-size: 15px;">Key Responsibilities</li>
                    <li>High-performance computing (HPC) and Simulation with VASP package.</li>
                    <li>Mathematical modeling and computer simulation based on Mathematica and Python.</li>
                    <li>Data visualization, analysis and reporting findings to scientific journals.</li>
                </ul>
                <div class="gradient-line"></div>
              </div>
            <div class="additional-column">
                <span class="date" style="margin-top: -80px;">03.2017 - 10.2021</span>
                <span class="location" style="margin-left: -25px; margin-top: 15px;">University of Antwerp</span>
            </div>
        </div>
        <br>

<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Visiting Researcher</p>
                </div>
                <ul>
                <li style="list-style-type: none;  color: #a5a65f ;font-size: 15px;">Key Responsibilities</li>
                <li>Statistical and dynamical study of anomalous electrical properties of semiconductors under thermodynamic fluctuation and with magnetic impurities.</li>
                 <li style="font-family: 'Avenir Next LT Pro'; font-weight: normal; font-size: 14px; color: gray; margin-top: 20px;padding-bottom: 30px;">IPM : Institute for Research in Fundamental Sciences, Tehran</li>
                </ul>
                <p style="font-family: 'Avenir Next LT Pro'; font-weight: normal; font-size: 14px; color: gray; margin-top: -20px;"></p>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date" style="margin-top: -70px;">03.2016 - 02.2017</span>
                <span class="location" style="margin-left: 20px; margin-top: 10px;">IPM</span>
            </div>
        </div>
        <br>

<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Visiting Researcher</p>
                </div>
                <ul>
                     <li style="list-style-type: none;  color: #a5a65f ;font-size: 15px;">Key Responsibilities</li>
                    <li>Nanoscale simulations of 2D materials using Quantum ESPRESSO package.</li>
                </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date" style="margin-top: -5px;">10.2015 - 02.2016</span>
                <span class="location" style="margin-top: 8px;">Uppsala University</span>
            </div>
        </div>
    </section>

<br>
<br>

<section>
        <div class="textbox">
            <div class="title-container">
                <i class="fa fa-briefcase"></i>
                <p>Optical Design</p>
            </div>
        </div>
        <br>
        <div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Research Engineer</p>
                </div>
                <ul>
                    <li style="list-style-type: none;  color: #a5a65f ;font-size: 15px;">Key Responsibilities</li>
                     <li>Developing alpha and beta prototypes for optical setups. For example, I designed and developed a Schlieren imaging system, which is depicted on my <a href="https://www.youtube.com/channel/UC0ghSST2dX-Yt1UBAKqMLZA" style="color: #4682B4;">YouTube</a> channel.</li>
                                   </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date" style="margin-top: -30px;" >01.2020 - 03.2021</span>
                <span class="location" style="margin-top: 20px;">University of Antwerp</span>
            </div>
        </div>
        <br>
        
<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Optical Design Engineer</p>
                </div>
                <ul>
                    <li style="list-style-type: none; color: #a5a65f ;font-size: 15px;">Key Responsibilities</li>
                    <li>Designing and constructing optical setups to demonstrate optical phenomena to the public. Several optical phenomena demonstrated include holography, polarization, interference, diffraction, and dispersion, among others.</li>
                     </ul>
                <div class="gradient-line"></div>
              </div>
            <div class="additional-column">
                <span class="date" style="margin-top: -40px;">01.2014 - 09.2015</span>
                <span class="location" style="margin-left: 25px; margin-top: 15px;">nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;IASBS</span>
            </div>
        </div>
       
 <br>
 <br>




<section>
        <div class="textbox">
            <div class="title-container">
                <i class="fa fa-briefcase"></i>
                <p>Material Characterization, Optical Metrology</p>
            </div>
        </div>
        <br>
        <div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Research Assistance</p>
                </div>
                <ul>
                    <li style="list-style-type: none;  color: #a5a65f ;font-size: 15px;">Key Responsibilities</li>
                     <li>Image processing of interferometric patterns to measure roughness of thin films.</li>
                      <li>Atomic Force Microscopy characterization of thin films.</li>
                       <li>Producing optical components with &lambda;/4 flatness, and interferometric surface characterization.</li>
                                   </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date" style="margin-top: -30px;" >05.2008 - 08.2009</span>
                <span class="location" style="margin-top: 20px;">Univeristy of Tehran</span>
            </div>
        </div>
      <br>
     <br>



<section>
        <div class="textbox">
            <div class="title-container">
                <i class="fa fa-briefcase"></i>
                <p>Teaching</p>
            </div>
        </div>
        <br>
        <div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Lab Instructor and Research Teacher</p>
                </div>
                <ul>
                    <li style="list-style-type: none;  color: #a5a65f ;font-size: 15px;">Key Responsibilities</li>
                     <li>Supervising students for the International Young Physicists' Tournament (IYPT).</li>
                      <li>Teaching students the relevant practical theories and how to use laboratory equipment.</li>
                                   </ul>
                <div class="gradient-line"></div>
            </div>
            <div class="additional-column">
                <span class="date" style="margin-top: -30px;" >09.2010 - 08.2011</span>
                <span class="location" style="margin-top: 20px;">Mofid High School, Tehran</span>
            </div>
        </div>
        <br>
      
<div class="textbox2">
            <div class="main-content">
                <div style="margin-left: 0.1em; margin-top: -0.6em; margin-bottom: 0.1em; display: flex; align-items: center; margin-bottom: 5px;">
                    <p>Tutor</p>
                </div>
                <ul>
                    <li style="list-style-type: none; color: #a5a65f ;font-size: 15px;">Key Responsibilities</li>
                     <li>Tutoring high school students in math and physics.</li>
                 </ul>    
                <div class="gradient-line"></div>
              </div>
            <div class="additional-column">
                <span class="date" style="margin-top: -40px;">09.2009 - 08.2010</span>
                <span class="location" style="margin-left: 25px; margin-top: 15px;">Institute of Khaje Nasir, Tehran</span>
            </div>
        </div>
       
 <br>
 <br>
