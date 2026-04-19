# TransfiniteMeshPrimitives (TFMP) - demo

Visual demo for building template-based 3D primitives for Gmsh GEO generation and transfinite meshing, with face attachment, mesh settings, physical groups, and GEO export.

<p align="center">
  <img src="assets/demo/main_demo.gif" alt="TFMP main demo" width="900">
</p>

## Overview

TFMP is a visual authoring tool concept for constructing structured 3D geometry from predefined primitive templates and exporting Gmsh-compatible GEO descriptions.

This repository is presented as a **demo showcase** of the interface and workflow design.  
It does **not** include source code or executable releases.

## Highlights

- Template-based creation of 3D primitives
- Interactive editing of size, position, and rotation
- Face-to-face attachment workflow between primitives
- Physical group assignment for point / line / surface / volume entities
- Edge mesh settings for transfinite meshing workflows
- Gmsh GEO export-oriented geometry preparation
- 3D preview with geometry labels and workspace grid

## Demo

### 1. Primitive authoring

Create geometry from predefined primitive templates, including rectangular prisms, triangular prisms, sector-based shapes, and annular sector variants.

<p align="center">
  <img src="assets/demo/primitive_editor.png" alt="Primitive editor" width="900">
</p>

### 2. Interactive 3D preview

Preview the constructed geometry in 3D with workspace grid, view switching, and direct visual inspection of primitive placement.

<p align="center">
  <img src="assets/demo/preview_scene.png" alt="3D preview scene" width="900">
</p>

### 3. Face attachment

Attach one primitive face to another through a face-matching workflow for structured geometry composition.

<p align="center">
  <img src="assets/demo/face_attachment.gif" alt="Face attachment demo" width="900">
</p>

### 4. Physical groups

Assign geometry entities into physical groups for downstream Gmsh workflows.

<p align="center">
  <img src="assets/demo/physical_groups.png" alt="Physical groups panel" width="900">
</p>

### 5. Mesh settings

Configure edge-wise mesh settings for transfinite meshing workflows, including node count, spacing mode, and ratio control.

<p align="center">
  <img src="assets/demo/mesh_settings.png" alt="Mesh settings dialog" width="900">
</p>

### 6. GEO export workflow

Prepare geometry and grouping information for Gmsh GEO export.

<p align="center">
  <img src="assets/demo/geo_export.png" alt="GEO export workflow" width="900">
</p>

## Supported primitive templates

- Rect Prism
- Tri Prism
- Sector Circle
- Sector Ellipse
- Sector Concave Circle
- Sector Concave Ellipse
- Annular Sector Circle
- Annular Sector Ellipse

## Example workflow

1. Choose a primitive template
2. Define dimensions and transform parameters
3. Add multiple primitives into the scene
4. Arrange or attach faces between primitives
5. Assign physical groups
6. Configure mesh settings for edges
7. Export GEO for Gmsh-based meshing workflow

## Repository scope

This repository is intended for:

- visual demonstration
- UI/UX presentation
- workflow explanation
- feature showcase

This repository does **not** provide:

- source code
- executable binaries
- packaged releases

## Notes

TFMP focuses on **geometry authoring and GEO preparation**, not direct mesh generation.  
The generated geometry is intended to be passed to **Gmsh**, where the actual mesh is generated according to GEO definitions and transfinite meshing settings.

## Contact

**Xi-Jun Fang**  
Email: fangmbf552688@gmail.com
