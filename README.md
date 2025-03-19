# internAPC


# 🚀 **Gamma-Ray Classification with DINOv2 and Clustering**  

## 📌 **Project Overview**  

This project focuses on **classifying gamma-ray events** detected by the **H.E.S.S. (High Energy Stereoscopic System)** telescopes using **machine learning and deep learning techniques**. The goal is to **distinguish gamma-ray events from background noise** (such as muons and protons) by leveraging:  

- **Unsupervised clustering (HDBSCAN)** to detect event structures  
- **Foundation models (DINOv2 by Meta)** for feature extraction  
- **Dimensionality reduction (UMAP, PCA)** to analyze event distributions  

The work is part of the **ADAPT project**, an initiative led by Prof. Yvonne Becherini, aiming to enhance astrophysical data analysis through **AI-driven classification and feature extraction techniques**.  

---

## 📁 **Repository Structure**  

### **1️⃣ Gamma-Ray Event Classification** (`gamma_classification.ipynb`)  
This notebook performs **event classification** using **HDBSCAN clustering** and shape-based feature extraction:  

- **Data preprocessing**: Cleaning and filtering events based on pixel intensity and telescope detection.  
- **Clustering with HDBSCAN**: Identifying gamma-ray candidates by detecting elliptical patterns.  
- **Ellipticity-based classification**: Assigning events as gamma rays or background based on cluster shape.  
- **Event visualization**: Plotting labeled events to validate the classification.  

🛠 **Key techniques:** Clustering (HDBSCAN), PCA, Ellipticity analysis  

---

### **2️⃣ Feature Extraction with DINOv2** (`feature_extraction_dinov2.ipynb`)  
This notebook focuses on **extracting deep features** from event images using the **DINOv2 vision transformer**:  

- **Raw & Preprocessed Event Images**: Generating event images with and without preprocessing.  
- **Feature extraction with DINOv2**: Obtaining high-dimensional representations of events.  
- **Dimensionality reduction (UMAP, PCA)**: Projecting features into a lower-dimensional space for analysis.  
- **Cluster visualization**: Identifying gamma-ray separability within the feature space.  

🛠 **Key techniques:** Self-supervised learning (DINOv2), Feature embedding, UMAP  

---

## 📊 **Results and Key Findings**  

- **HDBSCAN clustering successfully isolates gamma-ray events** by detecting elliptical shapes, significantly reducing noise.  
- **DINOv2 embeddings reveal structured separability** between gamma-ray and noise events, improving classification robustness.  
- **Combining clustering with deep feature extraction improves event classification accuracy**, demonstrating the power of **self-supervised learning** in astrophysical data analysis.  

---

## 🎯 **Skills Demonstrated**  

✅ **Machine Learning**: Clustering (HDBSCAN), Dimensionality Reduction (PCA, UMAP)  
✅ **Deep Learning**: Vision Transformers (DINOv2), Feature Extraction  
✅ **Data Processing**: Noise filtering, Event labeling, Image transformation  
✅ **Astrophysics**: Gamma-ray detection, Cherenkov telescope data analysis  
✅ **Scientific Computing**: Python (NumPy, Pandas, Matplotlib, Scikit-learn), PyTorch  

---

## 🔥 **Why This Project?**  

This project bridges the gap between **cutting-edge AI and astrophysics**, showcasing how **self-supervised learning and clustering** can significantly **improve gamma-ray detection**. The techniques developed here can be extended to **anomaly detection, time-series analysis, and other domains where pattern recognition in noisy data is crucial**.  


---

## 📬 **Contact & Acknowledgments**  

This work was conducted as part of the **ADAPT project**, under the supervision of **Prof. Yvonne Becherini**.  

💼 **Looking for Software Engineering / Data Science / AI Research Internship opportunities!**  
📧 Feel free to reach out via **gauthier.jeannin@etu.minesparis.psl.eu**  
