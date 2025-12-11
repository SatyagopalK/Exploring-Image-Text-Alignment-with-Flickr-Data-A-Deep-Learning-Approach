# Exploring Image-Text Alignment with Flickr Data: A Deep Learning Approach  
**Academic Project | Jan 2025 – Apr 2025**

---

## 📌 Project Overview
Developed an **Image Caption Generator** using the **Flickr8k dataset**, enabling automatic generation of descriptive captions for images. The project integrates **computer vision** and **natural language processing**, aligning image features with textual descriptions.

---

## 🖼️ Dataset
- **Dataset Used:** Flickr8k (8,000 images with multiple captions each)  
- **Preprocessing Steps:**  
  - Resized images  
  - Tokenized and padded captions  
  - Built vocabulary from dataset  

---

## 🧠 Model Architecture
The model combines:

1. **VGG16 CNN (pre-trained)** – for extracting image features  
2. **LSTM Network** – to generate sequential captions  
3. **Image-Text Alignment** – merges CNN features with LSTM hidden states for accurate caption generation  

---

## 🔧 Training & Optimization
- Trained on **Flickr8k training set**  
- Optimized using:  
  - **Cross-entropy loss**  
  - Learning rate scheduling  
  - Early stopping  
- Evaluated with **BLEU scores** to measure caption quality  

---

## 🎯 System Functionality
- Users can upload an image  
- AI generates a descriptive caption in real time  
- Demonstrates alignment between **image features and textual context**  

---

## 🌱 Impact
- Automates image description for:  
  - Accessibility tools (visually impaired users)  
  - Image retrieval and search  
  - Social media automation  
- Showcases deep learning for **multimodal tasks** combining vision and NLP  
