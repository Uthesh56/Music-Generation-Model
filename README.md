# MUSIC GENERATION PROJECT USING LSTM

## Overview

Welcome to the Music Generation Project! In this project, we'll explore the fascinating world of music generation using Long Short-Term Memory (LSTM) neural networks. Our primary goal is to generate new classical music compositions inspired by the works of Joseph Haydn, a prominent composer of the classical period.

## Dataset

Our dataset is sourced from the Kunst der Fuge website, providing a collection of classical music compositions by Joseph Haydn. It consists of musical scores in a machine-readable format, such as MusicXML or MIDI, making it suitable for music generation tasks. The dataset includes information about musical notes, chords, and octaves, which are essential for understanding and generating music. [Source Dataset](https://www.kunstderfuge.com/haydn.htm)

## Getting Started

### Prerequisites

Before delving into this exciting project, ensure you have the following prerequisites in place:

- **Python** (version 3.7 or higher)
- **Jupyter Notebook** (optional but highly recommended)

## Data Preprocessing

Before training our LSTM model for music generation, we need to preprocess the musical compositions to create a suitable dataset for training. These preprocessing steps are essential to convert the music data into a format that our model can understand.

### Musical Score Parsing

We initiate data preprocessing by parsing the musical scores. This involves:

1. **File Format Conversion**: Converting the musical scores into a standardized machine-readable format, such as MusicXML or MIDI, while retaining essential information about notes, chords, and octaves.

2. **Score Segmentation**: Dividing the musical scores into individual pieces or compositions. This creates a structured dataset for training, preserving information about musical notes, chords, and octaves.

### Feature Engineering

To facilitate music generation, we perform feature engineering:

1. **Musical Feature Extraction**: Extracting essential musical features from the compositions, including:
   - **Notes**: Identifying individual musical notes, which are the fundamental building blocks of music.
   - **Chords**: Recognizing chord progressions, which are combinations of multiple notes played simultaneously.
   - **Octaves**: Tracking the octave range of each note, allowing for variations in pitch.

These extracted features, encompassing notes, chords, and octaves, will be used as input for the LSTM model.

## LSTM Music Generation Model

We build a Long Short-Term Memory (LSTM) neural network for music generation. LSTM is well-suited for sequence data, making it an ideal choice for generating music. The model will learn the patterns and structures present in Haydn's compositions, including the relationships between notes, chords, and octaves, and generate new music in a similar style.

## Conclusion

- Music generation is a captivating field that blends creativity and machine learning. LSTM models offer a powerful way to generate music by capturing temporal dependencies and musical patterns, including the intricate relationships between notes, chords, and octaves.

- The potential for generating music inspired by Joseph Haydn's compositions, with attention to notes, chords, and octaves, is exciting. This project can lead to the creation of new classical pieces that pay homage to his style while exploring musical nuances at the note and chord level.

- The success of the music generation model will depend on the quality of the dataset, the model architecture, and hyperparameter tuning. Experimentation and fine-tuning, considering the interplay of notes, chords, and octaves, will be key to achieving the best results in generating classical music compositions.
