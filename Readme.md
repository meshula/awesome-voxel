# Awesome Voxel [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Projects and resources relating to coding for Voxels

Key -

- :page_facing_up: Research project or paper
- :computer: Code
- :art: Tool

## Contents

- [Deformations](#deformations)
- [File Loaders](#file-loaders)
- [Foundations](#foundations)
- [Mapping](#mapping)
- [Physics](#physics)
- [Proceduralism](#proceduralism)
- [Reconstruction](#reconstruction)
- [Rendering](#rendering)
- [Sparse Volumes](#sparse-volumes)
- [Surfacers](#surfacers)
- [Tools](#tools)
- [Voxelizers](#voxelizers)
- [Wavefront Collapse](#wavefront-collapse)
- [Contribute](#contribute)
- [License](#license)

## Foundations

- (https://www.merl.com/publications/docs/TR2000-15.pdf) :page_facing_up: Adaptively Sampled Distance Fields: A General Representation of Shape for Computer Graphics, Sarah F. Frisken, Ronald N. Perry, Alyn P. Rockwood, Thouis R. Jones, TR2000-15 December 2000

## Sparse Volumes

- [OpenVdb](http://www.openvdb.org/) :computer: Dreamworks' hierarchical sparse volume representation and manipulation library
- [OctoMap](http://octomap.github.io/) :computer: :art: An Efficient Probabilistic 3D Mapping Framework Based on Octrees

## File Loaders

- [EnkiMI](https://github.com/dougbinks/enkiMI) :computer: Enki Minecraft file loader
- https://github.com/aiekick/MagicaVoxel_File_Writer Aiekick's Magica Voxel file writer

## Mapping

- [https://web.stanford.edu/~zollhoef/papers/EG18_RecoSTAR/paper.pdf] :page_facing_up: State of the Art on 3D Reconstruction with RGB-D Cameras
- [voxblox](https://github.com/ethz-asl/voxblox) :computer: :art:  A volumetric library that stores Truncated Signed Distance Fields in voxels
- [tsdf Fusion](https://github.com/andyzeng/tsdf-fusion) :computer: Fusing Truncated Signed Distance Files

## Voxelizers

- [VoxSurf](https://github.com/sylefeb/VoxSurf) :computer: :art: C++ surface voxelizer; converts STL files to VOX files
- [SdfGen](https://github.com/christopherbatty/SDFGen) :computer: :art: commandline utility to generate grid-based signed distance fields from triangle meshes
- [Voxelizer](https://github.com/karimnaaji/voxelizer) :computer: Header only voxelizer in C
- [Discregid](https://github.com/InteractiveComputerGraphics/Discregrid) Discretize signed distance fields, includes cubic interpolation
- [Haar Tree](https://github.com/mikolalysenko/haar-tree-3d) :computer: Haar Tree
- [Voxel Hashing](https://github.com/niessner/VoxelHashing) :computer: Voxel Hashing, by Niessner et al, Siggraph Asia 2017
- [Voxel Panda](https://github.com/ooper-shlab/VoxelPanda-Swift) Using SceneKit and ModelIO to voxelize a mesh, in Swift

## Reconstruction

- [https://github.com/vsitzmann/deepvoxels] :computer: :page_facing_up: Deep Voxels has a neural rendering function that uses voxel occupancy for an occlusion estimate.

## Surfacers
- [https://github.com/emilk/Dual-Contouring] :computer: Dual Contouring
- [https://github.com/nickgildea/fast_dual_contouring] Dual contouring, includes a SIMD QEF implementation
- [https://github.com/Lin20/BinaryMeshFitting] :computer: Another contouring scheme, includes QEF 
- [https://github.com/tdhooper/glsl-marching-cubes] :computer: Marching Cubes

## Wavefront Collapse

- [VoxModSynth](https://github.com/sylefeb/VoxModSynth) :computer:  C++ implementation of wave function collabse for model synthesis

## Deformations

- [VolumeDeform](https://graphics.stanford.edu/~niessner/papers/2016/5volumeDeform/innmannn2016deform.pdf) :page_facing_up: VolumeDeform: Real-time Volumetric Non-rigid Reconstruction

## Rendering

- [Fast Ray Box Intersections](http://www.jcgt.org/published/0007/03/04/) :computer: :page_facing_up: A Ray-Box Intersection Algorithm and
Efficient Dynamic Voxel Rendering
- [Voxel Rendering Techniques](https://medium.com/@fogleman/voxel-rendering-techniques-fa8d869457ca) :page_facing_up: Optimal triangulation & more
- [CPU Sparse Voxel Octree](https://github.com/tunabrain/sparse-voxel-octrees) :computer: tunabrain's SVO raytracer
- [Efficient Sparse Voxel Octrees](http://research.nvidia.com/publication/efficient-sparse-voxel-octrees) :computer: :page_facing_up: Efficient Spare Volume Octrees by Laine and Karras
- [Voxlap](http://advsys.net/ken/voxlap.htm) :computer: Ken Silverman's influential early voxel terrain engine. It's currently not that easy to compile, but it of definite historical interest.
- [https://github.com/s-macke/VoxelSpace] VoxelSpace - old school height map rendering
- [https://github.com/tommyettinger/IsoVoxel] IsoVoxel - render isometric views of VOX files
- [http://www.cse.chalmers.se/edu/year/2017/course/TDA362/grid.pdf] :page_facing_up: A Fast Voxel Traversal Algorithm for Ray Tracking, by Amanatides and Woo

## Physics

- [Terrain Physics](https://zeuxcg.org/2017/12/30/voxel-terrain-physics/) :page_facing_up: Voxel Terrain Physics and Collision

## Proceduralism

- [Eric's MagicaVoxel Shaders](https://github.com/CodingEric/Erics-MagicaVoxel-Shaders-Collection) :computer:
- [Lachlan's MagicaVoxel Shaders](https://github.com/lachlanmcdonald/magicavoxel-shaders) :computer:
- [Goxel's voxel shape grammar](https://blog.noctua-software.com/goxel-procedural.html) :computer:
- [patStar's MagicaVoxel Shaders](https://github.com/patStar/voxelShader) :computer:

## Tools

- [MagicaVoxel](https://ephtracy.github.io) :art: MagicaVoxel Editor and Visualizer
- [Goxel](http://guillaumechereau.github.io/goxel/) :computer: :art: Open Source 3D voxel editor for Mac, Windows, iOS, and Linux.
- [Vengi](https://mgerhardy.github.io/engine/) :computer: :art: Cross platform voxel engine and tools like voxel editor, converter, and thumbnailer.
- [VoxQL](https://github.com/heptal/VoxQL) :computer: :art: QuickLook Generator for MagicaVoxel files on Mac.
- [https://github.com/mikelovesrobots/mmmm] A collection of everything needed to populate a city

## Contribute

Contributions are welcome - see the[contribution guidelines](contributing.md)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and
related or neighboring rights to this work.
