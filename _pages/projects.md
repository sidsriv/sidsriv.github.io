---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---



{% include base_path %}


Research Projects
====

* Construction and analysis of protein-protein interaction network in Leishmania major
  * Objective:  Comparison of cross study gene expression data (Agilent Microarray) for drug
sensitive and drug resistant L.donovani.
  * Individual Responsibility: Cross-platform normalized gene expressions from different experiments. Calculated Pearson correlation, mutual information score for gene pairs and implemented Principal component analysis, K-means clustering algorithms on normalized datasets.
  * Accomplishment: Performed correlation and mutual information analysis on gene pairs to study pattern similarity in gene expression and further employed cluster algorithms. Normalized 22 gene expression samples from 6 different experiments available in NCBI GEO database.
  * Tools used: Python Scientific stack (Numpy, Pandas, Scikit-learn, Matplotlib), R and Rstudio (Bioconductor)
  

* Hybrid evolutionary approach for Devanagari Handwritten numeral recognition using Convolutional Neural Network
  * Objective: To develop a novel approach for training Convolutional Neural Network using
initial weights based on Genetic Algorithms for fast optimization.
  * Individual Responsibility: Pre-processed 25,000 images of isolated handwritten Hindi characters using binarization, blurring, cropping, size normalization. Implemented vanilla CNN architechture with integrated genetic algorithm optimization
  using python.
  * Accomplishments: Achieved state-of-the-art accuracy of 96.83% on test data using our model and compared our results with standard classification algorithms like logistic regression, random forest and support vector machine.
  * Tools used: Python 3.5, Numpy, Matplotlib, Scikit-learn.


* Self-Attention based BLSTM model for named entity recognition in Drug, Disease and Clinical data
  * Objective: To develop a novel Long short term memory (LSTM) model with multi-head attention to recognise named entities in Biomedical and Clinical data.
  * Individual Responsibility: Developed novel architechture consisting of multi-head attention from transformer network cascaded with Bi-LSTM and conditional Radom Fields (CRF). Used pre-trained word embeddings from PubMed data and tested model on NCBI Disease NER, i2b2-2010 Clinical NER and Drugbank+MedLine Drug NER Datasets.
  * Accomplishments: Achieved result better than state-of-the-art model on Disease dataset (precision score:84.08%) and Clinical dataset (precision:84.63%,recall:83.06%,F-score:83.83%).
  * Tools used: Python 3.5, Tensorflow, Numpy, Scikit-Learn.


* Mining fine grain relations from Wikipedia Infoboxes
  * Objective: To extract fine-grained relations among entity mentions from wikipedia infobox data.
  * Individual Responsibility: Developed script to extract infobox data from article entries present in Wikipedia multistream XML dump. Developed script to scrape vital article list from wikipedia metadata page. Preprocessed relations and attributes present in infobox entries for person, organisation and location infobox types.
  * Tools used: Python 3.5, regex, beatifulsoup, pandas, xml. 
  



Independent Projects (with code)
====

* Finding the Suspect using Variational Autoencoder and Gaussian Process. [**link**](https://github.com/sidsriv/Bayesian-methods-for-machine-learning/blob/master/week6-final_project/Coursera%20BMML%2C%20Final%20project.ipynb)
  * This is the final project as part of the course "Bayesian Methods for machine learning", Part of "Advance machine learning specialization" at Coursera.  
  * In this project I tried to implement an app for crating facial composite that will be able to construct desired faces without explicitly providing databases of templates. I applied Variational Autoencoders and Gaussian processes for this task.
  
* Image Captioning using Deep CNN vision encoder and Language generating RNN. [**link**](https://github.com/sidsriv/Introduction-to-deep-learning/blob/master/week6/week6_final_project_image_captioning_clean.ipynb)
  * This is the final project as part of the course "Introduction to Deep Learning", Part of "Advance machine learning specialization" at Coursera.  
  * I used pre-trained InceptionV3 model for CNN encoder and extracted its last hidden layer as an embedding, these embeddings are used as input to language generating RNN to produce image captions.

* Autonomous driving - Car detection using YOLO algorithm. [**link**](https://github.com/sidsriv/Convolutional-Neural-Networks/blob/master/Week3/Car%20detection%20for%20Autonomous%20driving/Autonomous%2Bdriving%2Bapplication%2B-%2BCar%2Bdetection%2B-%2Bv1.ipynb)
  * This project was the part of 3rd week's assignment of the course "Convolutional Neural networks", part of "Deep Learning Specialization" by Andrew Ng at Coursera.
  * In this project, I implemented the the YOLO (you only look once) algorithm, for box detection and used a pre-trained CNN architecture for object detection.

* Implementations for Modelling and Simulation algorithms in Natural Processes [**link**](https://github.com/sidsriv/Simulation-and-modelling-of-natural-processes)
  * These Scripts are part of Assignments from the course "Modelling and Simultaion in natural processes" by University of Geneva at Coursera
  * I implemented classical mathematical models to Simulate natural processes like Barnes-hut Galaxy simulation, 2-D flow in Cylender, lotka-Volterra prey-predator model and Agent based simulation for traffic lights.
  
* Implementations for Introduction to Natural Language Processing [**link**](https://github.com/sidsriv/Introduction-to-Natural-Language-Processing-UMich-Coursera)
  * These Scripts are part of Assignments from the course "Introduction to Natural language processing" by University of Michigan at Coursera
  * Implemented algorithms like Dependancy Parsing using transition parser, language modelling and Part of Speech Tagging using Hidden Markov models and Word sense disambiguagtion using KNN and SVM.

