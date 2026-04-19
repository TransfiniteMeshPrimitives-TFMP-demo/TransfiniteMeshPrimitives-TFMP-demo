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
- GEO export-oriented geometry preparation for Gmsh
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

This section presents representative geometry setups created in TFMP and their corresponding downstream results in Gmsh.

### Example 1. Multi-primitive composition

An example of combining multiple primitives into a larger structured geometry through placement and face attachment.

<p align="center">
  <img src="assets/demo/examples/example_01_tfmp.png" alt="Example 1 in TFMP" width="440">
  <img src="assets/demo/tfmp_to_gmsh/example_01_gmsh.png" alt="Example 1 in Gmsh" width="440">
</p>

<p align="center">
  <sub>Left: geometry authored in TFMP. Right: the corresponding GEO-driven geometry or mesh viewed in Gmsh.</sub>
</p>

### Example 2. Sector-based geometry construction

An example showing sector and annular-sector primitives used to build curved structured geometry.

<p align="center">
  <img src="assets/demo/examples/example_02_tfmp.png" alt="Example 2 in TFMP" width="440">
  <img src="assets/demo/tfmp_to_gmsh/example_02_gmsh.png" alt="Example 2 in Gmsh" width="440">
</p>

<p align="center">
  <sub>Left: geometry authored in TFMP. Right: the corresponding GEO-driven geometry or mesh viewed in Gmsh.</sub>
</p>

### Example 3. Physical-group-ready setup

An example prepared for downstream Gmsh workflows with geometry entities organized into physical groups.

<p align="center">
  <img src="assets/demo/examples/example_03_tfmp.png" alt="Example 3 in TFMP" width="440">
  <img src="assets/demo/tfmp_to_gmsh/example_03_gmsh.png" alt="Example 3 in Gmsh" width="440">
</p>

<p align="center">
  <sub>Left: geometry authored in TFMP. Right: the corresponding GEO-driven geometry or mesh viewed in Gmsh.</sub>
</p>

---

## Example Workflow

1. Choose a primitive template
2. Define dimensions and transform parameters
3. Add multiple primitives into the scene
4. Arrange primitives or attach faces between them
5. Assign physical groups
6. Configure edge mesh settings
7. Export GEO for Gmsh-based meshing workflows

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
