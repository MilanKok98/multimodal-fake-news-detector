# Multimodal Fake News Detector
### **Project Overview**

This project aims to develop a multimodal fake news detection system that analyzes both textual and visual content to determine the veracity of news articles. By combining natural language processing (NLP) for text analysis and computer vision techniques for image analysis, the system will provide more robust fake news detection compared to unimodal approaches. The project aims to answer the following problem statement: **given an image + headline/body text, predict if the news is real or fake.**

### **Key Features:**
- Multimodal analysis combining text and image data
- Deep learning models for feature extraction from both modalities
- Fusion techniques to combine textual and visual information
- Binary classification (real vs fake news) output
- Evaluation against benchmark datasets

### **Dataset Requirements:**

Th[e project will utilize datasets containing:
- https://github.com/KaiDMML/FakeNewsNet)

### **Technical Approach:**

- Text Processing Pipeline:
  - NLP preprocessing (tokenization, stemming, etc.)
  - Feature extraction using transformers (BERT, RoBERTa) or LSTMs

- Image Processing Pipeline:
  - Image preprocessing and augmentation
  - Feature extraction using CNNs (ResNet, VGG) or vision transformers

- Multimodal Fusion:
  - Early/late fusion strategies
  - Attention mechanisms for cross-modal interaction
  - Decision-level integration

- Classification:
  - Binary classifier trained on combined features
  - Output confidence scores for real/fake prediction

### Future Work
- Expand to multiple languages
- Incorporate social context and propagation patterns
- Develop browser extension for real-time detection
- Improve explainability of model decisions

Author:
- **Name:** Milan
- **Github:** MilanKok98

Feel free to contribute or report issues
