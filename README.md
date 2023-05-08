# BioSoundTutorial

This repository contains 5 tutorials that should be done in succession.  These tutorials show how to use BioSound to extract sound features from natural sounds: animal and human vocalizations, music or enviromental sounds.  BioSound represents sounds using classical bioacoustical features such as the frequency of energy quartiles in the power spectrum as well as features used more specifically for speech and animal calls such as the fundamental, the pitch saliency and formants.  Biosounds also include a spectrogram and a modulation power spectrum.

The tutorials will show you how to analize an ensemble of sounds that have been pre-cut (as separate wav files for example) in units that are relevant for the analysis. 

The BioSound object is in theunissenlab/soundsig.  You can pip install the latest version directly from github:

`pip install -e git+https://github.com/theunissenlab/soundsig.git@master#egg=soundsig`
Or you can also directly attempt the pip install from PyPi

`pip install soundsig`.   

The 5 Jupyter tutorials contain additional information on the methodology.

## Running in Google colab (work in progress)

The [tutorial can be run in colab](https://colab.research.google.com/github/theunissenlab/BioSoundTutorial/blob/master/BioSound_Tutorial_Colab.ipynb). This notebook will clone this repository for the necessary data files.
