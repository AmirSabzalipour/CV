---
layout: page
title: Education
permalink: /about/
feature-img: "assets/img/pexels/travel.jpeg"
position: 1
tags: [Page]
---


<style>
  .education-title {
   font-family: sans-serif; /* Font family */
   font-size: 1em;
   color: white;
   font-weight: bold;
   }

   
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

<h1 class="education-title" style="font-family: Cambria, serif;"></h1>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }}</title>
  <!-- Add any additional meta tags, stylesheets, or scripts here -->
  <link rel="stylesheet" href="assets/custom.css"> <!-- Correct path to your custom CSS file -->
  <style>
    /* Reset default margin and padding */
    body {
      margin: 0;
      padding: 10px;
      background-image: url('assets/img/header/education.jpg');
      background-repeat: no-repeat;
      background-position: center center;
      background-size: 1100px 300px; /* Ensure the background image covers the entire viewport */
    }



  /* Define your CSS styles here */
  /* Add your CSS styles if needed */
</style>
<section style="color: lapislazuli; font-size: 15px; font-weight: bold;">
  <h2></h2>
  <div style="margin-top: 1em;">
    <div style="background-color: white; border: 0.4px solid gray; border-radius: 20px; padding: 6px 8px; width: 100%; box-shadow: 0px -5px 2px gray;">
      <div style="font-size: 12px; color: black;">
        <strong>09.2023 Present</strong> | <em>Master of Digital Text Analysis</em> | Faculty of Arts, University of Antwerp
        <p style="font-size: 11px;">
          Applying Natural Language Processing (NLP), Machine Learning (ML), and Data Science to analyze text, audio, and video content from various sources, including web content, books, audiobooks, and speeches.
        </p>
      </div>
    </div>
    <div style="margin-top: 1em; background-color: white; border: 0.4px solid gray; border-radius: 20px; padding: 6px 8px; width: 100%; box-shadow: 0px -5px 2px gray;">
      <div style="font-size: 12px; color: black;">
        <strong>03.2017 10.2021</strong> | <em>Ph.D. in Physics</em> | University of Antwerp, Belgium
        <p style="font-size: 11px;">
          Thesis title: <a href="https://repository.uantwerpen.be/docstore/d:irua:8696" style="color: lapislazuli;">"Charge Transport in Magnetic Topological Insulators"</a>
        </p>
      </div>
    </div>
    <div style="margin-top: 1em; background-color: white; border: 0.4px solid gray; border-radius: 20px; padding: 6px 8px; width: 100%; box-shadow: 0px -5px 2px gray;">
      <div style="font-size: 12px; color: black;">
        <strong>09.2011 04.2014</strong> | <em>M.Sc. in Physics</em> | Institute for Advanced Studies in Basic Science, Zanjan, Iran
        <p>
          Studying Spin-Orbit interaction's effect on the anisotropic properties of materials.
        </p>
      </div>
    </div>
    <div style="margin-top: 1em; background-color: white; border: 0.4px solid gray; border-radius: 20px; padding: 6px 8px; width: 100%; box-shadow: 0px -5px 2px gray;">
      <div style="font-size: 12px; color: black;">
        <strong>09.2003 04.2008</strong> | <em>B.Sc in Physics</em> | University of Tehran, Tehran
        <p>
          Thin film fabrication by Physical Vapor Deposition (PVD) techniques.
        </p>
      </div>
    </div>
  </div>
</section>


