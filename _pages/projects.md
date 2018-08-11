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

* Finding the Suspect using Variational Autoencoder and Gaussian Process [**link**](https://github.com/sidsriv/Bayesian-methods-for-machine-learning/blob/master/week6-final_project/Coursera%20BMML%2C%20Final%20project.ipynb)
  * This is the final project as part of the course "Bayesian Methods for machine learning"
  * In this project I tried to implement an app for crating facial composite that will be able to construct desired faces without explicitly providing databases of templates. I applied Variational Autoencoders and Gaussian processes for this task.
