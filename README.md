# TransfiniteMeshPrimitives (TFMP) — demo

<p align="center">
  Visual demo for building template-based 3D primitives for Gmsh GEO generation and transfinite meshing workflows, with face attachment, mesh settings, physical groups, and GEO export.
</p>

<p align="center">
  <img src="assets/main_icon.png" alt="TFMP icon" width="500">
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#highlights">Highlights</a> •
  <a href="#featured-interaction">Featured Interaction</a> •
  <a href="#examples">Examples</a> •
  <a href="#repository-scope">Repository Scope</a> •
  <a href="#contact">Contact</a>
</p>

---

## Overview

TFMP is a visual authoring tool concept for constructing structured 3D geometry from predefined primitive templates and preparing Gmsh-compatible GEO descriptions.

This repository is presented as a **demo showcase** of the interface and workflow design.  
It does **not** include source code, executable binaries, or packaged releases.

<p align="center">
  <img src="assets/demo/main_demo.gif" alt="TFMP main demo" width="900">
</p>

---

## Highlights

- Template-based creation of 3D primitives
- Primitive library including rectangular prisms, triangular prisms, sector-based shapes, and annular-sector variants
- Interactive editing of size, position, and rotation
- Face-to-face attachment workflow between primitives
- Physical group assignment for point, line, surface, and volume entities
- Edge mesh settings for transfinite meshing workflows
- Geometry preparation for Gmsh GEO export
- 3D preview with geometry labels and workspace grid

---

## Featured Interaction

### Face attachment

Attach one primitive face to another through a face-matching workflow for structured geometry composition.

<p align="center">
  <img src="assets/demo/face_attachment.gif" alt="Face attachment demo" width="900">
</p>

---

## Examples

This section presents representative device-oriented examples created in TFMP, with each figure showing a direct comparison between the TFMP-authored geometry and the corresponding downstream result in [Gmsh](https://gmsh.info/).

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

This repository does **not** provide:

- Source code
- Executable binaries
- Packaged releases

---

## Contact

**Xi-Jun Fang**  
Email: fangmbf552688@gmail.com
