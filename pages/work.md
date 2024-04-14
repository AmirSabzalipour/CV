--- 
layout: page
title : Work Experience 
permalink: /portfolio/
subtitle: "" 
feature-img: "assets/img/pexels/travel.jpeg"
position: 2
tags: [Page]
---

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Conversion</title>

<style>
  .education-title {
   font-family: sans-serif; /* Font family */
   font-size: 1em;
   color: white;
   font-weight: bold;
   }

   // To clear things when we float the element inside nav and ul



.site-header {
  position: absolute;
  top: 2.5px; /* Align the top of the header with the top of the page */
  left: 0%;
  background: rgba(255, 255, 255, .3); /* Background color */
  padding: 5px;
 background: var(--background);
  display: flex; /* Assuming .site-header uses flexbox */
  justify-content: space-between;
  height: auto; 
  width: 95%;
  border-radius: 22px;
  background-color: #f7f4f4;
  transform: translateX(3%);
  margin-top: 0px;
  position: relative;
  background-image: url('assets/img/header/machin.jpg');
  background-size: cover; /* Ensure image covers the entire header */
  

  .nav-container {
    position: absolute;
    top: 20%;
    left: 50%;
    transform: translate(-50%, -50%); /* Center content within container */
    margin-left: auto;
    opacity: 0.1;
  }
   
   .separator {
    user-select: none;
    opacity: 0;

    &:first-child {
      display: none;
    }
  }

  a {
    color: var(--header-link);
  }

  .avatar {
    height: 3em;
    width: 3em;
    float: left;
    margin-top: -13px;
    border-radius: 0.2em;
    margin-right: 0.5em;
    padding: 10px 10px;

  }

  .site-title {
    float: left;
    color:#3e5069;
    font-weight: bold;
    font-family: $font-family-logo;
    font-size: 1.3em;
    margin-top: 2px;
    margin-right: 20px;
    margin-left: 10px;
    margin-bottom: 10px;

  }
  #pull {
    margin-left: 30px 30px 50px 80px; /* Adjust margin for the hamburger icon */
  }
}



nav {
  display: flex; /* Make the navigation bar a flex container */
  justify-content: center;
  list-style: none;
  margin:0px;
  
  
  
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
    line-height: 1.5;
    float: right;
    text-align: right;
    display: block;
    
  
  li { 
   margin-right: 0.4em;
    display: inline;
    padding: 5px;
    float: left;
    font-weight: bold;
    
  

  a {font-size: 1em; padding: 0px 0px;
    color: var(--link);
    font-weight: normal;
    &:hover {
      color:blue;
    }

    &#pull {
      i {
        margin-top: 20px;
        margin-right: 0px;
        float: right;
      }
    }
  }
}
  }
}


html[data-theme="dark"] nav ul li a {
  color: black; /* Change the color to black in dark mode */
}


@media (min-width: $break) {
  nav {
    flex-wrap: wrap; /* Allow navigation items to wrap on smaller screens */
  }
  a#pull {
    display: none;
  }

  .navbar-label-with-icon {
    display: none;
  }
}



@media screen and (max-width: $break) {
  nav ul li a {
    font-size:1.2em; /* Your desired font size */;
  }
  .site-header {
    width: 100%; /* Set the width to 100% to occupy the full width of the viewport */
    border-radius: 0px;
  }
  .site-title {
   margin-right: 35px; 
   margin-left: 20px;
    float: none; 
    font-size: 1em;
  }
  
    
  nav {
    display: flex;
    height: auto;

    .separator {
      display: none !important;
    }

    ul {
      width: 100%;
      overflow: hidden;

      /* fade out, then shrink */
      transition: opacity .25s 0s, font-size .25s 0s;
      transition-delay: 0s;

      &.hide {
        font-size: 0;
        margin: 0;
        opacity: 0;
        padding: 0;
      }
    }

    li {
      width: 100%;
      text-align: center;
      font-size: 0.7em;
      position: relative;
      background-color: var(--background);
      backdrop-filter: brightness(0.2);

      &:nth-of-type(1n) {
        background-color: var(--background);
       
      }
     
      a {
        width: 100%;
        margin: 0;
        display: block;
        font-size: .9em;
      }

    }
    .clear {
      *zoom: 1;
    
      &:after {
        clear: both;
      }
    
      &:before,
      &:after {
        content: " ";
        display: table;
      }
    }
    
  }
  #text-box {
    overflow-wrap: break-word;
    max-width: 100%;
  }
}
#pull i {
  color:darkolivegreen; /* Set the color of the hamburger icon */
}

#pull {
  /* Adjust padding around the hamburger icon */
  margin-top: 20px;
  margin-right: 4px;
  margin-left: 2px;
}

/* Adjust margin for the hamburger icon */
#pull i {
  margin-top: 4px;
  margin-right: 4px;
  margin-left: 2px;
  float: right;

}
.nav-container {
  /* Existing styles for .nav-container... */
  display: flex; /* Assuming .nav-container uses flexbox */
  justify-content: flex-start; /* Align navigation to the left within .site-header */
  justify-content: center;  /* Center navigation within .site-header */
  justify-content: flex-end; /* Align navigation to the right within .site-header */
}
</style>
</head>
<body>
<section>
<div style="display: inline-block; padding-right: 20px;">
    <span style="font-size: 21px; color: rgba(130, 150, 90, 0.7); font-weight: bold; font-family: 'Avenir Next LT Pro';">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I) Computational Research on Materials
    </span>
</div>
<br><br>


<div style="background-color: white; border: 0.6px solid gray; border-radius: 20px; padding: 5px 20px; width: 99%; box-shadow: -8px -2px 2px rgba(128, 128, 128, 0.6);">
  <div style="margin-left: 1em; margin-top: 1em;">
    <p style="font-size: 10.8px; color: rgba(0, 0, 0, 1); margin-bottom: 1;"></p>
   <div style="display: flex; align-items: center;">
    <p style=" font-size: 19px;color:#2171b5; margin-right: 10px;">Postdoctoral Researcher,</p>
    <p class="italic" style="margin-right: 10px;"><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">University of Antwerp,</span><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, 1);"> October 2021 - January 2023</span></p>
</div>


</div>
  <ul style="font-size: 22px; color: #2171b5; font-family: 'Avenir Next LT Pro', sans-serif;"> 
    <li>Investigation of the effect of magnetic defects on topological materials' electronic properties.</li>
    <li>Designing topological heterostructures with the aim of minimizing electrical energy losses.</li>
    <li>Modeling and simulation of electrical resistivity at the micron and nanometer scales in Python.</li>
  </ul>
</div>
 


<div style="background-color: white; border: 0.6px solid gray; border-radius: 20px; padding: 5px 20px; width: 99%; box-shadow: -8px -2px 2px rgba(128, 128, 128, 0.6);">
  <div style="margin-left: 1em; margin-top: 1em;">
    <p style="font-size: 10.8px; color: rgba(0, 0, 0, 1); margin-bottom: 1;"></p>
   <div style="display: flex; align-items: center;">
    <p style=" font-size: 19px;color:#2171b5; margin-right: 10px;">Doctoral Researcher,</p>
    <p class="italic" style="margin-right: 10px;"><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">University of Antwerp,</span><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, 1);"> March 2017 - October 2021</span></p>
</div>

</div>
    <ul style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);"> 
      <li>Modelling materials at the atomic level using VASP simulation package on an HPC cluster.</li>
      <li>Studding how substrate and gate voltage affect quantum transport in thin films of materials.</li>
      <li>Conducting numeric and analytical computations utilizing the Wolfram Language and Python.</li>
      <li>Analysis, visualization, scientific writing, and publishing the result.</li>
    </ul>
  </div>




<div style="background-color: white; border: 0.6px solid gray; border-radius: 20px; padding: 5px 20px; width: 99%; box-shadow: -8px -2px 2px rgba(128, 128, 128, 0.6);">
  <div style="margin-left: 1em; margin-top: 1em;">
    <p style="font-size: 10.8px; color: rgba(0, 0, 0, 1); margin-bottom: 1;"></p>
   <div style="display: flex; align-items: center;">
    <p style=" font-size: 19px;color:#2171b5; margin-right: 10px;">Visiting Researcher,</p>
    <p class="italic" style="margin-right: 10px;"><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">Institute for Research in Fundamental Sciences, Tehran, Iran, </span><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, 1);"> February 2016 - February 2017</span></p>
</div>

</div>
  <ul style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">       <li>Investigation of the effects of multiple electron scattering on electric current behavior.</li>
      <li>Statistical and dynamical analysis of semiconductors under thermodynamic fluctuations.</li>
    </ul>
  </div>




<div style="background-color: white; border: 0.6px solid gray; border-radius: 20px; padding: 5px 20px; width: 99%; box-shadow: -8px -2px 2px rgba(128, 128, 128, 0.6);">
  <div style="margin-left: 1em; margin-top: 1em;">
    <p style="font-size: 10.8px; color: rgba(0, 0, 0, 1); margin-bottom: 1;"></p>
   <div style="display: flex; align-items: center;">
    <p style=" font-size: 19px;color:#2171b5; margin-right: 10px;">Visiting Researcher,</p>
    <p class="italic" style="margin-right: 10px;"><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">Uppsala University, Uppsala, Sweden, </span><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, 1);"> October 2015 - January 2016</span></p>
</div>

</div>
  <ul style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">       <li>Using Quantum Espresso to model 2D nanomaterials, such as self-consistent forces, stress calculations, and electronic properties such as band gap values.</li>
    </ul>
  </div>

<br>
<section>
<div style="display: inline-block; padding-right: 20px;">
    <span style="font-size: 21px; color: rgba(130, 150, 90, 0.7); font-weight: bold; font-family: 'Avenir Next LT Pro';">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; II) Optical Design
    </span>
</div>
<br><br>

<div style="background-color: white; border: 0.6px solid gray; border-radius: 20px; padding: 5px 20px; width: 99%; box-shadow: -8px -2px 2px rgba(128, 128, 128, 0.6);">
  <div style="margin-left: 1em; margin-top: 1em;">
    <p style="font-size: 10.8px; color: rgba(0, 0, 0, 1); margin-bottom: 1;"></p>
    <div style="display: flex; align-items: center;">
      <p style=" font-size: 19px;color:#2171b5; margin-right: 10px;">Research Engineer,</p>
      <p class="italic" style="margin-right: 10px;"><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">University of Antwerp, Antwerp, Belgium, </span><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, 1);">January 2020 - March 2021</span></p>
    </div>
  </div>
   <ul style="font-size: 17px;"> <!-- Change the font-size here -->
    <li>Developing alpha and beta prototypes for optical setups. For example, I designed and developed a Schlieren imaging system, which is depicted on my <a href="https://www.youtube.com/channel/UC0ghSST2dX-Yt1UBAKqMLZA" style="color: #4682B4;">YouTube</a> channel.</li>
  </ul>
</div>



<div style="background-color: white; border: 0.6px solid gray; border-radius: 20px; padding: 5px 20px; width: 99%; box-shadow: -8px -2px 2px rgba(128, 128, 128, 0.6);">
  <div style="margin-left: 1em; margin-top: 1em;">
    <p style="font-size: 10.8px; color: rgba(0, 0, 0, 1); margin-bottom: 1;"></p>
    <div style="display: flex; align-items: center;">
      <p style=" font-size: 19px;color:#2171b5; margin-right: 10px;">Optical Design Engineer,</p>
      <p class="italic" style="margin-right: 10px;"><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">Institute for Advanced Studies in Basic Science, Zanjan, Iran, </span><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, 1);">January 2014 - September 2015</span></p>
    </div>
  </div>
  <ul style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">     <li>Designing and constructing optical setups to demonstrate optical phenomena to the public. Several optical phenomena demonstrated include holography, polarization, interference, diffraction, and dispersion, among others.</li>
  </ul>
</div>


<br>
<section>
<div style="display: inline-block; padding-right: 20px;">
    <span style="font-size: 21px; color: rgba(130, 150, 90, 0.7); font-weight: bold; font-family: 'Avenir Next LT Pro';">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; III) Material Characterization, Optical Metrology
    </span>
</div>
<br><br>


<div style="background-color: white; border: 0.6px solid gray; border-radius: 20px; padding: 5px 20px; width: 99%; box-shadow: -8px -2px 2px rgba(128, 128, 128, 0.6);">
  <div style="margin-left: 1em; margin-top: 1em;">
    <p style="font-size: 10.8px; color: rgba(0, 0, 0, 1); margin-bottom: 1;"></p>
    <div style="display: flex; align-items: center;">
      <p style=" font-size: 19px;color:#2171b5; margin-right: 10px;">Research Assistance,</p>
      <p class="italic" style="margin-right: 10px;"><span style="font-family: 'Avenir Next LT Pro';font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, .8);">Univeristy of Tehran, Tehran, Iran, </span><span style="font-family: 'Avenir Next LT Pro";font-variant: small-caps; text-transform: lowercase; font-size: 18px;color: rgba(174, 198, 207, 1);">May 2008 - August 2009</span></p>
     </div>
  </div>
 <ul style="font-size: 17px; font-family: 'Avenir Next LT Pro'> <!-- Change the font-size here -->
      <li>Interferometric image processing to measure thin film surface roughness.</li>
      <li>Producing optical components with $\lambda$/4 flatness, and interferometric surface characterization.</li>
      <li>Atomic Force Microscopy characterization of thin films.</li>
 </ul>
</div>

