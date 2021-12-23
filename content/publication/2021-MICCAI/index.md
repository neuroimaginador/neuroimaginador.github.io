---
abstract: 'In this paper, a novel method to estimate the level of Rician noise in
  magnetic resonance images is presented.  We hypothesize that noiseless images follow
  Benford''s law, that is, the probability distribution of the first digit of the
  image values is logarithmic. We show that this is true when we consider the raw
  acquired image in the frequency domain. Two measures are then used to quantify the
  (dis)similarity between the actual distribution of the first digits and the more
  theoretical Benford''s law: the Bhattacharyya coefficient and the Kullback-Leibler
  divergence. By means of these measures, we show that the amount of noise directly
  affects the distribution of the first digits, thereby making it deviate from Benford''s
  law. In addition, in this work, these findings are used to design a method to estimate
  the amount of Rician noise in an image. The utilization of supervised machine learning
  techniques (linear regression, polynomial regression, and random forest) allows
  predicting the parameters of the Rician noise distribution using the dissimilarity
  between the measured distribution and Benford''s law as the input variable for the
  regression. In our experiments, testing over magnetic resonance images of 75 individuals
  from four different repositories, we empirically show that these techniques are
  able to precisely estimate the noise level present in the test T1 images. '
authors:
- Rosa Maza-Quiroga
- Karl Thurnhofer-Hemsi
- admin
- Ezequiel López-Rubio
date: '2021-09-27'
header:
  caption: ''
  image: 2021-MICCAI.png
image_preview: miccai2021-logo.png
math: true
publication: 24th International Conference on Medical Image Computing and Computer
  Assisted Intervention (MICCAI) 2021
publication_short: 'MICCAI 2021'
publication_types:
- '1'
selected: false
title: Rician noise estimation for 3D Magnetic Resonance Images based on Benford's Law
url_code: 'https://github.com/icai-uma/RicianNoiseEst_3DMRI_BenfordsLaw.git'
url_dataset: ''
url_pdf: 2021-miccai.pdf
url_project: ''
url_slides: ''
url_video: ''

tags:
- MRI
- Rician noise
- Benford’s law
- Noise estimation 
---

