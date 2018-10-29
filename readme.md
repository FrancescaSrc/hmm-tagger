## Introduction

This notebook implements  to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf) using the [Pomegranate](https://github.com/jmschrei/pomegranate) library. Hidden Markov models are used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

## Getting Started

**NOTE:** If you are prompted to select a kernel when you launch a notebook, choose the **Python 3** kernel.

Download a copy of the project from my repository or get the original project from GitHub [here](https://github.com/udacity/hmm-tagger) and then run a Jupyter server locally with [Anaconda](https://www.anaconda.com/download/).

**NOTES:** These steps are **not** required if you are using the project Workspace.

0. (Optional) The provided code includes a function for drawing the network graph that depends on [GraphViz](http://www.graphviz.org/). You must manually install the GraphViz executable for your OS before the steps below or the drawing function will not work.

1. Open a terminal and clone the project repository:
```
$ git clone https://github.com/udacity/hmm-tagger
```

3. Switch to the project folder and create a conda environment (note: you must already have Anaconda installed):
```
$ cd hmm-tagger
hmm-tagger/ $ conda env create -f hmm-tagger.yaml
```

4. Activate the conda environment, then run the jupyter notebook server. (Note: windows users should run `activate hmm-tagger`)
```
hmm-tagger/ $ source activate hmm-tagger
(hmm-tagger) hmm-tagger/ $ jupyter notebook
```

Depending on your system settings, Jupyter will either open a browser window, or the terminal will print a URL with a security token. If the terminal prints a URL, simply copy the URL and paste it into a browser window to load the Jupyter browser. Once you load the Jupyter browser, select the project notebook (HMM tagger.ipynb) and follow the instructions inside to complete the project.

###Extra Tips
Here are some resources you can visit for more insight on the project and improving your skills.

-[Learning POS Tagging & Chunking in NLP](https://medium.com/greyatom/learning-pos-tagging-chunking-in-nlp-85f7f811a8cb)

-[An introduction to part-of-speech tagging and the Hidden Markov Model](https://medium.freecodecamp.org/an-introduction-to-part-of-speech-tagging-and-the-hidden-markov-model-953d45338f24)

-[Part of Speech Tagging with Hidden Markov Chain Models](https://towardsdatascience.com/part-of-speech-tagging-with-hidden-markov-chain-models-e9fccc835c0e)

-[Part-Of-Speech Tagging for Social Media Texts](https://www.researchgate.net/publication/265794799_Part-Of-Speech_Tagging_for_Social_Media_Texts)

-[Part of Speech Tagging](http://web.media.mit.edu/~havasi/MAS.S60/PNLP6.pdf)

-[Part-of-Speech tagging tutorial with the Keras Deep Learning library](https://becominghuman.ai/part-of-speech-tagging-tutorial-with-the-keras-deep-learning-library-d7f93fa05537)
-[Part-of-Speech Tagging for Code-mixed Indian Social Media, Text at ICON 2015](https://arxiv.org/pdf/1601.01195.pdf)
