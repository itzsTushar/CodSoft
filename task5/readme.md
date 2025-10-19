# ✍️ Handwritten Text Generation using RNN (Task 5)
DEMO : https://youtu.be/TZ-PakhlX3c
This project focuses on generating **realistic handwritten text** using a **Recurrent Neural Network (RNN)** architecture inspired by *Alex Graves’* paper *“Generating Sequences with Recurrent Neural Networks.”* The model learns to produce smooth, human-like handwriting by predicting pen stroke sequences conditioned on textual input.

Due to **limited GPU access on Google Colab**, the model was trained for **12 epochs**. The setup used **PyTorch**, an **LSTM-based network**, and a **Negative Log-Likelihood loss function** optimized with **Adam**. Even within this constraint, the model successfully demonstrated coherent handwriting generation and strong alignment between text and generated strokes.

### 📘 Credits  
- **Base Repository:** [Handwriting Synthesis by Swechha Singh](https://github.com/swechhasingh/Handwriting-synthesis.git)  
- **Research Paper:** *Generating Sequences With Recurrent Neural Networks* by **Alex Graves**  
  - [arXiv Link](https://arxiv.org/abs/1308.0850) | [DOI](https://doi.org/10.48550/arXiv.1308.0850)  
  - Demonstrates how LSTM networks can generate complex sequences with long-range dependencies, applied to both text and online handwriting synthesis.  

**Author:** Tushar Sharma  

