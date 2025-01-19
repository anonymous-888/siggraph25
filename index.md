---
layout: project_page
permalink: /

title: Textured 3D Regenerative Morphing with 3D Diffusion Prior
authors:
    Paper 680
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Textured 3D morphing creates smooth and plausible interpolation sequences between two 3D objects, focusing on transitions in both shape and texture. This is important for creative applications like visual effects in filmmaking. Previous methods rely on establishing point-to-point correspondences and determining smooth deformation trajectories, which inherently restrict them to shape-only morphing on untextured, topologically aligned datasets. This reliance leads to labor-intensive preprocessing and poor generalization. To overcome these challenges, we propose a method for 3D regenerative morphing using a 3D diffusion prior. Unlike previous approaches that depend on explicit correspondences and deformations, our method eliminates the additional need for obtaining correspondence and uses the 3D diffusion prior to generate morphing. Specifically, we first introduce a 3D diffusion model and interpolate the source and target information at three levels: initial noise, model parameters, and condition features. We then explore an Attention Fusion strategy to generate more smooth morphing sequences. To further improve the plausibility of semantic interpolation and the generated 3D surfaces, we propose two strategies: (a) Token Reordering, where we match approximate tokens based on semantic analysis to guide implicit correspondences in the denoising process of the diffusion model, and (b) Low-Frequency Enhancement, where we enhance low-frequency signals in the tokens to improve the quality of generated surfaces. Experimental results show that our method achieves superior smoothness and plausibility in 3D morphing across diverse cross-category object pairs, offering a novel regenerative approach for 3D morphing with textured representations.
        </div>
    </div>
</div>

---

## More Cases

![](/static/image/video_ours.gif =800x450)

*Figure 1: More morphing cases.*


