---
layout: page
title: Projects
permalink: /projects/
order: 3
---

### Research Projects

* Self-supervised learning of shared audio-video-text representations (Ongoing)
    * Exploring novel intermediate pretraining strategies to learn joint audio-video-text embeddings
    * Experimenting with cross-modal contrastive losses, extending them to three modalities using *mixup*

* Microarchitectural Enhancements for High Performance I/O (Ongoing)
    * Augmenting an existing microarchitecture simulator, Qsim, with I/O tracing functionality
    * Exploring microarchitectural optimizations to improve latency under the regime of high speed I/O

* Sketch-based Modeling (Spring 2021) 
[[report]({{ site.url }}/assets/reports/sketch_based_modeling.pdf)]
    * Studied various approaches of generating3D models from user-drawn sketches, attempting to devise a novel method which would generate a set of smoothly-connected Bézier patches to fit the sketch

* Analysis of Vector Addition Systems
[[report]({{ site.url }}/assets/reports/ens_internship_report.pdf)]
    * Worked on the non-trivial problem of devising an algorithm to construct the semi-linear bases for projections
    of reachability sets of Vector Addition Systems, elucidating definitions and formal proofs

### Technical Projects

* Image Segmentation using Recurrent Residual U-Net (Spring 2020)
[[code](https://github.com/akkapakasaikiran/MIS-R2UNet)] 
[[report](https://github.com/akkapakasaikiran/MIS-R2UNet/blob/master/project_report.pdf)]
    * Performed segmentation on medical images using a deep neural network developed by augmenting a U-Net with residual connections and recurrence, achieving fine results on the dice coefficient metric

* Compiler for a C-like Language (Spring 2021)
    * Built a compiler for a subset of C incorporating expressions, control structures, functions, and scoping
    * Performed scanning (using Lex), parsing (using Yacc), and AST construction, yielding assembly code

* Hospital Management System (Spring 2021) [[code](https://github.com/CS387-Project-Team/Patient-management-system)]
    * Developed a patient-centric hospital management system as a Flask web app providing functionalities such as book/cancel appointments and tests, buy medicines, pay bills, add prescription, etc.
    * Added secure access to patients’ details and history as well as an interface to view disease analytics

* FMX Modeling and Animation (Autumn 2020) 
[[code]()] 
[[movie](https://youtu.be/RhG3SWKn6W8)]
    * Modeled a bike, a rider, and a track in OpenGL and rendered it using shading and texturing
    * Animated the above scene to create a short movie of an FMX rider performing stunts


* Exploring the Foreshadow Attack (Autumn 2020) 
[[report]({{ site.url }}/assets/reports/foreshadow.pdf)]
[[presetation]({{ site.url }}/assets/reports/foreshadow_presentation.pdf))]
    * Explored and imitated Foreshadow, a speculative execution attack on Intel's processors which allows attackers to steal sensitive information from personal computers or third-party clouds
    * Studied precursor attacks like Meltdown and Spectre which exploit transient out-of-order execution
    * Presented a proof-of-concept by simulating SGX's abort page semantics to showcase an attack

### Smaller Projects

* A Simple Container from Scratch [[code](https://github.com/akkapakasaikiran/container-from-scratch)]
    <!-- * Understood and built a simple container from scratch using Linux namespaces and cgroups -->

* Reinforcement Learning
    * Bandit Algorithms [[code](https://github.com/akkapakasaikiran/bandit-algos)]
    * MDP Planning [[code](https://github.com/akkapakasaikiran/mdp-planning)]
    * Windy Gridworld [[code](https://github.com/akkapakasaikiran/windy-gridworld)]

* Proofreading Rewriter [[code](https://github.com/akkapakasaikiran/Proofreading-Rewriter)]
    <!-- * Developed a Python-based tool which detects and corrects spelling and grammar mistakes, and suggests alternative words and phrases using statistics from online APIs like datamuse and phrasefinder -->

* Spanning Tree Protocol [[code](https://github.com/akkapakasaikiran/NoLoops)] 
    <!-- * Built a loop-free logical topology of LANs and bridges by implementing the protocol in C++ -->
    <!-- * Simulated the functioning of learning bridges on a sequence of data transfers using callbacks -->

* Battleships [[code](https://github.com/saum-g/Battleships)]
    <!-- * Implemented the board game Battleships in the language Racket with multiple difficulty levels, incorporating ideas from functional and object oriented paradigms to design probabilistic -->

* Traffic Sign Classification using Deep Learning [[code](https://github.com/akkapakasaikiran/Traffic-Signs-Classifier)]
    <!-- * Implemented a CNN based on Inception modules and Spatial Transformation layers from scratch -->
    <!-- * Trained on the GTSRB dataset achieving almost 98% accuracy with little to no data augmentation -->