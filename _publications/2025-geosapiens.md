---
title: "Geometric-Guided Few-Shot Dental Landmark Detection with Human-Centric Foundation Model"
collection: publications
category: conferences
permalink: /publication/2025-geosapiens
excerpt: 'This paper presents GeoSapiens, a novel few-shot learning framework that adapts a human-centric foundation model (Sapiens) for dental landmark detection with geometric priors.'
date: 2025-06-01
venue: 'International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI 2025)'
paperurl: 'https://arxiv.org/abs/2507.04710'
codeurl: 'https://github.com/xmed-lab/GeoSapiens'
---

**Authors**: Anbang Wang\*, Marawan Elbatel\*, Keyuan Liu, Lizhuo Lin, Meng Lan, Yanqi Yang, Xiaomeng Li  
(\*Equal contribution)

**Abstract**: Accurate detection of anatomic landmarks is essential for assessing alveolar bone and root conditions, thereby optimizing clinical outcomes in orthodontics, periodontics, and implant dentistry. Manual annotation of landmarks on cone-beam computed tomography (CBCT) by dentists is time-consuming, labor-intensive, and subject to inter-observer variability. Deep learning-based automated methods present a promising approach to streamline this process efficiently. However, the scarcity of training data and the high cost of expert annotations hinder the adoption of conventional deep learning techniques. To overcome these challenges, we introduce GeoSapiens, a novel few-shot learning framework designed for robust dental landmark detection using limited annotated CBCT of anterior teeth. Our GeoSapiens framework comprises two key components: (1) a robust baseline adapted from Sapiens, a foundational model that has achieved state-of-the-art performance in human-centric vision tasks, and (2) a novel geometric loss function that improves the model's capacity to capture critical geometric relationships among anatomical structures. Experiments conducted on our collected dataset of anterior teeth landmarks revealed that GeoSapiens surpassed existing landmark detection methods, outperforming the leading approach by an 8.18% higher success detection rate at a strict 0.5 mm threshold—a standard widely recognized in dental diagnostics.

**Links**: [Paper](https://arxiv.org/abs/2507.04710) | [Code](https://github.com/xmed-lab/GeoSapiens)

