# Multimodal Fake News Detector

### **Project Overview**

This project aims to develop a multimodal fake news detection system that analyzes both textual and visual content to determine the veracity of news articles. By combining natural language processing (NLP) for text analysis and computer vision techniques for image analysis, the system will provide more robust fake news detection compared to unimodal approaches.


### **Key Features:**

- Multimodal analysis combining text and image data
- Deep learning models for feature extraction from both modalities
- Fusion techniques to combine textual and visual information
- Binary classification (real vs fake news) output
- Evaluation against benchmark datasets

### **Dataset Requirements:**

The project will utilize datasets containing:

- [https://github.com/entitize/Fakeddit](https://github.com/entitize/Fakeddit)

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

### Project Structure

```
multimodal-fake-news-detector/
├── data/                   # Dataset storage
├── notebooks/              # Jupyter notebooks for exploration
├── src/
│   ├── text_processing/    # Text analysis modules
│   ├── image_processing/   # Image analysis modules
│   ├── fusion/             # Multimodal integration
│   └── utils/              # Helper functions
├── models/                 # Saved model weights
├── requirements.txt        # Python dependencies
└── README.md               # This file
```

**Author:**

- **Name:** Milan
- **Github:** MilanKok98

Feel free to contribute or report issues
