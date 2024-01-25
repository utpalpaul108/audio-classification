# Audio Classification using Deep Learning

## Overview

Deep learning-based audio classification. The goal of this project is to classify audio samples into predefined categories using deep neural networks. This can be useful for tasks such as speech recognition, music genre classification, and more.

## Dataset

Here I have used Z by HP Unlocked Challenge 3 - Signal Processing dataset from [kaggle](https://github.com/JovianHQ/opendatasets) to count the number of Capuchinbird calls within a given clip.


## Installation

<div style="padding-bottom:10px"><b>STEP 00 :</b> Clone the repository</div>

```bash
https://github.com/utpalpaul108/audio-classification
```
<div style="padding-top:10px"><b>STEP 01 :</b> Create a virtual environment after opening the repository</div>

Using Anaconda Virtual Environments

```bash
conda create -n venv python=3.10 -y
conda activate venv
```
Or for Linux operating system, you can use that

```bash
python3.10 -m venv venv
source venv/bin/activate
```

<div style="padding-top:10px; padding-bottom:10px"><b>STEP 02 :</b> Install the dependencies</div>

```bash
pip install -r requirements.txt
```
For downloading the Kaggle dataset, place the `kaggle.json` file (Kaggle API credentials) in your root directory.

Finally, run the notebook.