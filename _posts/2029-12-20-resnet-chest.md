---
layout: post
current: post
cover: assets/images/cd-background.jpg
navigation: True
title: COVID-19 Detection from Chest X-Ray Images
date: 2020-12-20 10:18:00
last_modified_at: 2020-12-20 10:18:00
tags: [Experiences]
class: post-template
subclass: 'post'
author: Atharva Pusalkar
---

A small project that I did back in December of 2020 for COVID-19 detection using chest x-ray images. The model uses a modified ResNet-50 model for detection using RGB signals.

GradCAM activation map using the ResNet-50 model:
![GradCAM for activation map visualization](assets/images/cd-blog.png)

CLAHE (Contrast Limited Adaptive Histogram Equalization) is also applied to highlight key areas in the scanned images:
![CLAHE for COVID detection](assets/images/cd-clahe.png)

For complete implementation, visit [https://colab.research.google.com/drive/1WSC3at-tNeRX-phdlGnnJYiagJwElp5o?usp=sharing](https://colab.research.google.com/drive/1WSC3at-tNeRX-phdlGnnJYiagJwElp5o?usp=sharing) 
