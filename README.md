# Probing a Chess-LLM: Exploring what happens inside a Chess-Playing Language Model

Silvano Vento Maddonni - 247370 - silvano.maddonni@studenti.unitn.it

## About the project
This is the project for the ANLP course.

In this project we test how a LLM performs in computer chess, an area that doesn’t directly belong to language, and explore and try to understand how it is internally reasoning.

The project is composed of three parts. In part one, after handling the conversion and tokenization of the data, the model is set up to be able to predict the next move and a probing is conducted on its ability to keep predictions inside legal moves. In the second part, the focus is shifted towards probing the model by analyzing different attention heatmaps of the layers and heads. In the last part, a
dedicated probing classifier is trained on top of the model to check the ability of the model to have an internal understanding of the position of the pieces.


## Files
The folder contains the jupyter notebook (`project_(c).ipynb`) that can be used to replicate the work done. 

In addition: the `src` folder (also in zip for convenience of uploading it) contains some python files and utils that are used. 

The `vocab.txt` is used by tokenizer. The `papers` folder contains the three main papers used as base/inspiration. 

PDFs of Project Report and the Presentation are included.



## Datasets
3 datasets have been used. One is downloaded inside the notebook from HuggingFace. The other two are:

`lichess_db1.pgn`

`lichess_db2.pgn`


## Usage
Inside the jupyter notebook there are comments to guide the execution. 

In the first cells there are instructions to install packages needed and to load the needed files. 
