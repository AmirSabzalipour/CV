---
layout: page
title: Projects
permalink: /projects/
subtitle: ""
feature-img: "assets/img/pexels/travel.jpeg"
position: 5
tags: [Page]
---

<style>
  .education-title {
    font-family: sans-serif; /* Font family */
    font-size: 1em;
    color: white;
    font-weight: bold;
  }

  body {
    margin: 0;
    padding: 10px;
    background-image: url('assets/img/header/education.jpg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover; /* Ensure the background image covers the entire viewport */
  }

  h1 {
    font-family: Cambria, serif;
    color: white;
    text-align: center;
    margin-bottom: 20px;
  }

  section {
    margin: 20px;
    padding: 10px;
    background-color: #f9f9f9;
    border-radius: 5px;
    border: 1px solid #ddd;
  }

  h2 {
    font-family: Arial, sans-serif;
    font-size: 1.5em;
    color: #333;
    margin-top: 20px;
  }

  ul {
    list-style-type: disc;
    padding-left: 40px;
    margin: 10px 0;
  }

  li {
    margin-bottom: 10px;
    line-height: 1.6;
    font-family: Georgia, serif;
    color: #555;
  }

  ul ul {
    list-style-type: circle;
    margin-left: 20px;
  }
</style>

<h1 class="education-title">Projects</h1>

<section>
  <h2>Sentiment Analysis using Machine Learning Algorithms</h2>
  <ul>
    <li>Analyzed text data including Mobile Apps, Twitter, Yelp, and product Reviews.</li>
    <li>Trained and evaluated various deep learning and classical machine learning models.</li>
    <li>Achieved sentiment accuracy of 48% (neutral), 71% (negative), and 81% (positive).</li>
  </ul>

  <h2>Automatic Detection of Machine-Generated Text</h2>
  <ul>
    <li>Analyzed web-scraped data (Reviews, Poems, Tweets, News) in English and Dutch.</li>
    <li>Achieved 97% accuracy in detecting machine-generated text using ensemble learning.</li>
    <li>The top-performing classical model surpassed deep learning models by a significant margin.</li>
  </ul>

  <h2>Developing an Age-Appropriate Rating System for Podcasts</h2>
  <ul>
    <li>Developed a topic modeling system for podcasts, integrating BERTopic and LMMs.</li>
    <li>Model directly identifies topics without post-processing, reducing computation time.</li>
    <li>Developed an age rating system for podcasts based on identified topics and subtopics.</li>
  </ul>

  <h2>Evaluating GPT Model Performance Using Perplexity</h2>
  <ul>
    <li>Used a GPT model with GPT2Tokenizer, trained on Christopher Marlowe’s books.</li>
    <li>Evaluated on: TinyShakespeare, a science fiction dataset, and a nonsensical dataset.</li>
    <li>Results of Perplexity scores:
      <ul>
        <li>252 (TinyShakespeare)</li>
        <li>339 (science fiction)</li>
        <li>221,642.7 (nonsense)</li>
      </ul>
    </li>
    <li>Conclusion: Performs well on familiar text, struggles with new genres, fails on nonsense.</li>
  </ul>
</section>






