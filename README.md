# 🧠✨ MultiEmbed: Unified Text, Image, and Multimodal Embeddings

**MultiEmbed** is a collection of notebooks demonstrating how to generate and compare feature embeddings from text, images, and combinations of both. This project showcases the power of pretrained models in transforming raw data into meaningful numerical representations for downstream applications like similarity search, classification, and retrieval.

## 1️⃣ Text Encoding with BERT

📄 **Module**: `text_encoding.ipynb`  
🚀 **Model**: `bert-base-uncased` (Hugging Face Transformers)  
📌 **Highlights**:

- Tokenize text and extract [CLS] embeddings.
- Compare sentence similarity using cosine similarity.
- Understand how BERT captures semantic information in embeddings.

📈 **Applications**: Semantic search, sentence classification, clustering.

## 2️⃣ Image Encoding with ResNet-50

🖼️ **Module**: `image_encoding.ipynb`  
🚀 **Model**: `resnet50` (TorchVision)  
📌 **Highlights**:
- Preprocess images and extract 2048-dimensional feature vectors.
- Normalize and compare image embeddings using cosine similarity.
- Demonstrates visual similarity detection with CNN features.

📈 **Applications**: Image retrieval, clustering, object recognition.

## 3️⃣ Multimodal Embeddings with CLIP

🖼️ + 📄 **Module**: `multimodal_encoding.ipynb`  
🚀 **Model**: `openai/clip-vit-base-patch32` (Hugging Face)  
📌 **Highlights**:

- Encode images and corresponding text into a shared semantic space.
- Compare embeddings for semantic alignment.
- Includes an image captioning component using `vit-gpt2`.

📈 **Applications**: Cross-modal retrieval, captioning, zero-shot classification.