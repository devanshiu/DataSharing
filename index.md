## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/devanshiu/DataSharing/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Introduction

Classification of histologic patterns in lung adenocarcinoma is critical for determining tumor grade and treatment. However, this task is often challenging due to the heterogeneous nature of lung adenocarcinoma and the subjective criteria for evaluation. In this study, we propose a deep learning model that automatically classifies the histologic patterns of lung adenocarcinoma on surgical resection slides. Our model uses a convolutional neural network to identify regions of neoplastic cells, then aggregates those classifications to infer predominant and minor histologic patterns for any given whole-slide image. We evaluated our model on an independent set of 143 whole-slide images. It achieved a kappa score of 0.525 and an agreement of 66.6% with three pathologists for classifying the predominant patterns, slightly higher than the inter-pathologist kappa score of 0.485 and agreement of 62.7% on this test set. All evaluation metrics for our model and the three pathologists were within 95% confidence intervals of agreement. If confirmed in clinical practice, our model can assist pathologists in improving classification of lung adenocarcinoma patterns by automatically pre-screening and highlighting cancerous regions prior to review. 

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

### Motivation


### Dataset
To develop and evaluate our model for classifying lung adenocarcinoma histology patterns, we collected whole-slide images from all patients with a diagnosis of lung adenocarcinoma since 2016 who underwent lobectomies at the Dartmouth-Hitchcock Medical Center (DHMC), a tertiary academic care center in Lebanon, New Hampshire. These histopathology slides contain formalin-fixed paraffin-embedded tissue specimens and were scanned by a Leica Aperio whole-slide scanner at 20x magnification at the Department of Pathology and Laboratory Medicine at DHMC. In total, 422 whole-slide images were collected for this study. We randomly partitioned 279 of these images (about two-thirds of the dataset) for model training, and the remaining 143 images (about one-third of the dataset) for model testing.


### Code
Our code is available here: https://github.com/BMIRDS/deepslide

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/devanshiu/DataSharing/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Accessing Dataset

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfGi9_3tinNB8XV8fUhWX4YPKsl8kRcLhj66xKdOq2nXkXEiQ/viewform" width="640" height="2166" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
