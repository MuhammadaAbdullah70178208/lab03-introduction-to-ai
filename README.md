lab03/
├── text_features.ipynb      # Part A notebook (Text features)
├── image_features.ipynb     # Part B notebook (Image features)
├── image_utils.py           # Reusable image_to_features extraction script
├── dataset.npz              # 20-sample feature-engineered dataset
├── report.md                # Answers to all discussion questions
└── README.md                # Project documentation and execution instructions
AI-101L: Laboratory 3 — Transforming Textual and Image DataOverviewThis laboratory covers foundational feature engineering techniques for converting unstructured raw data (text and images) into numerical, fixed-length feature vectors suitable for traditional machine learning algorithms.Key Topics ImplementedPart A (Text Features): Bag-of-Words (BoW) text representation using CountVectorizer to produce document-term matrices, analyzing vocabulary growth with n-grams, and observing sparsity.   Part B (Image Features): Grayscale transformation as dimensionality/feature reduction, spatial matrix flattening, image resolution resizing, and feature vector extraction.   Home Assignment: Creating a 2-class image dataset, extracting uniform (64, 64) features into a (20, 4096) matrix, saving to dataset.npz, and analyzing the Curse of Dimensionality.   
