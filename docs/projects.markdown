---
layout: page
title: Research projects
permalink: /proj/

---

<style>
.project-card {
  padding: 20px 25px;
  margin-bottom: 30px;
  border-radius: 8px;
  transition: background-color 0.3s ease, box-shadow 0.3s ease;
}
.project-card:hover {
  background-color: #f7f7f7;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}
</style>

<div class="project-card" markdown="1">

[**Inpainting the Neural Picture: Inferring Unrecorded Brain Area Dynamics from Multi-Animal Datasets**](https://neurips.cc/virtual/2025/loc/san-diego/poster/117392)

<img src="/assets/images/proj4.png" alt="drawing" style="display:block; margin:0 auto; width:80%; padding:10px 0;">
<p align = "justify">
Understanding how distributed brain circuits drive an animal’s behavior requires recordings from interconnected cortical and subcortical areas. While Neuropixels enable simultaneous recordings from multiple areas, no single experiment covers all areas of interest, and, in a given recorded area, different neurons are recorded across sessions and animals. This poses a central challenge: how can we integrate multi-animal datasets to study interactions across brain areas that are not recorded simultaneously in any single session? We introduce NeuroPaint, a masked autoencoding approach for inferring the dynamics of unrecorded brain areas. By training across animals with overlapping subsets of recorded regions, NeuroPaint learns to reconstruct neural dynamics in unrecorded areas by leveraging shared structure across individuals. 
<br><br>
<a href="https://dandiarchive.org/dandiset/000363?search=susu+chen&pos=1"><b>MAP Dataset</b></a> | <a href="https://viz.internationalbrainlab.org/app"><b>IBL Dataset</b></a> | <a href="https://github.com/tinaxia2016/NeuroPaint"><b>Code</b></a>
</p>

</div>

<div class="project-card" markdown="1">

[**Stimulus-dependent communication within and between visual areas**](https://www.cell.com/iscience/fulltext/S2589-0042(24)01737-1)

<img src="/assets/images/proj3.jpg" alt="drawing" style="display:block; margin:0 auto; width:100%; padding:10px 0;">
<p align = "justify">
In collaboration with Dr. Adam Kohn’s lab at Albert Einstein College of Medicine, I analyzed simultaneously recorded spike data from monkey primary visual cortex and secondary visual cortex from Utah arrays, tetrodes, and Neuropixels probes. Previous work showed that trial-to-trial variability is not only shared within each visual area, but also shared between visual areas, which is often interpreted as communication between areas. However, how this communication depends on stimuli had remained unexplored. I addressed this gap by developing statistical models to capture the neural data simultaneously recorded from two visual areas. Guided by the circuit mechanism underlying shared variability, I designed novel statistical models that concisely describe the stimulus-dependence of within-area and inter-areal
shared variability. This work characterized the stimulus-dependent "communication" (shared variability) within-area and across area with a parsimonious stastiscal model (generalized affine model) and provided a simple circuit dynamics explanation for this dependence. 
<br><br>
<a href="https://crcns.org/data-sets/vc/v1v2-1/"><b>Dataset 1</b></a> | <a href="https://datadryad.org/stash/dataset/doi:10.5061/dryad.h9w0vt4s0"><b>Dataset 2</b></a> | <a href="https://github.com/tinaxia2016/NeuronalVariabilityStatsModels"><b>Code</b></a>
</p>

</div>

<div class="project-card" markdown="1">

[**Stable representation of a naturalistic movie emerge from unstable single neuronal responses**](https://abstracts.g-node.org/conference/BC20/abstracts#/uuid/feecff01-04aa-4940-ae10-d64ab5929370)


<img src="/assets/images/proj2.png" alt="drawing" style="float:left;width:50%; padding: 10px 25px 15px 0px;">
<p align = "justify">
In collaboration with Dr. Michael Goard’s lab at UC Santa Barbara, I analyzed chronic calcium imaging data from mouse primary visual cortex. We found that single neuronal responses to a repeated naturalistic movie drifted across weeks. However, by applying a dimensionality reduction method (Isomap) and an unsupervised 
learning method (<a href="https://fietelab.mit.edu/code/">SPUD</a>), we extracted a stable one-dimensional representation of time in the naturalistic movie from population activity across weeks. 
Further analysis showed that the stable representation was mediated by the precise timing and coordinations between episodic activity in single neuronal responses.

<br><br>
<a href="https://doi.org/10.25349/D9M606"><b>Dataset</b></a> | <a href="https://github.com/ahwillia/tensortools"><b>TCA</b></a> | <a href="https://fietelab.mit.edu/code/"><b>SPUD</b></a>
</p>

<div style="clear: both;"></div>

</div>

<div class="project-card" markdown="1">

[**Mixed representation of stimulus-driven and -independnent variables in single neurons**](https://journals.physiology.org/doi/abs/10.1152/jn.00431.2020?casa_token=MO5OvecahU8AAAAA:mya07nSYZ6fJgq26bY6leUwm8Dn7GTopzJqMgQmUL1_aZSQjF2nwbfDcRf0EBSWYxX26pHe6nE0)


<img src="/assets/images/proj1.png" alt="drawing" style="float:left;width:50%; padding: 10px 25px 15px 0px;">
<p align = "justify">
Most of the neurons in visual cortex have highly variable responses from trial to trial during repeated visual stimulation. It is not clear 
how those neurons contribute to encoding different variables. Using a multi-way analysis method (<a href="https://github.com/ahwillia/tensortools">TCA</a>), we extracted two types of latent factors shared across neurons: 
</p>
- latent factors consistent across trials
- latent factors inconsistent across trials
<p align = "justify">
We found that a single neuron's response reliability imposes only a weak constraint on its encoding capabilities. 
</p>

</div>

