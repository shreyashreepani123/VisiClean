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
📊 Results & Performance Analysis
Metric	Value
Accuracy	90.95%
Precision	99.52%
Recall	91.23%
F1 Score	95.19%
🔍 Interpretation
✅ High Accuracy (90.95%)
Indicates that the model performs consistently well in distinguishing between similar and dissimilar images across the dataset.
🎯 Exceptional Precision (99.52%)
This is a standout metric — it means almost every image predicted as a duplicate is actually correct.
👉 Very low false positives, which is critical in real-world systems (e.g., avoiding wrong matches in search or recommendations).
🔁 Strong Recall (91.23%)
The model successfully detects most of the actual duplicate/similar images.
👉 Only a small portion of true matches are missed.
⚖️ Balanced F1 Score (95.19%)
Shows an excellent balance between precision and recall.
👉 Confirms the model is both accurate and reliable, not biased toward one metric.
🚀 Overall Performance Insight

The model demonstrates highly reliable similarity detection, with extremely high precision and strong recall, making it well-suited for real-world applications like image deduplication, search systems, and recommendation engines.
⚡ Why This Project Stands Out
Combines transformer-based vision + similarity learning
Uses hashing for speed and scalability
Avoids brute-force comparison
Inspired by real-world systems like:
Image search engines
Face recognition
E-commerce recommendation systems

