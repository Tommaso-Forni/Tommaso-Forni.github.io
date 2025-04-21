---
layout: default
title: PhD Thesis Projects
---

# Artificial Intelligence for Predictive Design and Development of Innovative Materials, Manufacturing Processes, and Technological Applications

This page presents a collection of projects developed during my PhD, focused on the integration of machine learning techniques into the modeling, characterization, and prediction of material properties across different length scales. From nanoscale image-based representations of graphene to macro-scale mechanical property prediction in polymeric components, these projects showcase data-driven frameworks for advancing materials science and engineering. Each project combines domain-specific knowledge with modern ML tools, and is accompanied by open-source code repositories for reproducibility and further development.

## GrapheNet: A Deep Learning Framework for Predicting the Physical and Electronic Properties of Nanographenes Using Images

GrapheNet is a novel image-based representation framework developed for nanographene flakes. It employs convolutional neural networks (CNNs) to extract and learn from spatial features encoded in images of atomic structures, enabling efficient and scalable prediction of material properties.

Compared to traditional descriptor-based approaches, GrapheNet demonstrates improved computational performance and generalizability, making it well-suited for high-throughput materials screening and property prediction tasks. The methodology has been rigorously benchmarked against conventional techniques, showing clear advantages in both accuracy and scalability.

The repository can be found here: [GrapheNet](https://github.com/daimoners/GrapheNet)


## Data-Driven Analysis and Generation of Defective Graphene Nanoflakes for Property Prediction and Device Optimization

This project extends the image-based representation approach to incorporate detailed defect characterization in graphene nanoflakes. By combining object detection with geometric and frequency-domain feature extraction, it enables a precise and interpretable analysis of structural irregularities.

Machine learning models, such as XGBoost, are integrated to predict electronic properties based on extracted defect features. This framework enhances the overall predictive performance and supports robust, scalable analysis of complex defect patterns, making it a valuable tool for data-driven materials design.

The repository can be found here: [GrapheNetDefectDetector](https://github.com/daimoners/GrapheNetDefectDetector)

## Exploring the Interplay of Material Properties, Production Parameters, and ML in Mechanical Property Prediction

This project explores the macro-scale application of machine learning for predicting the mechanical properties of polymeric specimens produced via additive manufacturing (AM). By integrating experimental tensile test data with supervised ML models, the framework achieves high predictive accuracy for elastic properties such as Young’s modulus and yield strength.

The use of model interpretability techniques enables the identification of key features driving mechanical behavior, offering valuable insights into the relationship between processing parameters, material structure, and performance. Developed in collaboration with the University of Belgrade, this study demonstrates the practical potential of data-driven approaches to optimize AM processes and improve the mechanical performance of manufactured components.

The repository can be found here: [MechanicalPropertyPrediction](https://github.com/daimoners/MechanicalPropertyPrediction)