--- 
layout: page
title : Projects 
permalink: /portfolio/
subtitle: "" 
feature-img: "assets/img/pexels/computer.jpeg"
position: 5
tags: [Page]
---

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NLP Project</title>
  <style>
    section {
      font-size: 12.3px;
    }
    .section-title {
      font-size: 12.3px;
      font-weight: bold;
      color: olivine;
    }
    .tcolorbox {
      background-color: white;
      border: 0.4px solid gray;
      border-radius: 15pt;
      padding: 7pt;
      margin-bottom: 10pt;
      width: 99%;
      box-shadow: -1pt -5pt 2pt gray;
    }
    .bluegray {
      color: bluegray;
    }
  </style>
</head>
<body>
  <section>
    <div class="section-title">Natural Language Processing (NLP)</div>
    <p><strong>Sentiment Analysis</strong></p>
    <p>In this sentiment analysis project, I examined a dataset comprising 50,000 online comments gathered from various platforms, including mobile reviews, Twitter sentiments, and Yelp reviews. The main objective was to classify each comment into one of three categories: positive, negative, or neutral. To accomplish this task, I employed a deep learning model. Below, I briefly provide the details of this project and the applied tools.</p>
    <div class="tcolorbox">
      <p><strong class="bluegray">Exploration of Data:</strong><br>
      <span style="font-size: 10px;">Understanding the structure and types of data, evaluating the statistics of the data, managing missing values and duplicates, addressing data biases, managing outliers, transforming variables, creating new variables</span></p>
      
      <p><strong class="bluegray">Preprocessing Pipeline for Text:</strong><br>
      <span style="font-size: 10px;">Cleaning (removing punctuations, URLs, stop words), lower casing, tokenization, stemming, text lemmatization and numerical vector conversion.</span></p>
      
      <p><strong class="bluegray">Design the Model:</strong><br>
      <span style="font-size: 10px;">Develop the PyTorch architecture for the neural network, specifying the count of layers, nodes, batch size, activation functions, and any other pertinent elements</span></p>
      
      <p><strong class="bluegray">Model Training:</strong><br>
      <span style="font-size: 10px;">Using optimization techniques like SGD or Adam and real-time evaluating the training through monitoring of loss functions</span></p>
      
      <p><strong class="bluegray">Hyperparameter Optimization:</strong><br>
      <span style="font-size: 10px;">Utilizing grid or random search to optimize hyperparameters like learning rate, batch size, epochs, layers, and neuron counts</span></p>
      
      <p><strong class="bluegray">Testing the Model:</strong><br>
      <span style="font-size: 10px;">Using optimal hyper-parameters to adjust the model, then evaluating it on the test set to measure its generalization performance</span></p>
      
      <p><strong class="bluegray">Model Evaluation:</strong><br>
      <span style="font-size: 10px;">Using metrics such as Accuracy, Precision, Recall, F1-score, Confusion Matrix</span></p>
    </div>
  </section>
</body>
