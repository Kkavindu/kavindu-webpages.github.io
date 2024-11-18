---
title: "🔗 Research Assistant & MS Candidate"
collection: teaching
type: "Research Assistant & MS Candidate"
permalink: /teaching/2017-spring-teaching-4
venue: "Clarkson University, Mechanical and Aerospace Engineering Department"
date: 2020-01-01
location: "Potsdam, USA"
---

In my role as a Research Assistant and MS Candidate at Clarkson University, I specialized in developing automated systems and deep learning solutions for precise material testing. My work included designing a patent-pending micro-tensile testing system featuring a fully automated, high-resolution imaging setup for real-time analysis. I also pioneered a deep learning framework to enhance microscopic strain measurement by tracking microstructural features in in-situ videos, achieving unprecedented accuracy in strain analysis. These projects represent my commitment to advancing material testing through automation and AI innovation.

Development of Automated In-Situ Testing System (Patent pending)
======
I designed and developed a fully automated in-situ micro-tensile testing system, now patent-pending, to enable high-resolution, in-situ microscopic deformation video acquisition. Built entirely from scratch, this innovative setup integrates mechanical precision, advanced imaging capabilities, and software-driven automation to deliver real-time high quality and high throuput data generation.

The system features a 3-axis motorized stage with precision stepper motors, providing exceptional control over specimen positioning during tensile testing. Paired with a high-load micro-tensile tester, it captures critical deformation events under controlled loading conditions. High-resolution inverted upright optical microscopy at multiple magnifications (5X, 10X, and 20X) ensures detailed visualization of microstructural evolution during deformation.

To enhance usability and performance, I developed a robust software suite that integrates:

 - Feature Tracking: Automated detection and real-time tracking of microstructural features to maintain the original location within the field of view.
 - Dynamic Autofocus and Focus Stacking: Intelligent algorithms to capture the entire field of view within focus especially at high strain levels during testing.
 - Panoramic Imaging: The latest addon to the system for capturing in-situ videos of the entire specimen surface for comprehensive microstructural studies.
 - Image Stabilization: Advanced post-processing features to generate final high-resolution videos.

This system not only delivers high-quality, real-time data in less than 8.5 minutes but also addresses longstanding challenges in in-situ testing, such as reducing variability and accelerating testing workflows. It has become a cornerstone of research at Clarkson University, where it is heavily utilized across multiple projects, supporting advancements in materials science and mechanical engineering.

Building on its success, we are working with Micron LLC, a startup company based in Potsdam, NY, to commercialize this system as a marketable product. This initiative aims to bring cutting-edge, automated in-situ micro-tensile testing capabilities to a broader audience in academia and industry, revolutionizing the way materials are studied and characterized at the microscale.

Smart in-situ tensile testing system
![In-situ stage](Figure 7.png "Smart in-situ tensile testing system")

Characterization of microscopic deformation of materials using deep learning algorithms
======
A microstructure-informed design approach is set to revolutionize the design of metals and alloy components for aerospace applications. In this approach, a designer utilizes the influence of individual microstructural features on microscopic deformation to yield desirable macroscopic properties. Therefore, the development of advanced experimental capabilities that enable detailed characterization of microscopic deformation of material test specimens is critical to realize this paradigm shift in practice. However, extracting the complex characteristics of microscopic deformation hidden in raw image data is quite challenging. In this article, we propose an automated data extraction and analysis method based on instance segmentation and tracking of microstructural features using deep learning (DL) and image processing algorithms. The method consists of a trained mask Region-based Convolutional Neural Network (mask R-CNN) DL model combined with a regional instance segmentation approach for the instance segmentation of features, an intersection over union-based multi-object tracking method to track segmented instances as they deform, and kinematics models to extract the material characteristics from the geometrical data of the deforming instances. The method is then validated by characterizing the microscopic deformation of an additively manufactured 316L stainless steel coupon specimen under quasi-static tensile loading. Our study presents a general framework for advancing deep learning algorithms to solve complex problems in the field of experimental mechanics.

Publication: Characterization of microscopic deformation of materials using deep learning algorithms, Material & Design 2021

Talk 1: Characterization of Microscopic Deformation of Materials Using Deep Learning Methods, MS&T 2021, Columbus, Ohio, USA
Talk 2: Characterization of microscopic deformation of materials using computer vision, AIAA Scitech 2023, National Harbor, MD, USA

Deep Learning based microscopic strain measuring technique for in-situ data
![Graphical abstract M&D](Figure 4.png "Deep Learning based microscopic strain measuring technique for in-situ data")
