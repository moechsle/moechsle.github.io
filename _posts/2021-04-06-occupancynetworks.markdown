---
layout: post
title: "Occupancy Networks: Learning 3D Reconstruction in Function Space."
date: 2021-04-06 00:00:00 +0300
authors: L. Mescheder, M. Oechsle, M. Niemeyer, A. Geiger
conference: CVPR 2019 (oral)
videolink: https://www.youtube.com/embed/w1Qo3bOiPaE?autoplay=1&mute=1
description: # Add post description (optional)
img: vis3d.gif # Add image post (optional)
tags: [3D deep learning, continous function as 3D representation] # add tag
---

With the advent of deep neural networks, learning-based approaches for 3D reconstruction have gained popularity. However, unlike for images, in 3D there is no canonical representation which is both computationally and memory efficient yet allows for representing high-resolution geometry of arbitrary topology. Many of the state-of-the-art learning-based 3D reconstruction approaches can hence only represent very coarse 3D geometry or are limited to a restricted domain. In this paper, we propose Occupancy Networks, a new representation for learning-based 3D reconstruction methods. Occupancy networks implicitly represent the 3D surface as the continuous decision boundary of a deep neural network classifier. In contrast to existing approaches, our representation encodes a description of the 3D output at infinite resolution without excessive memory footprint. We validate that our representation can efficiently encode 3D structure and can be inferred from various kinds of input. Our experiments demonstrate competitive results, both qualitatively and quantitatively, for the challenging tasks of 3D reconstruction from single images, noisy point clouds and coarse discrete voxel grids. We believe that occupancy networks will become a useful tool in a wide variety of learning-based 3D tasks.

[![Paper]()](http://www.cvlibs.net/publications/Oechsle2019ICCV.pdf "Paper")\\
[![Code]()](https://github.com/LMescheder/Occupancy-Networks "Code")