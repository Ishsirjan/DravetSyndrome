# SCN1A Projection and Expression Analysis

This project explores simulated and real circuit dysfunction and recovery in Dravet syndrome using gene expression images and projection metadata from the Allen Brain Atlas. It demonstrates how machine learning can distinguish pathological vs. rescued brain states based on ISH features, projection patterns, and graph metrics.

## 🔍 Overview
- Simulated Dravet-like damage on ISH images of SCN1A expression
- Generated "healed" counterparts to represent therapeutic recovery
- Extracted intensity, texture, and edge features
- Built classifiers (Random Forest, XGBoost) to identify recovery states
- Used real SCN1A-Cre vs. wild-type tracer projection data to classify circuit disruption
- Performed graph-based simulations and ML on global efficiency and density

## 📁 Structure
SCN1A-Connectivity-Project/
├── notebooks/                # Main analysis notebooks
├── data/                    # Allen Brain Atlas projection CSVs
├── images/                  # Sample ISH brain slices
├── models/                  # Trained models (optional)
├── utils/                   # Feature extraction helpers
├── README.md
├── requirements.txt
└── LICENSE

## 🧪 Data Sources
- Allen Mouse Brain Connectivity Atlas (projection data): https://connectivity.brain-map.org/projection
- Allen Mouse Brain Atlas (gene expression): https://mouse.brain-map.org/
- SCN1A gene filter for expression images and then downloaded the coronal mouse images- 77340528 

## ✨ Tools Used
- Python, Jupyter Notebooks
- scikit-learn, xgboost
- numpy, pandas, matplotlib, seaborn
- networkx, opencv

## 📊 Output
- Accuracy >90% in image-based and projection-based classification
- Feature importance rankings
- Visualizations of projection strength and image intensity

## 📚 Citation
If you use this work, please cite the Allen Institute and original data authors and code authors
