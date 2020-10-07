## Pathologist-level classification of histologic patterns on resected lung adenocarcinoma slides with deep neural networks

### Introduction

Classification of histologic patterns in lung adenocarcinoma is critical for determining tumor grade and treatment. However, this task is often challenging due to the heterogeneous nature of lung adenocarcinoma and the subjective criteria for evaluation. In this study, we propose a deep learning model that automatically classifies the histologic patterns of lung adenocarcinoma on surgical resection slides. Our model uses a convolutional neural network to identify regions of neoplastic cells, then aggregates those classifications to infer predominant and minor histologic patterns for any given whole-slide image. We evaluated our model on an independent set of 143 whole-slide images. It achieved a kappa score of 0.525 and an agreement of 66.6% with three pathologists for classifying the predominant patterns, slightly higher than the inter-pathologist kappa score of 0.485 and agreement of 62.7% on this test set. All evaluation metrics for our model and the three pathologists were within 95% confidence intervals of agreement. If confirmed in clinical practice, our model can assist pathologists in improving classification of lung adenocarcinoma patterns by automatically pre-screening and highlighting cancerous regions prior to review. 

### Motivation


### Dataset
To develop and evaluate our model for classifying lung adenocarcinoma histology patterns, we collected whole-slide images from all patients with a diagnosis of lung adenocarcinoma since 2016 who underwent lobectomies at the Dartmouth-Hitchcock Medical Center (DHMC), a tertiary academic care center in Lebanon, New Hampshire. These histopathology slides contain formalin-fixed paraffin-embedded tissue specimens and were scanned by a Leica Aperio whole-slide scanner at 20x magnification at the Department of Pathology and Laboratory Medicine at DHMC. In total, 422 whole-slide images were collected for this study. We randomly partitioned 279 of these images (about two-thirds of the dataset) for model training, and the remaining 143 images (about one-third of the dataset) for model testing.


### Code
Our code is available here: https://github.com/BMIRDS/deepslide

### Accessing Dataset

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfGi9_3tinNB8XV8fUhWX4YPKsl8kRcLhj66xKdOq2nXkXEiQ/viewform" width="640" height="2166" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
