---
layout: page
title: Work Experience
permalink: /portfolio/
subtitle: ""
feature-img: "assets/img/pexels/"
position: 1
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
            border-radius: 30px 30px 30px 30px;
            padding: 10px  10px 7px 10px ;
            margin:0;
            box-shadow: 0 2px 2px white;
            position: relative; 
            display: flex;/* Ensure relative positioning for absolute positioning of pseudo-element */
    }

     .textbox::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%; /* Take up the full width of the box */
            height: 8px; /* Thickness of the strip */
            /* background: linear-gradient(to right, rgba(65, 105, 225, 0.8) 30%, rgba(65, 105, 225, 0.5) 70%);  */ */
            border-radius: 20px 20px 20px 20px; /* Ensure rounded corners on the top */
     }

    .textbox h3 {
            color: #333;
            font-size: 12px;
            margin-bottom: 10px;
    }

    .textbox p {
            color: #666;
            font-size: 16px;
            line-height: 1.6;
    }

     @media only screen and (max-width: 600px) {
    /* Adjust styles for small screens */
    .textbox {
        flex-direction: column;
        align-items: flex-start;
        padding: 10px;
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
        font-size: 9px;
        margin-left: 0;
        margin-top: 5px;
    }

    /* Remove styles for additional column */
    .textbox .additional-column {
        display: none;
    }
}

</style>
@media only screen and (max-width: 600px) {
        /* Adjust title size for small screens */
        .small-screen-title {
            font-size: 20px; /* Adjust as needed */
        }
    }
</style>

<section>
    <div class="textbox" style="display: flex;justify-content: space-between; border: .5px solid  white;  background-color: white; line-height: 40px; margin-bottom: -5px;">
        <div style="margin-left: 0.4em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: -5px;">
            <i class="fa fa-briefcase" style="margin-right: 5px; color: #abb8a0;"></i> <!-- Icon -->
            <p class="small-screen-title" style="font-weight: bold; font-family: 'Garamond'; font-size: 23px; color: #abb8a0; margin-left: .2em;"> Computational Research on Materials</p> <!-- Text -->
        </div>
    </div>
    <!-- Other content -->
</section>




<section>


<div class="textbox" style="display: flex;justify-content: space-between; border: .5px solid  white;  background-color: white; line-height: 40px; margin-bottom: -5px;">
    <div style="margin-left: 0.4em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: -5px;">
        <i class="fa fa-briefcase" style="margin-right: 5px; color: #abb8a0;"></i> <!-- Icon -->
        <p style="font-weight: bold; font-family: 'Garamond'; font-size: 23px; color: #abb8a0; margin-left: .2em;"> Computational Research on Materials</p> <!-- Text -->
    </div>
</div>

<div class="textbox" style="display: flex;justify-content: space-between; line-height: 90px; margin-bottom: 10px;">
    <div class="main-content" style="flex: 1;">
    <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;"> <p style=" font-weight: bold; font-family: 'Garamond'; font-size: 20px; color: rgba(62,121,180,1);margin-left: .9em;"> Postdoctoral Researcher</p>
        </div>
    <ul style="font-size: 15px; font-family: 'AvenirNext LT Pro Regular', sans-serif; margin-left: 1.7em; color: black;">
    <li style="margin-bottom: 10px;">Python-based modeling and simulation of electrical resistivity at micron and nanometer scales.</li>
    <li style="margin-bottom: 10px;">Developing computational models to optimize energy loss in quantum topological materials, incorporating statistical, electrical, quantum and topological features.</li>
    </ul>
     <div style="::before; content: ''; position: absolute; top: 47px; left:10px; width: 98%; height: 2.5px; background: linear-gradient(to right, rgba(62,121,180,.6)  79.5%, rgba(200,144,98,1)  20.5%); 
    border-radius: 10px 10px 10px 10px;"> </div>
     </div>
<div class="additional-column" style="width: 160px; height: 100px; position: relative;">
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray; position: absolute; top: 0; left: 0;"> </span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200,144,98,1); position: absolute; top: 5px; left: 10px;">10.2021 - 06.2023</span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200,144,98,1); position: absolute; top: 50px; left: 6px;">University of Antwerp</span></p>
</div>
 </div>


<div class="textbox" style="display: flex;justify-content: space-between; line-height: 90px; margin-bottom: 10px;">
    <div class="main-content" style="flex: 1;">
    <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;"> <p style=" font-weight: bold; font-family: 'Garamond'; font-size: 20px; color: rgba(62,121,180,1);margin-left: .9em;"> Doctoral Researcher</p>
        </div>
    <ul style="font-size: 15px; font-family: 'AvenirNext LT Pro Regular', sans-serif; margin-left: 1.7em; color: black;">
    <li style="margin-bottom: 10px;">Simulations of materials using VASP package on a High-performance computing (HPC) cluster.</li>
    <li style="margin-bottom: 10px;">Conducting numeric and analytical computations utilizing the Wolfram Language and Python.</li>
    <li style="margin-bottom: 10px;">Data visualization, analysis of observed behavior, and reporting findings to scientific journals.</li>
    </ul>
    <div style="::before; content: ''; position: absolute; top: 47px; left: 10px; width: 98%; height: 3px; background: linear-gradient(to right, rgba(62,121,180,.6)  80%, rgba(64, 130, 109,1) 20%); 
    border-radius: 10px 10px 10px 10px;"> </div>
     </div>
<div class="additional-column" style="width: 160px; height: 100px; position: relative;">
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray; position: absolute; top: 0; left: 0;"> </span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(64, 130, 109,1); position: absolute; top: 5px; left: 10px;">03.2017 - 10.2021</span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(64, 130, 109,1); position: absolute; top: 50px; left: 6px;">University of Antwerp</span></p>
</div>
 </div>


<div class="textbox" style="display: flex;justify-content: space-between; line-height: 90px; margin-bottom: 10px;">
    <div class="main-content" style="flex: 1;">
    <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;"> <p style="font-weight: bold; font-family: 'Garamond';  font-size: 20px; color: rgba(62,121,180,1);margin-left: 0.9em;"> Visiting Researcher</p>
        </div>
    <ul style="font-size: 15px; font-family: 'AvenirNext LT Pro Regular', sans-serif; margin-left: 1.7em; color: black;">
<li style="margin-bottom: 10px;">Statistical and dynamical study of anomalous electrical properties of semiconductors under thermodynamic fluctuation and with magnetic   impurities.</li>
<p style="font-size: 14px; color:gray; margin-top: 10px;">IPM : Institute for Research in Fundamental Sciences, Tehran</p> 
    </ul>
    <div style="::before; content: ''; position: absolute; top: 47px; left: 10px; width: 98%; height: 3px; background: linear-gradient(to right, rgba(62,121,180,.6)  80.7%, rgba(200,144,98,1)  19.3%); 
    border-radius: 10px 10px 10px 10px;"> </div>
     </div>
<div class="additional-column" style="width: 160px; height: 100px; position: relative;">
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray; position: absolute; top: 0; left: 0;"> </span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color:rgba(200,144,98,1) ; position: absolute; top: 5px; left: 10px;">03.2016 - 02.2017</span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200,144,98,1);  position: absolute; top: 50px; left: 10px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;IPM</span></p>
</div>
 </div>

<div class="textbox" style="display: flex;justify-content: space-between; line-height: 90px; margin-bottom: 10px;">
    <div class="main-content" style="flex: 1;">
    <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;"> <p style="font-weight: bold; font-family: 'Garamond'; font-size: 20px; color: rgba(62,121,180,1);margin-left: 0.9em;"> Visiting Researcher</p>
        </div>
    <ul style="font-size: 15px; color: black;margin-left: 1.7em; font-family: 'Avenir Next LT Pro', sans-serif;">
       <li style="margin-bottom: 10px;">Nanoscale simulations of 2D materials using Quantum ESPRESSO package.</li>
    </ul>
    <div style="::before; content: ''; position: absolute; top: 47px; left: 10px; width: 98%; height: 3px; background: linear-gradient(to right, rgba(62,121,180,.6)  80.5%, rgba(64, 130, 109,1)  20.5%); 
    border-radius: 10px 10px 10px 10px;"> </div>
     </div>
<div class="additional-column" style="width: 160px; height: 100px; position: relative;">
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray; position: absolute; top: 0; left: 0;"> </span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(64, 130, 109,1); position: absolute; top: 5px; left: 10px;">10.2015 - 02.2016</span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(64, 130, 109,1); position: absolute; top: 50px; left: 10px;">Uppsala University</span></p>
</div>
 </div>

<br>
<br>
<br>
<br>
<br>

<section>
<div class="textbox" style="display: flex;justify-content: space-between; border: .5px solid  white;  background-color: white; line-height: 40px; margin-bottom: -5px;">
    <div style="margin-left: 0.4em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: -5px;">
        <i class="fa fa-briefcase" style="margin-right: 5px; color: #abb8a0;"></i> <!-- Icon -->
        <p style="font-weight: bold; font-family: 'Garamond'; font-size: 23px; color: #abb8a0; margin-left: .2em;"> Optical Design</p> <!-- Text -->
    </div>
</div>
<div class="textbox" style="display: flex;justify-content: space-between; line-height: 90px; margin-bottom: -20px;">
    <div class="main-content" style="flex: 1;">
    <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;"> <p style="font-weight: bold; font-family: 'Garamond'; font-size: 20px; color: rgba(62,121,180,1);margin-left: 0.9em;">Research Engineer</p>
        </div>
    <ul style="font-size: 15px; color: black; font-family: 'Avenir Next LT Pro', sans-serif;margin-left: 1.7em;">
     <li style="margin-bottom: 10px;">Developing alpha and beta prototypes for optical setups. For example, I designed and developed a Schlieren imaging system, which is depicted on my <a href="https://www.youtube.com/channel/UC0ghSST2dX-Yt1UBAKqMLZA" style="color: #4682B4;">YouTube</a> channel.</li>
    </ul>
    <div style="::before; content: ''; position: absolute; top:40px; left: 10px; width: 98%; height:3px; background: linear-gradient(to right, rgba(62,121,180,.6)  80.5%, rgba(200,144,98,1)  20.5%); 
    border-radius: 10px 10px 10px 10px;"> </div>
     </div>
   <div class="additional-column" style=" padding-top: -8px; width: 180px;height: 100px;">
      <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray;"> </span></p>
    <p><span style="font-family: 'Avenir Next LT Pro';position: absolute; top: 10px; left: 720px; font-size: 15px; color: rgba(200,144,98,1);">01.2020 - 03.2021</span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200,144,98,1);position: absolute; top: 60px; left: 720px;">University of Antwerp</span></p>
 </div>
</div>

<br>

<div class="textbox" style="display: flex;justify-content: space-between;  line-height: 90px; margin-bottom: -5px;">
    <div class="main-content" style="flex: 1;">
        <div style="margin-left: 0em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 9px;"> <p style="font-weight: bold; font-family: 'Garamond'; font-size: 20px; color: rgba(62,121,180,1);margin-left: 0.9em;">Optical Design Engineer</p>
        </div>
    <ul style="font-size: 15px;margin-left: 1.7em; color: black; font-family: 'Avenir Next LT Pro', sans-serif;">
     <li style="margin-bottom: 10px;">Designing and constructing optical setups to demonstrate optical phenomena to the public. Several optical phenomena demonstrated include holography, polarization, interference, diffraction, and dispersion, among others.</li>
     <p style="font-size: 14px; color:gray; margin-top: 10px;">IASBS : Institute for Advanced Studies in Basic Sciences, Zanjan, Iran</p> 
    </ul>
    <div style="::before; content: ''; position: absolute; top:40px; left: 10px; width: 98%; height:3px; background: linear-gradient(to right, rgba(62,121,180,.6) 80.5%, rgba(64, 130, 109,1)  20.5%); 
    border-radius: 10px 10px 10px 10px;"> </div>
     </div>
   <div class="additional-column" style=" padding-top: -8px; width: 160px;height: 100px;">
      <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray;"> </span></p>
    <p><span style="font-family: 'Avenir Next LT Pro';position: absolute; top: 10px; left: 720px; font-size: 15px; color: rgba(64, 130, 109,1);">01.2014 - 09.2015</span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(64, 130, 109,1);position: absolute; top: 60px; left: 720px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;IASBS</span></p>
 </div>
</div>

<br>
<br>
<br>
<br>
<br>

<section>

<div class="textbox" style="display: flex;justify-content: space-between; border: .5px solid  white;  background-color: white; line-height: 40px; margin-bottom: -5px;">
    <div style="margin-left: 0.4em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: -5px;">
        <i class="fa fa-briefcase" style="margin-right: 5px; color: #abb8a0;"></i> <!-- Icon -->
        <p style="font-weight: bold; font-family: 'Garamond'; font-size: 23px; color: #abb8a0; margin-left: .2em;"> Material Characterization, Optical Metrology</p> <!-- Text -->
    </div>
</div>
<div class="textbox" style="display: flex;">
    <div class="main-content" style="flex: 1;">
        <div style="margin-left: 0em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 9px;"> <p style="font-weight: bold; font-family: 'Garamond'; font-size: 20px; color: rgba(62,121,180,1);margin-left: 0.9em;">Research Assistance</p>
        </div>
    <ul style="font-size: 15px; color: black;margin-left: 1.7em; font-family: 'Avenir Next LT Pro', sans-serif;">
     <li style="margin-bottom: 10px;">Image processing of interferometric patterns to measure roughness of thin films.</li>
    <li style="margin-bottom: 10px;">Atomic Force Microscopy characterization of thin films.</li>
     <li style="margin-bottom: 10px;">Producing optical components with &lambda;/4 flatness, and interferometric surface characterization.</li>
    </ul>
    <div style="::before; content: ''; position: absolute; top:40px; left: 10px; width: 98%; height:3px; background: linear-gradient(to right, rgba(62,121,180,.6) 80.5%, rgba(200,144,98,1)  20.5%); 
    border-radius: 10px 10px 10px 10px;"> </div>
     </div>
   <div class="additional-column" style=" padding-top: -8px; width: 160px;height: 100px;">
      <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray;"> </span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; position: absolute; top: 10px; left: 720px;color: rgba(200,144,98,1);">05.2008 - 08.2009</span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200,144,98,1);position: absolute; top: 60px; left: 720px;">Univeristy of Tehran</span></p>
 </div>
</div>


<br>
<br>
<br>
<br>
<br>
<section>

<div class="textbox" style="display: flex;justify-content: space-between; border: .5px solid  white;  background-color: white; line-height: 40px; margin-bottom: -5px;">
    <div style="margin-left: 0.4em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: -5px;">
        <i class="fa fa-briefcase" style="margin-right: 5px; color: #abb8a0;"></i> <!-- Icon -->
        <p style="font-weight: bold; font-family: 'Garamond'; font-size: 23px; color: #abb8a0; margin-left: .2em;"> Teaching</p> <!-- Text -->
    </div>
</div>
<div class="textbox" style="display: flex;justify-content: space-between; line-height: 90px; margin-bottom: 10px;">
    <div class="main-content" style="flex: 1;">
    <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;"> <p style="font-weight: bold; font-size: 20px; color: rgba(62,121,180,1); font-family: 'Garamond'; margin-left: .9em;"> Lab Instructor and Research Teacher</p>
        </div>
    <ul style="font-size: 15px;margin-left: 1.7em; color: black; font-family: 'Avenir Next LT Pro', sans-serif;">
     <li style="margin-bottom: 10px;"> Supervising students for the International Young Physicists' Tournament (IYPT).</li>
    <li style="margin-bottom: 10px;">Teaching students the relevant practical theories and how to use laboratory equipment.</li>
    </ul>
    <div style="::before; content: ''; position: absolute; top: 47px; left:10px; width: 98%; height: 3px; background: linear-gradient(to right, rgba(62,121,180,.6)  75%, rgba(64, 130, 109,1)  25%); 
    border-radius: 10px 10px 10px 10px;"> </div>
     </div>
<div class="additional-column" style="width: 220px; height: 100px; position: relative;">
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray; position: absolute; top: 0; left: 0;"> </span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(64, 130, 109,1); position: absolute; top: 5px; left: 30px;">09.2010 - 08.2011</span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(64, 130, 109,1); position: absolute; top: 50px; left: 0px;">Mofid High School, Tehran</span></p>
</div>
 </div>

<div class="textbox" style="display: flex;justify-content: space-between; line-height: 90px; margin-bottom: 10px;">
    <div class="main-content" style="flex: 1;">
    <div style="margin-left: 0.1em; margin-top: -0.1em; display: flex; align-items: center; margin-bottom: 5px;"> <p style="font-weight: bold; font-size: 20px; color: rgba(62,121,180,1); font-family: 'Garamond'; margin-left: .9em;"> Tutor</p>
        </div>
    <ul style="font-size: 15px; font-family: 'AvenirNext LT Pro Regular', sans-serif; margin-left: 1.7em; color: black;"> 
  <li> Tutoring high school students in math and physics.</li>
    </ul>
    <div style="::before; content: ''; position: absolute; top: 47px; left:10px; width: 98%; height: 3px; background: linear-gradient(to right, rgba(62,121,180,.6)  75%, rgba(200,144,98,1)  25%); 
    border-radius: 10px 10px 10px 10px;"> </div>
     </div>
<div class="additional-column" style="width: 220px; height: 100px; position: relative;">
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: gray; position: absolute; top: 0; left: 0;"> </span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color: rgba(200,144,98,1); position: absolute; top: 5px; left: 30px;">09.2009 - 08.2010</span></p>
    <p><span style="font-family: 'Avenir Next LT Pro'; font-size: 15px; color:rgba(200,144,98,1); position: absolute; top: 50px; left: 0px;">Institute of Khaje Nasir, Tehran</span></p>
</div>
 </div>
































