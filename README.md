# SPEECH-RECOGNITION-SYSTEM

**COMPANY**: CODTECH IT SOLUTIONS

**NAME** : SAMUDRALA SAI MRUDHULA

**INTERN ID** : CT120FHK

**DOMAIN** : ARTIFICIAL INTELLIGENCE

**DURATION** : 8 WEEKS

**MENTOR** : NEELA SANTHOSH 


## DESCRIPTION :

**Project Overview** :
This project implements a Speech Recognition System using Wav2Vec2, a state-of-the-art transformer-based model developed by Facebook AI (Meta) for Automatic Speech Recognition (ASR). The main objective of this project is to convert spoken audio into accurate and readable text using deep learning techniques.

Traditional speech recognition models rely on handcrafted features and large amounts of labeled audio data. However, Wav2Vec2 significantly improves upon this by leveraging self-supervised learning to train on vast amounts of unlabeled speech data. This approach allows it to recognize various accents, noise conditions, and diverse speaking styles more effectively.

To make this system interactive and user-friendly, we integrate Gradio, a Python library that provides a simple web-based interface. With Gradio, users can upload or record audio files and see the real-time transcription output without needing to install or configure complex software.

This project is particularly useful for applications requiring high-accuracy speech-to-text conversion, such as voice assistants, transcription services, and accessibility tools for the hearing impaired.

**Tools & Libraries Used** :

To build this speech recognition system, the following tools and libraries are utilized:

1. Gradio – Provides an intuitive web interface for testing the model with recorded or uploaded audio files.
  
2. Librosa – A powerful Python library used for audio processing, feature extraction, and waveform analysis.
   
3. Torch (PyTorch) – A deep learning framework that supports efficient model inference and computations.

4. Transformers (Hugging Face) – Provides access to the pre-trained Wav2Vec2ForCTC model, allowing for high-quality speech recognition.

These tools collectively enable the system to process speech input, extract key features, and generate accurate transcriptions.

**Applications** :

Speech recognition technology has a wide range of real-world applications, including but not limited to:

1. Voice Assistants – Widely used in AI-powered voice assistants such as Siri, Google Assistant, and Alexa, allowing users to interact with devices using natural speech.

2. Transcription Services – Converts speech from meetings, lectures, interviews, and podcasts into written text, making information easier to store and access.

3. Accessibility Solutions – Assists the hearing impaired by providing real-time captions and text-based communication options.

4. Voice Commands & Smart Devices – Enables users to control smart home devices, cars, and mobile applications hands-free using voice commands.

**How It Works**

1️. Load and preprocess the audio input using Librosa.

2️. Use a pre-trained Wav2Vec2 model for feature extraction and transcription.

3️. Display the recognized text using Gradio's web-based UI.

## OUTPUT:

![Image](https://github.com/user-attachments/assets/2063f9dc-eec4-4b1d-84ca-0a4071172ad4)
