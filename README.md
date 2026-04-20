# TransfiniteMeshPrimitives (TFMP) — demo

<p align="center">
  Visual demo for authoring template-based 3D primitives for <a href="https://gmsh.info/">Gmsh</a> GEO workflows, featuring editable geometry construction, face attachment, transfinite mesh control, physical groups, and GEO export.
</p>

<p align="center">
  <img src="assets/main_icon.png" alt="TFMP icon" width="500">
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#why-tfmp">Why TFMP?</a> •
  <a href="#featured-interaction">Featured Interaction</a> •
  <a href="#examples">Examples</a> •
  <a href="#repository-scope">Repository Scope</a> •
  <a href="#contact">Contact</a>
</p>

---

## Overview

TFMP is a visual authoring tool concept for constructing structured 3D geometry from predefined primitive templates and preparing Gmsh-compatible GEO descriptions for downstream meshing workflows.

Directly writing Gmsh GEO scripts is flexible, but it can become less convenient when structured 3D geometry must be built, edited, rearranged, and kept consistent across transfinite settings, physical groups, and entity IDs. TFMP is designed to make that workflow more editable, visual, and workflow-oriented before GEO export.

This repository is presented as a **demo showcase** of the interface and workflow design only.

<p align="center">
  <img src="assets/demo/main_demo.gif" alt="TFMP main demo" width="900">
</p>

<p align="center">
  <sub>Short animated workflow preview. Loading may take a few seconds on GitHub.</sub>
</p>

---

## Why TFMP?

Compared with writing Gmsh GEO files manually, TFMP is designed to make structured geometry authoring more editable, visual, and workflow-oriented.

- Build structured 3D geometry from reusable primitive templates instead of rewriting repeated GEO blocks by hand
- Edit dimensions, placement, and rotation through an interactive UI instead of repeatedly modifying GEO scripts
- Assemble multi-part structures through face-to-face attachment instead of manual geometric alignment
- Configure edge-wise transfinite mesh settings, including node count, distribution mode, and ratio control
- Organize physical groups for point, line, surface, and volume entities before export
- Keep geometry entities and exported IDs more consistent for downstream Gmsh workflows
- Preview the constructed geometry visually with workspace grid and labels before GEO export

---

## Featured Interaction

### Face attachment

Attach one primitive face to another through a face-matching workflow for structured geometry assembly.

<p align="center">
  <img src="assets/demo/face_attachment.gif" alt="Face attachment demo" width="900">
</p>

---

## Examples

This section presents representative device-oriented examples created in TFMP, with each figure showing a direct comparison between the TFMP-authored geometry and the corresponding downstream result in Gmsh.

### Example 1. MOSFET structure

A structured device example showing how TFMP can be used to build and organize MOSFET-like geometry for downstream Gmsh GEO-based workflows.

<p align="center">
  <img src="assets/demo/examples/example_mosfet_comparison.png" alt="MOSFET example: TFMP and Gmsh comparison" width="900">
</p>

<p align="center">
  <sub>TFMP-authored geometry and its downstream result in Gmsh.</sub>
</p>

### Example 2. Ring resonator structure

A curved-geometry example showing how sector-based primitive templates can be used to construct ring-resonator-like structures and pass them into Gmsh workflows.

<p align="center">
  <img src="assets/demo/examples/example_ring_resonator_comparison.png" alt="Ring resonator example: TFMP and Gmsh comparison" width="900">
</p>

<p align="center">
  <sub>TFMP-authored geometry and its downstream result in Gmsh.</sub>
</p>

---

## Repository Scope

This repository is intended for:

- Visual demonstration
- UI/UX presentation
- Workflow explanation
- Feature showcase

It is a demo-only repository and does **not** provide:

- Source code
- Executable binaries
- Packaged releases

---

## Contact

**Xi-Jun Fang**  
Email: fangmbf552688@gmail.com
