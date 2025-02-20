# msc-thesis-audio-states
Accompanying code to MSc thesis on "Leveraging Audio States & Transitions for Improved Track Sequencing in Music Streaming Sessions"

## Requirements
- Python 3
- Tensorflow 2.0
- Tensorflow Probability 0.8
- matplotlib, pandas, scipy, numpy, seaborn
- faiss

## Files
``state-extraction/`` contains all code for Chapter 3 on Extracting and Understanding Audio States & Transitions, with the exception of the counterfactual track-reranking experiment.

**data_prep.ipynb** - Code to prepare dataset used for experiments

**full_analysis.ipynb** - Code for state extraction analysis

``track-sequencing/`` contains all code for Chapter 4 on Leveraging Audio States & Transitions for Track Sequencing.

**reranking-data-prep.ipynb** - Code to prepare dataset used for experiments

**state-extraction.ipynb** - Code for state extraction for sessions in all datasets, and perform counterfactual re-ranking experiment

**audio-attribute-prediction.ipynb** - Code to build and run top audio attribute prediction classifier

**track-reranking.ipynb** - Code for preferred state prediction and track re-ranking algorithm, plus analysis

## Dataset
All experiments are done on a subset of Spotify's [Music Streaming Sessions Dataset](https://arxiv.org/abs/1901.09851), which can be obtained [here](https://www.aicrowd.com/challenges/spotify-sequential-skip-prediction-challenge).
