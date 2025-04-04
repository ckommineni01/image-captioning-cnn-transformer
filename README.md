# 🖼️ Image Caption Generation using CNN and Transformers

This project explores an image captioning system that generates meaningful textual descriptions for input images using deep learning. It integrates **Convolutional Neural Networks (CNNs)** with **Recurrent Neural Networks (RNNs)** and attention mechanisms.

---

## 🧠 Overview

- Extract image features using **ResNet50**
- Sequence modeling using **LSTM**
- Dataset: A subset of **Flickr8k** with 500 images
- Implemented caption generation pipeline with tokenizer, vocabulary pruning, and custom data generator
- Trained from scratch using Keras & TensorFlow

---

## 📁 Dataset

- Subset of Flickr8k dataset (first 500 images)
- Each image has multiple reference captions
- Preprocessed with padding, start/end tokens, and vocabulary cleanup

---

## 🧱 Model Architecture

- **CNN Encoder**: ResNet50 to extract feature maps
- **RNN Decoder**: LSTM network that learns the sequence of words
- **Tokenization**: Custom tokenizer with padding and start/end tokens
- **Loss**: Sparse categorical cross-entropy

---

## 🔍 Key Observations

- Model successfully learned to generate basic captions from scratch
- Attention helps focus on important image regions
- Training performance improved over 20+ epochs
- BLEU scores used for evaluation

---

## 🚀 Future Enhancements

- Use **Vision Transformers (ViT)** instead of ResNet50
- Integrate **Transformer-based decoder** instead of LSTM
- Switch to larger datasets (MS COCO, full Flickr8k)
- Streamlit UI for real-time caption generation

---

## 📑 Documentation

📄 [Literature_Review.pdf](./Literature_Review.pdf)

Contains full explanation of methodology, architecture diagrams, model evaluation, and future work.

---

## 👨‍💻 Author

**Chaitanya Krishna Kommineni**  
[LinkedIn](https://www.linkedin.com/in/kchaitanya17/)  
[Portfolio](https://tinyurl.com/ckommineni)
