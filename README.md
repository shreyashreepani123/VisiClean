🌟 VisiClean — Intelligent Image Duplicate Detection System

🚀 SNN + Vision Transformer + Deep Hashing + FAISS

VisiClean is a scalable and high-performance image similarity detection system designed to identify duplicate or visually similar images using advanced deep learning and similarity search techniques. The system combines Siamese Neural Networks, Vision Transformers, Deep Hashing, and FAISS to deliver fast and accurate results on large-scale datasets.

🔥 Key Highlights
🧠 Siamese Neural Network for similarity learning
🤖 Vision Transformer for advanced feature extraction
⚡ Deep Hashing for compact representations
🚀 FAISS for ultra-fast similarity search
📊 Strong evaluation using multiple performance metrics
📂 Scalable to large datasets
🧠 Model Architecture

The system integrates multiple modern deep learning components:

🔹 Siamese Neural Network (SNN)
Uses shared weights to process image pairs/triplets
Learns similarity between images
Ensures similar images are closer in embedding space
🔹 Vision Transformer (ViT)
Backbone model for feature extraction
Captures global relationships in images
More powerful than traditional CNNs for complex patterns
🔹 Deep Hashing
Converts high-dimensional embeddings into compact hash codes
Reduces storage requirements
Enables faster similarity comparison
🔹 FAISS (Similarity Search Engine)
Stores embeddings efficiently
Performs fast nearest neighbor search
Retrieves Top-K similar images in milliseconds
⚙️ Tech Stack
Python
PyTorch
TIMM (Vision Transformer models)
FAISS
Scikit-learn
Matplotlib
📂 Dataset
Structured image dataset (class-based organization)
Used for:
Training via triplet sampling
Testing similarity detection
🏋️ Training Details
Parameter	Value
Model Backbone	Vision Transformer
Training Type	Siamese Network
Loss Function	Triplet Loss
Optimizer	Adam
Learning Rate	3e-5
Epochs	30
Embedding Size	128
🔍 Similarity Search
Embeddings indexed using FAISS
Performs nearest neighbor search
Retrieves most similar images efficiently
Suitable for large-scale datasets
📊 Model Evaluation

The model is evaluated using standard metrics:

Accuracy → Overall correctness
Precision → Correct duplicate detections
Recall → Ability to detect all duplicates
F1 Score → Balance between precision and recall
📈 Graph Analysis
🔴 ROC Curve
Plots True Positive Rate vs False Positive Rate
Measures model discrimination ability
AUC score indicates performance
🔵 Precision-Recall Curve
Plots Precision vs Recall
Useful for imbalanced datasets
Helps choose optimal similarity threshold

