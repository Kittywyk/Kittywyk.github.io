---
title: Nighttime Vulnerable Road User (VRU) Detection
date: 2024-04-28
external_link: 

image:
  caption: 

authors:
  - admin
  
tags:

---

## Abstract
Detecting vulnerable road users (VRUs) at night presents significant challenges. Numerous methods rely heavily on annotations, yet the low visibility of nighttime images poses difficulties for labeling. To obviate the need for nighttime annotations, unsupervised domain adaptation manifests as a viable solution. However, existing approaches often focus solely on semantic-level domain shifts, neglecting the pixel-level discrepancies due to inherent degradations in the night domain, which can significantly impair machine vision. This oversight limits the effectiveness of nighttime VRU detection. To this end, TripleA, an unsupervised domain adaptation framework is introduced to achieve nighttime VRU detection. Realized through a crucial triple alignment, TripleA first aligns the distributions of the labeled daytime domain with the unlabeled nighttime domain. Then, the degraded image is enhanced in terms of illumination and noise. We present an illumination difference-aware denoising network to address the intractable noise and enable selfsupervised learning through a meticulously designed exchange-recombination strategy, which is integrated into a novel pseudosupervised attention to achieve noise distribution alignment. To further enhance the capabilities of the denoising network under real-world scenarios, we introduce degradation alignment to enforce domain-invariant degradation encoding. Extensive experiments demonstrate that our proposed framework achieves superior performance in nighttime VRU detection without relying on nighttime annotations.

## My Role
I am the first author of the study and I completed all the steps of conceptualizing the experiment, conducting the experiment and writing the paper.

## Research Content
1. VRUs in traffic surveillance camera data during the daytime were labeled.
2. An unsupervised domain adaptation framework was proposed for nighttime VRU detection using only daytime annotations, reducing the cost of manually labeling challenging nighttime data
3. An illumination difference-aware denoising network was designed to suppress noise that is coupled with illumination in nighttime images, the network can be trained in a self-supervised manner
4. A paper manuscript was authored and it is currently under review by IEEE Transactions on Intelligent Transportation Systems


<!--more-->
