---
layout: post
title: Releasing Not Pure Poole v0.1.0
author: Songzi Vong
tags:
- jekyll theme
- jekyll
date: 2020-10-01 13:56 +0800
---
Let's face it, osteoarthritis is no laughing matter. But did you know that measuring the thickness of the subchondral bone plate can give us important insights into the health of our joints? This layer of bone, located under the cartilage, can help diagnose and treat joint diseases like osteoarthritis. 
 
There are a few methods for measuring the thickness of this bone plate, but two of the most popular are dual thresholding and morphological escalator. Both have their pros and cons, but the choice depends on the type of medical images and desired accuracy. 
 
Dual thresholding is like a game of "hot and cold" - it separates the bone from surrounding tissue by using two different threshold values. The first value segments out the bone, the second segments out the surrounding tissue, and the difference gives us the thickness of the subchondral bone plate. 
 
The morphological escalator method is like a game of "peek-a-boo" - it uses math operations to extract the bone from surrounding tissue and calculate the thickness. It starts by applying a series of erosion and dilation operations to the image, adjusting the number of operations until the desired thickness is achieved. 
 
Both methods can be performed using medical imaging software such as CTAn Bruker. And a recent study has even introduced a new semi-automated protocol that reduces user bias and makes segmentation of trabecular from cortical bone more straightforward and user-friendly. 
 
So, next time you're feeling down about your osteoarthritis, remember that measuring the thickness of your subchondral bone plate can give you valuable insights into the health of your joints. And who knows, it might even bring a smile to your face.



















Subchondral bone plate thickness is an important parameter in the diagnosis and treatment of joint diseases such as osteoarthritis. The subchondral bone plate is the layer of bone that lies under the cartilage in a joint, and its thickness can provide important information about the health of the joint.

There are several methods for measuring subchondral bone plate thickness based on medical images, two of the most commonly used methods are dual thresholding and morphological escalator in CTAn software and Aviso. Both methods have their own advantages and disadvantages, and the choice of method depends on the type of medical images and the desired level of accuracy. 

Dual thresholding method is a technique that separates the bone from the surrounding tissue by applying two different threshold values. First, a lower threshold value is applied to the image to segment out the bone. Then, a higher threshold value is applied to the image to segment out the surrounding tissue. The difference between the two threshold values is used to calculate the thickness of the subchondral bone plate.

Morphological escalator method is a technique that uses mathematical morphology operations to extract the bone from the surrounding tissue, and then calculate the thickness of the subchondral bone plate. This method starts by applying a series of erosion and dilation operations to the image. The erosion operation is used to remove pixels from the bone structure, while the dilation operation is used to add pixels to the bone structure. The number of erosion and dilation operations is adjusted until the desired thickness of the subchondral bone plate is achieved. 

Both methods can be performed using a medical imaging software such as CTAn Bruker. This software is specifically designed for the analysis of medical images and has the capability to perform both dual thresholding and morphological escalator method.

A recent study, published in Royal Society Open Science, by Herbst et al. titled "A new straightforward method for semi-automated segmentation of trabecular bone from cortical bone in diverse and challenging morphologies" has presented a new semi-automated protocol which reduces user bias and enables straightforward, user-friendly segmentation of trabecular from the cortical bone. The study shows that this method can conveniently be used as a ‘recipe’ in commercial programs like Avizo and applied to a variety of datasets. The study also reported details of the recipe, so that other groups can readily re-create a similar method in open access programs. 
