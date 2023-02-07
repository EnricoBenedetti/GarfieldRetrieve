# GarfieldRetrieve

## Project and Project Work in Text Mining, Data Mining and Big Data Analytics

Author: Enrico Benedetti

Email: enrico.benedetti5 [at] studio.unibo.it


## What's this

This is a project done for the course "Text Mining, Data Mining and Big Data Analytics" at my university. It consists of the cleaning of a new dataset containing
based on the ever-updating [file](http://john.ccac.rwth-aachen.de:8000/ftp/dilbert/garfield.txt) containing transcripts of Garfield Strips. Only raw text and no speech bubble 
annotation unfortunately. Maybe this could be done using computer vision techniques.

In the notebook I perform:
- dataset creation and processing
- a short analysis of the text data
- unsupervised topic mining using latent semantic analysis
- building of a comic strip retrieval system based on deep metric learning (unsupervised) w/ sentence transformers.
- comparison of some approaches (latent semantic index baseline, pre-trained ST, fine-tuned ST w/ triplet loss, fine-tuned ST w/ multiple negatives loss).

Feel free to use this code to build a Garfield search engine or whatever!
