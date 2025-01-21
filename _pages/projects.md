---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---


### Cross-modality image generation for SV2A PET
<div style="display: flex; align-items: center;">
  <img src="/images/mr2sv2a.png" alt="" style="width: 300px; margin-right: 20px;">
  <p>This research developed an image translation method from T1w MRI (and/or [<sup>18</sup>F]FDG PET) to [<sup>11</sup>C]UCB-J SV2A brain PET. A 3D multi-stage residual U-Net with supervised attention was proposed for the image-to-image fast inference. Generating Synthetic PET Images of Synaptic Density Based on MR T1 Images, abstract submitted to <a href="https://jnm.snmjournals.org/content/65/supplement_2/242162.abstract">SNMMI 2024</a>, full paper submitted to <u>EJNMMI Physics</u>. </p>
</div>

<div style="display: flex; align-items: center;">
  <img src="/images/mr2sv2a_model.png" alt="" style="width: 300px; margin-right: 20px;">
  <p>Generation of Synthetic Brain PET Images of Synaptic Density from MRI and FDG-PET using a Multi-stage Residual U-Net, abstract submitted to <a href="https://ieeexplore.ieee.org/document/10655600">IEEE MIC 2024</a>. US provisional patent application pending: Methods for Generation of Synthetic SV2A PET from MRI Images.</p>
</div>

### Noise reduction for NeuroEXPLORER: A Multi-Tracer Investigation
<div style="display: flex; align-items: center;">
  <img src="/images/nx_denoise.png" alt="" style="width: 300px; margin-right: 20px;">
  <p>This project aims to develop denoising models for the ultra-high-sensitivity NeuroEXPLORER (NX) brain PET images across multiple tracers. Modified U-Nets and DDIM were implemented for the task of noise reduction across multiple tracers and count levels. The unified 3D models performed robustly for tracers including [<sup>18</sup>F]FDG, [<sup>18</sup>F]SynVesT-1, [<sup>18</sup>F]Flubatine, [<sup>18</sup>F]FE-PE2I, [<sup>18</sup>F]FPEB, [<sup>11</sup>C]LSN3172176, [<sup>11</sup>C]raclopride and [<sup>11</sup>C]-(+)-PHNO. Deep Learning Based PET Denoising for NeuroEXPLORER: A Multi-Tracer Investigation, abstract submitted to <u>SNMMI 2025</u>. </p>
</div>

### Direct estimation of arterial input function from dynamic brain PET imaging

<div style="display: flex; align-items: center;">
  <img src="/images/aif.png" alt="" style="width: 300px; margin-right: 20px;">
  <p> To achieve the estimation of arterial input function (AIF) without blood sampling, we developed a modified transformer to estimate metabolite corrected input function directly from dynamic images. TACs of various brain ROIs extracted from dynamic [<sup>11</sup>C]UCB-J images were served as inputs for predicting metabolite AIFs. Incorporating PET imaging physics, the model employed a loss function with frame-specific weighting to account for radioactive decay. Population-based input function was integrated using a derivative-based shape loss.
</p>
</div>


### Super resolution for mCT/HRRT scanners

<div style="display: flex; align-items: center;">
  <img src="/images/sr.png" alt="" style="width: 300px; margin-right: 20px;">
  <p> In this project, we aim to achieve super resolution for clinical mCT images, enhancing their resolution from approximately 4 mm to around 2.5 mm, matching the resolution of an HRRT scanner, and ultimately to 1.5 mm, comparable to the NX system. We adapted the idea of dense connections and proposed a densely connected network. Our preliminary results support the development of generative image restoration methods for brain PET image enhancement.
</p>
</div>


### CT-free attenuation correction for mCT/NX scanners
<div style="display: flex; align-items: center;">
  <img src="/images/nx_mumap.png" alt="" style="width: 300px; margin-right: 20px;">
  <p> To achieve CT-free attenuation correction for NX, we developed a 3D attention U-net with transfer learning to generate 𝜇-maps from non-attenuation-corrected (NAC) images. The network was trained on whole-body NAC mCT scans and the corresponding 𝜇-maps. We then fine-tuned the network using only 3 NX scans to generate 𝜇-maps for NX system. This project aims to explore the potential of adapting networks to bridge the domain gap in value distribution and resolution differences between scanners/vendors using very limited data.
</p>
</div>


### A Feature Reduction and Visualization Tool for the Diagnosis of ASD based on rs-fMRI
<div style="display: flex; align-items: center;">
  <img src="/images/dvae_visual.png" alt="" style="width: 300px; margin-right: 20px;">
  <p> We proposed a feature reduction and visualization tool for ASD detection using resting-state fMRI (rs-fMRI). Our approach employed a denoising variational autoencoder (DVAE) for dimensionality reduction, effectively encoded diagnostic information, reducing over 30,000 features to 1/3500 of their original size. The approach enables the interpretation of extracted latent representations by computing the network distribution of the latent features and visualizing them on brain maps. 
  [<a href="https://arxiv.org/abs/2410.00068">arXiv preprint</a>]
  [<a href="https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2024.1397093/full">Frontiers in Psychiatry</a>]
</p>
</div>



### Some older projects / collaborative projects
<u>Statistical modeling and analysis methodologies for MRI and EEG</u> <br>
^ Decreased but diverse activity of cortical and thalamic neurons in consciousness-impairing rodent absence seizures [<a href="https://www.nature.com/articles/s41467-022-35535-4">Nature Communications</a>]  <br>
^ Slow and fast cortical cholinergic arousal is reduced in a mouse model of focal seizures with impaired consciousness [<a href="https://www.cell.com/cell-reports/fulltext/S2211-1247(24)01363-9">Cell Reports</a>] <br>
^ Neuronal rhythmicity and cortical arousal in a mouse model of absence epilepsy [<a href="https://www.sciencedirect.com/science/article/pii/S0014488624002516">Experimental Neurology</a>] <br>
^ Auditory stimuli can interrupt spike-wave discharges in a genetic absence epilepsy rodent model [<a href="https://aesnet.org/abstractslisting/auditory-stimuli-can-interrupt-spike-wave-discharges-in-a-genetic-absence-epilepsy-rodent-model">AES 2022 abstract</a>] <br>
^ Cortical slow waves and reduced cholinergic arousal in mouse model of focal limbic seizures with impaired behavior [<a href="https://aesnet.org/abstractslisting/cortical-slow-waves-and-reduced-cholinergic-arousal-in-mouse-model-of-focal-limbic-seizures-with-impaired-behavior">AES 2022 abstract</a>] <br>
<u>A ResNet-LSTM model for motor imagery classification based on EEG</u> 
[<a href="https://github.com/yijingf/EEG_Motor_Imagery">GitHub repo</a>]<br>
<u>DP Gradient Descent with Adaptive per-Iteration Privacy Budget</u> 
[<a href="https://github.com/xinyuan-zheng/DP-AGD/blob/main/Dec07_presentation.pdf">GitHub repo</a>]<br>
<!-- <u>A Variational Principle for Graphical Models</u> 
<a href="https://github.com/xinyuan-zheng/A_Variational_Principle_for_Graphical_Models/blob/main/presentation-Variational_Principle.pdf">GitHub repo</a><br> -->


{% include base_path %}

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}
