# Laboratory 3 Report

Part A:
1. A single distinct vocabulary term (unique word) extracted from the entire document collection.
2. A Document-Term Count Matrix (a 2D numeric array or sparse matrix) that maps raw text into fixed-length arrays of token frequencies.
3. It completely removes grammar, syntax, and word sequence; it ignores synonyms and word meanings by treating every unique word as a separate dimension; and it silently strips out single-letter words and lowercase casing.

Part B:
1. It compresses three color channels (Red, Green, Blue) into one luminance channel, cutting two-thirds of the input data size while keeping shapes, brightness, and edges intact.
2. Height multiplied by Width (H x W). For a 64 by 64 image, the vector length is 4096.
3. Standard machine learning models (such as Logistic Regression and SVM) require a 1D vector of numerical features per data sample and cannot directly take 2D or 3D matrices as an input.
4. Machine learning models require every sample to have the exact same number of input features, so resizing ensures all images convert to the same vector length regardless of their original dimensions.

Home Assignment Paragraph:
Having only 20 samples in a 4096-dimensional feature space causes issues related to the curse of dimensionality. In such a high-dimensional space with very few samples, data points are sparse and isolated, which reduces the effectiveness of distance calculations and makes traditional classifiers prone to overfitting. Dimensionality reduction methods like PCA help address this by mapping the raw pixel values into a smaller set of principal components, while Convolutional Neural Networks (CNNs) process 2D spatial features directly rather than relying on flattened vectors.