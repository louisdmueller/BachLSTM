# BachLSTM

This is the course project for the seminar "Neural Networks". I tried implementing an LSTM that generates music by Bach.

## Model Details:
- Dropout
- Embeddings
- Attention
- Bidirectional
- AdamW as optimizer
- ReduceLrOnPlateau as scheduler

## Project Details:
- Trained exclusively on Bach piano pieces
- Train-val split: 90/10
- Uses padding, packing, and batching

## Results:
- The model can generate notes and complete pieces
- Often generates notes in the same key as the given initial melody
- Sometimes, the completion of the initial melody by the model is discernible
- Unfortunately, the music generated is minimally melodic or not melodic at all.
  - The reason for this is probably that the data is too complex.
  - A simpler approach would have been to let the model generate only melodies instead of complete pieces of music.
