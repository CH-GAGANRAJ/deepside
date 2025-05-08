# Deepside a Deeplearning Framwork for Drug Side effect prediction
The project titled "DeepSide – A Deep Learning Framework for Drug Side Effect Prediction" aims to improve the safety and efficiency of drug development by predicting potential adverse effects before clinical trials. Unforeseen side effects are a leading cause of drug failure, posing serious health risks and financial losses. This project addresses that problem using a deep learning-based solution that combines chemical structure data of drugs with gene expression profiles from the LINCS L1000 dataset.

Multiple deep learning architectures were evaluated, with the Convolutional Neural Network (CNN) model using SMILES string representations of drugs emerging as the most effective. It showed significant improvements over existing methods in terms of both macro and micro AUC scores. The system was also able to identify drug-side effect pairs absent from current labeled datasets but reported in scientific literature, showcasing its practical predictive power.

Tech Stack Used:

Programming Language: Python

Libraries & Frameworks: TensorFlow, PyTorch, scikit-learn, NumPy, Pandas

Data Processing & Visualization: Matplotlib, Seaborn

Dataset: LINCS L1000 (gene expression data), DrugBank/SMILES (chemical structure)

Model Architectures: MLP (Multi-Layer Perceptron), CNN (Convolutional Neural Network), multimodal deep learning models

This project demonstrates how combining bioinformatics and AI can create effective tools for drug safety analysis, ultimately supporting better, safer pharmaceutical development.

