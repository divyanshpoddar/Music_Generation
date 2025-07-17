# 🎵 Music Generation using Machine Learning

A Capstone Project submitted in partial fulfillment of the B.Tech degree at VIT Bhopal University.

This project explores multiple hybrid deep learning architectures for automated music generation. The goal is to generate coherent and expressive musical compositions by learning patterns from classical MIDI datasets.

## 🚀 Project Highlights

- 🔁 **Hybrid Models Implemented**:
  - `Transformer + LSTM`
  - `VAE + GAN`
  - `CNN + LSTM`
  - `RNN + Attention`
  - `Diffusion + Transformer`
  - `Simple LSTM (Baseline)`

- 🧠 **Deep Learning Frameworks**:
  - TensorFlow / Keras
  - PyTorch (optional extensions)
  - Custom music processing with `music21`, `pretty_midi`, `mido`

- 🎼 **Dataset**:  
  - Over 200 MIDI files of Chopin’s Nocturnes and Preludes
  - Preprocessing includes pitch normalization, note encoding, and time-series windowing

- 🧰 **Key Libraries Used**:
  - `TensorFlow`, `Keras`, `NumPy`, `Pandas`
  - `music21`, `pretty_midi`, `mido`
  - `Matplotlib`, `Seaborn` for visualization

## 🧪 Model Training & Evaluation

- Optimizer: `Adamax`, loss: `sparse categorical crossentropy`
- Training: up to 15 epochs with early stopping
- Evaluation metrics include:
  - Melodic coherence
  - Harmonic consistency
  - Human listening scores
- Visualizations:
  - Training curves
  - Note distribution histograms
  - t-SNE plots of learned sequences

## 🎧 Music Generation Pipeline

1. Extract MIDI notes and chords using `music21`
2. Encode sequences and normalize
3. Train selected model
4. Generate sequences with temperature sampling
5. Export to `.mid` format with expressive post-processing (e.g., sustain pedaling)

## 💡 Applications

- 🎮 Game Soundtracks  
- 🎬 Film & TV Background Scores  
- 🧘 Meditation & Therapy Music  
- 📱 Smart Assistants & IoT Background Scoring  
- 🛠️ AI-based Composition Assist Tools
