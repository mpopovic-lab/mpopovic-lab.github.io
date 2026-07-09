---
layout: single
title: Research
permalink: /research/
author_profile: true
classes: wide
---

## Research Interests

Marko Popovic's work combines theoretical physics with biological problems, with particular focus on:

- **Tissue Mechanics and Morphogenesis**: Understanding how tissues fold, flow, and shape themselves during development
- **Biological tissues as active amorphous solids**: Investigating mechanical properties of soft and amorphous materials, from epithelial tissues to glass-forming systems
- **Theoretical Models**: Vertex models, elastoplastic models, and particle-based descriptions of tissues

---

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 25px; margin: 40px 0;">

  <a href="#hydra-regeneration" style="text-decoration: none; color: inherit;">
    <div style="border: 1px solid #ddd; border-radius: 8px; overflow: hidden; transition: box-shadow 0.3s; height: 100%;">
      <div style="width: 100%; height: 300px; background-color: #e8f5e9; overflow: hidden;">
        <video autoplay loop muted playsinline style="width: 100%; height: 100%; object-fit: contain;">
          <source src="/assets/hydra_regeneration.mp4" type="video/mp4">
        </video>
      </div>
      <div style="padding: 20px;">
        <h3 style="margin-top: 0; color: #4CAF50;">Hydra Regeneration</h3>
        <p style="font-size: 0.9em; color: #666;">Understanding mechanical processes during regeneration</p>
      </div>
    </div>
  </a>

  <a href="#tissue-folding" style="text-decoration: none; color: inherit;">
    <div style="border: 1px solid #ddd; border-radius: 8px; overflow: hidden; transition: box-shadow 0.3s; height: 100%;">
      <div style="width: 100%; height: 300px; background-color: #f3e5f5; overflow: hidden;">
        <video autoplay loop muted playsinline style="width: 100%; height: 100%; object-fit: cover; object-position: right center;">
          <source src="/assets/tissue_folding.mp4" type="video/mp4">
        </video>
      </div>
      <div style="padding: 20px;">
        <h3 style="margin-top: 0; color: #9C27B0;">Tissue Folding</h3>
        <p style="font-size: 0.9em; color: #666;">Morphogenetic mechanisms and folding dynamics</p>
      </div>
    </div>
  </a>

  <a href="#tissue-plasticity" style="text-decoration: none; color: inherit;">
    <div style="border: 1px solid #ddd; border-radius: 8px; overflow: hidden; transition: box-shadow 0.3s; height: 100%;">
      <div style="width: 100%; height: 300px; background-color: #e3f2fd; overflow: hidden;">
        <video autoplay loop muted playsinline preload="auto" onended="this.play();" style="width: 100%; height: 100%; object-fit: contain;">
          <source src="/assets/alpha_0p12_gamma0_Nc200_compat.mp4" type="video/mp4">
          <source src="/assets/alpha_0p12_gamma0_Nc200.mp4" type="video/mp4">
        </video>
      </div>
      <div style="padding: 20px;">
        <h3 style="margin-top: 0; color: #2196F3;">Plasticity and Yielding</h3>
        <p style="font-size: 0.9em; color: #666;">Mechanical response and yielding transitions</p>
      </div>
    </div>
  </a>

  <a href="#order-disorder" style="text-decoration: none; color: inherit;">
    <div style="border: 1px solid #ddd; border-radius: 8px; overflow: hidden; transition: box-shadow 0.3s; height: 100%;">
      <div style="width: 100%; height: 300px; background-color: #fce4ec; overflow: hidden;">
        <video autoplay loop muted playsinline style="width: 100%; height: 100%; object-fit: contain;">
          <source src="/assets/order_disorder.mp4" type="video/mp4">
        </video>
      </div>
      <div style="padding: 20px;">
        <h3 style="margin-top: 0; color: #E91E63;">Order and Disorder</h3>
        <p style="font-size: 0.9em; color: #666;">Structural organization in biological tissues</p>
      </div>
    </div>
  </a>

</div>

<style>
a:hover div {
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}
</style>

---

## Hydra Regeneration {#hydra-regeneration}
{: style="color: #4CAF50;"}

Hydra regeneration provides a particularly clean system for connecting developmental biology with ideas from active matter. The tissue behaves as an active material whose large-scale organization is shaped by internally generated stresses, continuous remodeling, and orientational order in supracellular actin fibers. From this perspective, regenerating Hydra can be viewed as a living realization of active nematic physics, where topological defects, mechanical constraints, and material flows are not incidental features but part of the mechanism by which robust body axes and morphological structures emerge.

Recent work has made this picture more concrete by showing that mechanical strain is strongly concentrated at specific topological defect sites during regeneration and that external confinement can alter the number and arrangement of body axes that emerge from the same starting tissue.<sup>2,3</sup> A new preprint extends this picture further by showing that sufficiently strong geometric confinement can even reorient the inherited body axis itself, together with a large-scale remodeling of the supracellular actomyosin fiber organization.<sup>P1</sup> Together, these results argue that organizer formation and axial patterning are tightly coupled to geometry and mechanics, rather than being imposed only by a pre-existing biochemical program. In that sense, Hydra serves as a tractable model for mechanochemical self-organization in active living matter, where boundary conditions and internal stress patterns help steer developmental outcomes.<sup>2,3,P1</sup>

<ol>
  <li value="2">Y. Maroudas-Sacks, S. Suganthan, L. Garion, Y. Ascoli-Abbina, A. Westfried, N. Dori, I. Pasvinter, <u>M. Popović</u><sup>&#35;</sup>, K. Keren<sup>&#35;</sup>. <em>Mechanical strain focusing at topological defect sites in regenerating Hydra</em>, <strong>Development</strong>, 152(4) (2025).</li>
  <li value="3">Y. Maroudas-Sacks, L. Garion, S. Suganthan, <u>M. Popović</u>, K. Keren. <em>Confinement modulates axial patterning in regenerating Hydra</em>, <strong>PRX Life</strong>, 2, 043007 (2024).</li>
</ol>

<p><strong>P1.</strong> A. Westfried, L. Garion, <u>M. Popović</u>, K. Keren. <em>Body-Axis Reorientation in Regenerating Hydra under Geometric Confinement</em>, <strong>bioRxiv</strong>, <a href="https://doi.org/10.64898/2026.06.25.734673">10.64898/2026.06.25.734673</a> (2026).</p>

---

## Tissue Folding {#tissue-folding}
{: style="color: #9C27B0;"}

Tissue folding is one of the clearest manifestations of how local cellular processes are converted into organ-scale shape changes. This work asks how cell rearrangements, cell-shape changes, proliferation, and mechanical feedback combine to drive folds, eversion events, and other morphogenetic transformations in epithelial tissues. Much of this effort has focused on the Drosophila wing, where quantitative imaging and theory make it possible to connect measured cell dynamics to the emerging geometry of the tissue.<sup>5,14</sup>

Across this work, the goal is to move beyond descriptive accounts of folding toward predictive physical principles. Studies on mechanosensitive feedback, tissue flow inference, wing-disc eversion, and the mechanical consequences of cell division all point to the same general picture: folds and large deformations are collective phenomena that arise from distributed stresses rather than isolated local triggers.<sup>1,5,14</sup> A key objective is to identify which combinations of forces, material properties, and feedback rules make a tissue robustly fold in the right place and at the right time.

<ol>
  <li value="1">A. Tahaei, R. Piscitello-Gómez, S. Suganthan, G. Cwikla, J. F. Fuhrmann, N. A. Dye, and <u>M. Popović</u>. <em>Cell Divisions Imprint Long Lasting Elastic Strain Fields in Epithelial Tissues</em>, <strong>PRX Life</strong>, 3, 043008 (2025).</li>
  <li value="5">J. F. Fuhrmann, A. Krishna, J. Paijmans, C. Duclut, G. Cwikla, S. Eaton, <u>M. Popović</u>, F. Jülicher, C. D. Modes, and N. A. Dye. <em>Active shape programming drives Drosophila wing disc eversion</em>, <strong>Science Advances</strong>, 10(32) (2024).</li>
  <li value="14">N. A. Dye<sup>&#42;</sup>, <u>M. Popović</u><sup>&#42;</sup>, K. V. Iyer, J. F. Fuhrmann, R. Piscitello-Gómez, S. Eaton, F. Jülicher. <em>Self-organized patterning of cell morphology via mechanosensitive feedback</em>, <strong>eLife</strong>, 10, e57964 (2021).</li>
</ol>

---

## Plasticity and Yielding {#tissue-plasticity}
{: style="color: #2196F3;"}

Another major research direction concerns the mechanical response of tissues and other soft disordered materials under sustained driving. This work studies how materials deform elastically at short times, when they instead flow irreversibly, and how localized rearrangements cooperate to produce large-scale yielding. This includes both biological tissues, where activity and cell-generated forces drive remodeling, and more traditional amorphous systems, where creep, avalanches, and failure can be studied in a cleaner theoretical setting.<sup>6,7,11,19</sup>

This research spans epithelial yielding driven by random cellular traction, scaling theories of creep flow, thermally activated dynamics in amorphous solids, and elastoplastic descriptions of sudden failure. A recurring theme is that biological tissues can often be understood using concepts developed for glasses and yield-stress materials, but they also introduce new ingredients such as active forcing, growth, and remodeling.<sup>7,11,19</sup> The aim is to develop a common framework for plasticity that can explain when a tissue behaves like a solid, when it fluidizes, and how microscopic disorder shapes the path to flow or failure.

<ol>
  <li value="6">T. Divoux et al. <em>Ductile-to-brittle transition and yielding in soft amorphous materials: perspectives and open questions</em>, <strong>Soft Matter</strong>, 20, 6868-6888 (2024).</li>
  <li value="7">A. Amiri, C. Duclut, F. Jülicher, <u>M. Popović</u>. <em>Random traction yielding transition in epithelial tissues</em>, <strong>Physical Review Letters</strong>, 131, 188401 (2023).</li>
  <li value="11"><u>M. Popović</u>, T. W. J. de Geus, W. Ji, A. Rosso, M. Wyart. <em>Scaling description of creep flow in amorphous solids</em>, <strong>Physical Review Letters</strong>, 129(20), 208001 (2022).</li>
  <li value="19"><u>M. Popović</u>, T. W. J. de Geus, and M. Wyart. <em>Elastoplastic description of sudden failure in athermal amorphous materials during quasistatic loading</em>, <strong>Physical Review E</strong> (Rapid Communication), 98, 040901(R) (2018).</li>
</ol>

---

## Order and Disorder {#order-disorder}
{: style="color: #E91E63;"}

Biological tissues often operate in a regime between crystalline order and amorphous disorder, and this work examines how that intermediate structure is maintained and transformed during development. In epithelial systems, disorder is not simply noise that disappears over time: it can be sustained by proliferation, heterogeneity, and active remodeling, while ordering emerges only when those sources of variability are sufficiently reduced. A central question in this area is therefore how growth-driven disorder competes with the tendency of epithelial packings to crystallize.<sup>P1,P3</sup>

Recent preprints on the developing fruit-fly wing make this picture more precise. One shows that ongoing cell proliferation maintains cell-area polydispersity and accounts for most of the observed variance in cell area, thereby sustaining tissue disorder during growth.<sup>P1</sup> The other shows that decreasing cell-size heterogeneity drives a disorder-to-order transition toward crystalline packing, with a critical level of polydispersity separating disordered and ordered states; shear flow enhances large-scale alignment but is not required for crystallization itself.<sup>P3</sup> Together, these results frame tissue order as a balance between proliferation-driven heterogeneity and the physical tendency of epithelial packings to become ordered.<sup>P1,P3</sup>

<p><strong>P1.</strong> M. F. Staddon, N. A. Dye, <u>M. Popović</u><sup>&#35;</sup>, F. Jülicher<sup>&#35;</sup>. <em>Cell proliferation maintains cell area polydispersity in the growing fruit fly wing epithelium</em>, <strong>arXiv</strong>:2601.14509 (2026).</p>
<p><strong>P3.</strong> K. Chhajed, F. S. Gruber, R. Etournay, N. A. Dye, F. Jülicher, <u>M. Popović</u>. <em>Cell size heterogeneity controls crystallization of the developing fruit fly wing</em>, <strong>arXiv</strong>:2505.05437 (2025).</p>

---
