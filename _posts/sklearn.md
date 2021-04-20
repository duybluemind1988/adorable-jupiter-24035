---
title: Scikit learn summary
subtitle: All you need to know about scikit learn
excerpt: >-
  The Ride In The Woods lorem ipsum dolor sit amet, consectetur adipiscing elit,
  sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
date: '2021-04-11'
thumb_img_path: images/sklearn_image.png
thumb_img_alt: A motorcycle in a forest
content_img_path: images/sklearn_image.png
content_img_alt: A motorcycle in a forest
seo:
  title: The Ride In The Woods
  description: A cautionary tale about riding
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: The Ride In The Woods
      keyName: property
    - name: 'og:description'
      value: A cautionary tale about riding
      keyName: property
    - name: 'og:image'
      value: images/3.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: The Ride In The Woods
    - name: 'twitter:description'
      value: A cautionary tale about riding
    - name: 'twitter:image'
      value: images/3.jpg
      relativeUrl: true
layout: post
---

This project was started in 2007 as a Google Summer of Code project by David Cournapeau. Later that year, Matthieu Brucher started work on this project as part of his thesis.

In 2010 Fabian Pedregosa, Gael Varoquaux, Alexandre Gramfort and Vincent Michel of INRIA took leadership of the project and made the first public release, February the 1st 2010. Since then, several releases have appeared following a ~ 3-month cycle, and a thriving international community has been leading the development.

## An introduction to machine learning with scikit-learn

- Machine learning: the problem setting
- Loading an example dataset
- Learning and predicting
- Conventions

## Getting started

The purpose of this guide is to illustrate some of the main features that scikit-learn provides. It assumes a very basic working knowledge of machine learning practices (model fitting, predicting, cross-validation, etc.). Please refer to our installation instructions for installing scikit-learn.

Scikit-learn is an open source machine learning library that supports supervised and unsupervised learning. It also provides various tools for model fitting, data preprocessing, model selection and evaluation, and many other utilities.

## Fitting and predicting: estimator basics

Scikit-learn provides dozens of built-in machine learning algorithms and models, called estimators. Each estimator can be fitted to some data using its fit method.

Here is a simple example where we fit a RandomForestClassifier to some very basic data:

```python

from sklearn.ensemble import RandomForestClassifier
clf = RandomForestClassifier(random_state=0)
X = [[ 1,  2,  3],  # 2 samples, 3 features
     [11, 12, 13]]
y = [0, 1]  # classes of each sample
clf.fit(X, y)

```

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

```css
.selector{
  prop: value;
}
```

```R
library(tidyverse)
library(dplyr)
```


First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)