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
  <a href="#demo">Demo</a> •
  <a href="#example-geometries">Example Geometries</a> •
  <a href="#tfmp-to-gmsh">TFMP to Gmsh</a> •
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

## Demo

### 1. Face attachment

Attach one primitive face to another through a face-matching workflow for structured geometry composition.

<p align="center">
  <img src="assets/demo/face_attachment.gif" alt="Face attachment demo" width="900">
</p>

### 2. Physical groups

Assign geometry entities into physical groups for downstream Gmsh workflows.

<p align="center">
  <img src="assets/demo/physical_groups.png" alt="Physical groups panel" width="900">
</p>

### 3. Mesh settings

Configure edge-wise mesh settings for transfinite meshing workflows, including node count, spacing mode, and ratio control.

<p align="center">
  <img src="assets/demo/mesh_settings.png" alt="Mesh settings dialog" width="900">
</p>

---

## Example Geometries

This section presents representative geometry setups created in TFMP to demonstrate how template-based primitives can be combined into more structured 3D authoring workflows.

### Example 1. Multi-primitive composition

An example of combining multiple primitives into a larger structured geometry through placement and face attachment.

<p align="center">
  <img src="assets/demo/examples/example_01_tfmp.png" alt="Example geometry 1 in TFMP" width="900">
</p>

### Example 2. Sector-based geometry construction

An example showing sector and annular-sector primitives used to build curved structured geometry.

<p align="center">
  <img src="assets/demo/examples/example_02_tfmp.png" alt="Example geometry 2 in TFMP" width="900">
</p>

### Example 3. Physical-group-ready setup

An example prepared for downstream Gmsh workflows with geometry entities organized into physical groups.

<p align="center">
  <img src="assets/demo/examples/example_03_tfmp.png" alt="Example geometry 3 in TFMP" width="900">
</p>

---

## TFMP to Gmsh

TFMP focuses on **geometry authoring and GEO preparation**.  
The actual mesh is generated later in **Gmsh** according to the exported GEO definitions and transfinite meshing settings.

The following examples show the correspondence between the geometry authored in TFMP and its downstream interpretation in Gmsh.

### Example A. TFMP geometry → Gmsh result

<p align="center">
  <img src="assets/demo/tfmp_to_gmsh/example_a_tfmp.png" alt="TFMP example A" width="440">
  <img src="assets/demo/tfmp_to_gmsh/example_a_gmsh.png" alt="Gmsh example A" width="440">
</p>

<p align="center">
  <sub>Left: geometry authored in TFMP. Right: the corresponding GEO-based geometry / meshing result viewed in Gmsh.</sub>
</p>

### Example B. TFMP geometry → Gmsh result

<p align="center">
  <img src="assets/demo/tfmp_to_gmsh/example_b_tfmp.png" alt="TFMP example B" width="440">
  <img src="assets/demo/tfmp_to_gmsh/example_b_gmsh.png" alt="Gmsh example B" width="440">
</p>

<p align="center">
  <sub>Left: geometry authored in TFMP. Right: the corresponding GEO-based geometry / meshing result viewed in Gmsh.</sub>
</p>

### Example C. TFMP geometry → Gmsh result

<p align="center">
  <img src="assets/demo/tfmp_to_gmsh/example_c_tfmp.png" alt="TFMP example C" width="440">
  <img src="assets/demo/tfmp_to_gmsh/example_c_gmsh.png" alt="Gmsh example C" width="440">
</p>

<p align="center">
  <sub>Left: geometry authored in TFMP. Right: the corresponding GEO-based geometry / meshing result viewed in Gmsh.</sub>
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
