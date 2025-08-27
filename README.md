# MultiRetina-Deep Learning Disease Classification
Overview:
Advanced deep learning system for multi-label classification of retinal diseases using dual-input architecture that processes both left and right eye fundus images simultaneously. Built on the ODIR-5K dataset containing 5,000+ image pairs across 8 diagnostic categories.
Key Technical Components:

Architecture: DenseNet121-based dual-input model with parallel processing branches
Dataset: ODIR-5K fundus images labeled for 8 conditions (Normal, Diabetes, Glaucoma, Cataract, AMD, Hypertension, Myopia, Other)
Multi-label Classification: Simultaneous prediction of multiple co-existing retinal conditions
Data Processing: Image preprocessing, normalization, and dual-input TensorFlow pipeline optimization

Results:

Primary Model: DenseNet121 achieved 0.8456 AUC with 61.39% precision
Comparative Analysis: VGG16 baseline reached 0.82 AUC, demonstrating DenseNet superiority
Clinical Relevance: Strong generalization across validation and test sets for practical diagnostic application

Technical Innovation:

Dual-eye analysis captures complementary pathological features missed by single-eye approaches
Transfer learning with ImageNet pre-trained weights and fine-tuning strategy
Multi-label binary cross-entropy loss with early stopping and model checkpointing

Technologies Used:
TensorFlow, DenseNet121, VGG16, Python, medical imaging, computer vision
This project demonstrates expertise in medical AI, deep learning architecture design, and multi-label classification with real clinical applications.
