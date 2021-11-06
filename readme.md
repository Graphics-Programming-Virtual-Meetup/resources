# Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A hand-picked list of graphics programming resources by graphics programming virtual meetup attendees

- Meetup page: https://www.meetup.com/Graphics-Programming-Virtual-Meetup
- Join our Discord: https://discord.gg/TsTDb4uYfR
- Follow use on Twitter: https://twitter.com/GraphicsMeetup
- Youtube Channel: https://www.youtube.com/channel/UCbX05PBAE-582PYaRXdjRnw

## Contribute

Contributions welcome! To submit a PR, please first read the [contribution guidelines](contributing.md) first. You can also join our [Discord Server](https://discord.gg/TsTDb4uYfR) and make suggestions there.

## Table of Contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<details>
<summary>Table of Contents</summary>

- [Beginner friendly](#beginner-friendly)
- [Meta-links](#meta-links)
- [Overview](#overview)
  - [Books](#books)
  - [Courses](#courses)
- [Math](#math)
  - [Tutorials](#tutorials)
  - [Books](#books-1)
  - [Homogeneous Coordinate](#homogeneous-coordinate)
  - [Rotation](#rotation)
  - [Geometric Algebra](#geometric-algebra)
  - [Curves and Surfaces](#curves-and-surfaces)
  - [Implementing Math Library](#implementing-math-library)
- [Ray Tracing](#ray-tracing)
  - [Intro to Ray Tracing](#intro-to-ray-tracing)
  - [Ray Tracing Books](#ray-tracing-books)
  - [BVH](#bvh)
  - [Variance Reduction](#variance-reduction)
  - [Intersection](#intersection)
  - [Denoising](#denoising)
  - [GPU Ray Tracing](#gpu-ray-tracing)
- [Rasterization](#rasterization)
  - [Graphics Pipeline](#graphics-pipeline)
  - [Software Rasterization](#software-rasterization)
- [Graphics Techniques](#graphics-techniques)
  - [Depth Buffer](#depth-buffer)
  - [Normal Mapping](#normal-mapping)
  - [Shadow](#shadow)
  - [Ambient Occlusion](#ambient-occlusion)
  - [Reflection](#reflection)
  - [Transparency](#transparency)
  - [Ray Marching and SDF](#ray-marching-and-sdf)
  - [Mipmapping](#mipmapping)
  - [Line, Edge, and Outline Drawing](#line-edge-and-outline-drawing)
  - [Tessellation](#tessellation)
- [PBR](#pbr)
- [Shader Programming](#shader-programming)
- [Compute](#compute)
  - [Introduction to compute shader](#introduction-to-compute-shader)
  - [GPU Architecture](#gpu-architecture)
  - [GPU-driven rendering](#gpu-driven-rendering)
  - [Parallel Algorithms](#parallel-algorithms)
- [Color, HDR, and Tone Mapping](#color-hdr-and-tone-mapping)
- [Sampling](#sampling)
- [Animation](#animation)
- [Geometry](#geometry)
  - [Geometry representations](#geometry-representations)
  - [Iso-surface methods](#iso-surface-methods)
  - [Libraries](#libraries)
- [APIs](#apis)
  - [OpenGL](#opengl)
  - [Vulkan](#vulkan)
  - [WebGL](#webgl)
  - [WebGPU](#webgpu)
- [Programming](#programming)
  - [Meta-links](#meta-links-1)
  - [Engine Development](#engine-development)
  - [High-level Programming](#high-level-programming)
  - [Game loop](#game-loop)
- [Tools](#tools)
  - [Debuggers](#debuggers)
- [Assets](#assets)

</details>
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Beginner friendly

Here is a list of resources suitable for beginners,
though intermediate or advanced folks can also benefit from them.

- [Learn OpenGL](https://learnopengl.com/) - learnopengl.com is the definitive resource for learning real-time renderer techniques as beginners. Even though it is an OpenGL tutorial, it also teaches rendering techniques at the same time.
- [Ray Tracing in One Weekend series](https://raytracing.github.io/) - Those three short books explain basic concepts of path tracing and implement a software renderer from scratch.
- [CMU's introductory to Computer Graphics course](https://www.youtube.com/playlist?list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E) -
A comprehensive introduction to various topics in computer graphics.
- [Catlike Coding](https://catlikecoding.com/) - Focus on C# and shaders in Unity
- [Book Of Shaders](https://thebookofshaders.com/) - The author introduces shaders from an artistic perspective, and the book covers many topics that more engineering-focused resources such as "Learn OpenGL" won't cover.

## Meta-links
Resources that curate other resources. Some of meta links are omitted here if they are mentioned in other categories.

- [GPU Optimization for GameDev](https://gist.github.com/silvesthu/505cf0cbf284bb4b971f6834b8fec93d)
- [Volumetric Clouds Resources List](https://gist.github.com/pixelsnafu/e3904c49cbd8ff52cb53d95ceda3980e)
- [graphics resources](https://github.com/mattdesl/graphics-resources)
- [Awesome Computer Graphics](https://github.com/luisnts/awesome-computer-graphics)
- [Awesome Graphics Libraries - engines & frameworks](https://github.com/jslee02/awesome-graphics-libraries)
- [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision)
- [Awesome Gamedev](https://github.com/ellisonleao/magictools)  - lots of graphics related stuff
- [Physics-Based Animation](http://www.physicsbasedanimation.com/) - learning resources and papers

## Overview
### Books
- [Graphics Codex](https://graphicscodex.courses.nvidia.com/app.html) - Free
- [Real-Time Rendering, Fourth Edition](https://www.amazon.com/Real-Time-Rendering-Fourth-Tomas-Akenine-M%C3%B6ller/dp/1138627003)
- [Fundamentals of Computer Graphics 5th Edition](https://www.amazon.com/Fundamentals-Computer-Graphics-Steve-Marschner/dp/0367505037)

### Courses
- [CMU's introductory to Computer Graphics course](https://www.youtube.com/playlist?list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E)
- [6.837: Introduction to Computer Graphics (fall 2020)](https://youtube.com/playlist?list=PLQ3UicqQtfNuBjzJ-KEWmG1yjiRMXYKhh)
- [Introduction to Computer Graphics - Cem Yuksel](https://youtube.com/playlist?list=PLplnkTzzqsZTfYh4UbhLGpI5kGd5oW_Hh)

## Math

### Tutorials
- [[video series] Math For Game Devs](https://www.youtube.com/playlist?list=PLImQaTpSAdsD88wprTConznD1OY1EfK_V) - Video Series from Freya Holmér

### Books
- [Mathematics for Computer Graphics](https://www.amazon.com/Mathematics-Computer-Graphics-Undergraduate-Science/dp/1447173341)
- [Mathematics for 3D Game Programming and Computer Graphics, 3rd Edition](https://www.amazon.com/Mathematics-Programming-Computer-Graphics-Third/dp/1435458869)
- [Foundations of Game Engine Development, Volume 1: Mathematics](https://www.amazon.com/Foundations-Game-Engine-Development-Mathematics/dp/0985811749) -Introduces math routines with implementations. It also touchs grassman algebra.

### Homogeneous Coordinate
- [A trip down the graphics pipeline: the homogeneous perspective transform](https://www.ece.uvic.ca/~bctill/20004/additional/homcoord/00210494.pdf)

### Rotation
- [Gimbal lock confusion - Computer Graphics Stack Exchange](https://computergraphics.stackexchange.com/questions/12273/gimbal-lock-confusion)

### Geometric Algebra
- [Let's remove Quaternions from every 3D Engine](https://marctenbosch.com/quaternions/)

### Curves and Surfaces
- [[video] The Beauty of Bézier Curves](https://www.youtube.com/watch?v=aVwxzDHniEw)

### Implementing Math Library
- [On Vector Math Libraries](https://www.reedbeta.com/blog/on-vector-math-libraries/)

## Ray Tracing
### Intro to Ray Tracing
- [An Improved Illumination Model for Shaded Display](https://www.cs.drexel.edu/~david/Classes/Papers/p343-whitted.pdf) - Turner Whitted's original Ray Tracing Paper
- [Ray Tracing in One Weekend series](https://raytracing.github.io/)
### Ray Tracing Books
- [Physically Based Rendering: From Theory To Implementation Third Edition](https://www.pbr-book.org/)
- [Ray Tracing Gems](https://www.realtimerendering.com/raytracinggems/rtg/index.html)
- [Ray Tracing Gems II](https://www.realtimerendering.com/raytracinggems/rtg2/index.html)
### BVH
- [A Survey on Bounding Volume Hierarchies for Ray Tracing](https://meistdan.github.io/publications/bvh_star/paper.pdf) - Excellent overview paper
- [bvh - A modern C++ BVH construction and traversal library](https://github.com/madmann91/bvh)
### Variance Reduction
- [Distributing Monte Carlo Errors as a Blue Noise in Screen Space by Permuting Pixel Seeds Between Frames](https://hal.archives-ouvertes.fr/hal-02158423/file/blueNoiseTemporal2019_slides.pdf)

### Intersection
- [Static Object Intersections - Real Time Rendering Resource Page](https://www.realtimerendering.com/intersections.html) - A collection of intersection algorithms


### Denoising
- [Ray Tracing Denoising - Alain.xyz](https://alain.xyz/blog/ray-tracing-denoising)
- [Ray Tracing Filtering - Alain.xyz](https://alain.xyz/blog/ray-tracing-filtering)

### GPU Ray Tracing
- [Megakernels Considered Harmful: Wavefront Path Tracing on GPUs](https://research.nvidia.com/sites/default/files/pubs/2013-07_Megakernels-Considered-Harmful/laine2013hpg_paper.pdf)

## Rasterization
### Graphics Pipeline
- [A trip through the Graphics Pipeline 2011](https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index/)
- [Creative Use of GPU Fixed-Function Hardware](https://asawicki.info/news_1745_creative_use_of_gpu_fixed-function_hardware)

### Software Rasterization
- [ssloy/tinyrenderer](https://github.com/ssloy/tinyrenderer) - A short tutorial on writing a software rasterizer. Be careful that the tutorial has some rough edges.
- [A Parallel Algorithm for Polygon Rasterization](https://www.cs.drexel.edu/~david/Classes/Papers/comp175-06-pineda.pdf)
- [Scratchapixel: Rasterization Stage](https://www.scratchapixel.com/lessons/3d-basic-rendering/rasterization-practical-implementation/rasterization-stage)
- [Triangle rasterization in practice](https://fgiesen.wordpress.com/2013/02/08/triangle-rasterization-in-practice/)
- [Optimizing the basic rasterizer](https://fgiesen.wordpress.com/2013/02/10/optimizing-the-basic-rasterizer/)
- [High-Performance Software Rasterization on GPUs](https://users.aalto.fi/~laines9/publications/laine2011hpg_paper.pdf)
- [Line Rasterization slides, MIT EECS 6.837, Teller and Durand](http://groups.csail.mit.edu/graphics/classes/6.837/F02/lectures/6.837-7_Line.pdf)

## Graphics Techniques

### Depth Buffer
- [Depth Precision Visualized](https://developer.nvidia.com/content/depth-precision-visualized)
### Normal Mapping
- [Three Normal Mapping Techniques Explained For the Mathematically Uninclined](https://www.gamedeveloper.com/programming/three-normal-mapping-techniques-explained-for-the-mathematically-uninclined)
- [Normal Mapping - Learn OpenGL](https://learnopengl.com/Advanced-Lighting/Normal-Mapping)

### Shadow
- [Shadow Mapping - LearnOpenGL](https://learnopengl.com/Advanced-Lighting/Shadows/Shadow-Mapping)
- [Efficient Shadows from Many Lights](https://efficientshading.com/wp-content/uploads/s2015_shadows.pdf)
- [Experiments in Hybrid Raytraced Shadows](https://interplayoflight.wordpress.com/2021/05/15/experiments-in-hybrid-raytraced-shadows/)
- [Michał Olejnik - Raytraced Shadows in Call of Duty: Modern Warfare video presentation](https://www.youtube.com/watch?v=VXp-HEAw-l4) 

### Ambient Occlusion
- [Learn OpenGL: SSAO](https://learnopengl.com/Advanced-Lighting/SSAO)
- [John Chapman SSAO Tutorial](http://john-chapman-graphics.blogspot.com/2013/01/ssao-tutorial.html)
- [Screen Space Ambient Occlusion - Louis Bavoil, Miguel Sainz](https://developer.download.nvidia.com/SDK/10.5/direct3d/Source/ScreenSpaceAO/doc/ScreenSpaceAO.pdf)
- [Know your SSAO artifacts](https://mtnphil.wordpress.com/2013/06/26/know-your-ssao-artifacts/)
- [Practical Realtime Strategies for Accurate Indirect Occlusion](https://iryoku.com/downloads/Practical-Realtime-Strategies-for-Accurate-Indirect-Occlusion.pdf)

### Reflection
- [Screen-Space Reflections Explained](https://jhstrom.blogspot.com/2021/03/screen-space-reflections-explained.html)

### Transparency
- [Learn OpenGL: OIT](https://learnopengl.com/Guest-Articles/2020/OIT/Introduction)

### Ray Marching and SDF
- [Graphics Codex: Ray Marching](https://graphicscodex.courses.nvidia.com/app.html?page=_rn_rayMrch)
- [Distant functions for primitives - Inigo Quilez](https://www.iquilezles.org/www/articles/distfunctions/distfunctions.htm)
- [soft shadows in raymarched SDFs - 2010](https://www.iquilezles.org/www/articles/rmshadows/rmshadows.htm)

### Mipmapping
- [Pyramidal Parametrics](http://www.cs.cmu.edu/afs/cs.cmu.edu/academic/class/15869-f11/www/readings/williams83_mipmap.pdf) - Original Mipmap paper

### Line, Edge, and Outline Drawing
#### Triangulated line
- [Drawing Lines is Hard](https://mattdesl.svbtle.com/drawing-lines-is-hard)
- [Instanced Line Rendering Part I](https://wwwtyro.net/2019/11/18/instanced-lines.html)
- [Instanced Line Rendering Part II: Alpha blending](https://wwwtyro.net/2021/10/01/instanced-lines-part-2.html)

#### Outline
- [5 ways to draw an outline](https://alexanderameye.github.io/notes/rendering-outlines/)
- [The Quest for Very Wide Outlines](https://bgolus.medium.com/the-quest-for-very-wide-outlines-ba82ed442cd9)

### Tessellation
- [Tutorial 30: Basic Tessellation](https://ogldev.org/www/tutorial30/tutorial30.html) - Adds tutorial for Tessellation

## PBR
- [PBR - Learn OpenGL](https://learnopengl.com/PBR/Theory)
- [Physically Based Rendering in Filament](https://google.github.io/filament/Filament.html)
- [Everything (or most things) wrong with learnopengl.com/PBR/Theory](https://docs.google.com/document/d/1ZLT1-fIek2JkErN9ZPByeac02nWipMbO89oCW2jxzXo/edit)
- [Crash Course in BRDF Implementation](https://boksajak.github.io/files/CrashCourseBRDF.pdf)
- [Physically Based Shading at Disney](https://blog.selfshadow.com/publications/s2012-shading-course/burley/s2012_pbs_disney_brdf_notes_v3.pdf)
- [Deriving Lambertian BRDF from first principles](https://sakibsaikia.github.io/graphics/2019/09/10/Deriving-Lambertian-BRDF-From-First-Principles.html)

## Shader Programming
- [The Book of Shaders](https://thebookofshaders.com/)
- [shadertoy smoothstep demo](https://www.shadertoy.com/view/sdyGRW)
- [Shader Derivative Functions](http://www.aclockworkberry.com/shader-derivative-functions/) - useful for normals
- [How to read shader assembly](https://interplayoflight.wordpress.com/2021/04/18/how-to-read-shader-assembly/)
- [ShaderToy Advanced Tricks](https://shadertoyunofficial.wordpress.com/2021/03/09/advanced-tricks/) 

## Compute
### Introduction to compute shader
- [Introduction to Compute Shaders](https://anteru.net/blog/2018/intro-to-compute-shaders/)
- [More Compute Shaders](https://anteru.net/blog/2018/more-compute-shaders/)
- [Even more Compute Shaders](https://anteru.net/blog/2018/even-more-compute-shaders/)
- [Compute Shader Glossary](https://github.com/googlefonts/compute-shader-101/blob/main/docs/glossary.md)

### GPU Architecture
- [CIS 565 GPU Programming and Architecture](http://cis565-fall-2021.github.io/)
- [Gentle introduction to GPUs inner workings](https://vksegfault.github.io/posts/gentle-intro-gpu-inner-workings/)
- [GCN – two ways of latency hiding and wave occupancy](https://bartwronski.com/2014/03/27/gcn-two-ways-of-latency-hiding-and-wave-occupancy/)
- [Breaking Down Barriers](https://therealmjp.github.io/posts/breaking-down-barriers-part-1-whats-a-barrier/)
- [How does a GPU Shader work?](https://aras-p.info/texts/files/2018Academy%20-%20GPU.pdf)
- [Compute Shaders: Optimize your engine using compute / Lou Kramer, AMD](https://www.youtube.com/watch?v=0DLOJPSxJEg) 

### GPU-driven rendering
- [GPU Driven Rendering - Siggraph 2015](http://advances.realtimerendering.com/s2015/aaltonenhaar_siggraph2015_combined_final_footer_220dpi.pdf)

### Parallel Algorithms
- [Parallel Prefix Sum (Scan) with CUDA](http://www.eecs.umich.edu/courses/eecs570/hw/parprefix.pdf)
- [Thinking Parallel, Part I: Collision Detection on the GPU](https://developer.nvidia.com/blog/thinking-parallel-part-i-collision-detection-gpu/)
- [Thinking Parallel, Part II: Tree Traversal on the GPU](https://developer.nvidia.com/blog/thinking-parallel-part-ii-tree-traversal-gpu/)
- [Thinking Parallel, Part III: Tree Construction on the GPU](https://developer.nvidia.com/blog/thinking-parallel-part-iii-tree-construction-gpu/)

## Color, HDR, and Tone Mapping
- [Supporting Native HDR Monitors - OurMachinery](https://ourmachinery.com/post/supporting-native-hdr-monitors/)
- [Introduction to Color Theory for Games, Art and Tech - Shahriar Shahrabi](https://shahriyarshahrabi.medium.com/introduction-to-color-theory-for-games-art-and-tech-67bd4c8607d7)

## Sampling
- [A Pixel is not a Little Square!](http://alvyray.com/Memos/CG/Microsoft/6_pixel.pdf) - classic paper
- [Basics of Image Resampling](https://entropymine.com/imageworsener/resample/)

## Animation
- [Learn OpenGL: Skeletal Animation](https://learnopengl.com/Guest-Articles/2020/Skeletal-Animation)
- [(video) Animation Programming Basics](https://youtu.be/Jkv0pbp0ckQ)
- [(video) Animation Graphs](https://youtu.be/R-T3Mk5oDHI)

## Geometry
### Geometry representations
- [Lecture 10: Meshes and Manifolds (CMU 15-462/662)](https://youtu.be/HePDHsp8spU) - Great overview, and also spend significant time on the half-edge data structure

### Iso-surface methods
- [Interactive explanation of marching cubes and dual contouring](https://wordsandbuttons.online/interactive_explanation_of_marching_cubes_and_dual_contouring.html)
- [Polygonising a scalar field (Marching Cubes)](http://paulbourke.net/geometry/polygonise/)
- [Dual Contouring Tutorial](https://www.boristhebrave.com/2018/04/15/dual-contouring-tutorial/)
- [The Transvoxel Algorithm](https://transvoxel.org/)

### Libraries
- [Geometry Central](https://geometry-central.net/) - a modern C++ library of data structures and algorithms for geometry processing, with a particular focus on surface meshes

## APIs
### OpenGL
- [docs.gl](http://docs.gl/) - OpenGL API Documentation

#### Tutorials
- [Learn OpenGL](https://learnopengl.com/) - The highly recommended tutorial

#### Meta-links
- [Awesome OpenGL](https://project-awesome.org/eug/awesome-opengl) - Curated List for OpenGL

### Vulkan
- [Spec](https://www.khronos.org/registry/vulkan/specs/1.2-extensions/html/index.html) It is a good idea to keep it open while doing Vulkan Programming.
#### Tutorials
- [Vulkan Guide](https://vkguide.dev/) The best "Vulkan Tutorial" available.
- [TU Wien: Vulkan Lecture Series](https://www.youtube.com/playlist?list=PLmIqTlJ6KsE1Jx5HV4sd2jOe3V1KMHHgn)
- [vk_mini_path_tracer tutorial](https://github.com/nvpro-samples/vk_mini_path_tracer) A relative small tutorial that focus on path tracing using Vulkan's ray tracing API.
- [3D Graphics Rendering Cookbook](https://www.amazon.com/Graphics-Rendering-Cookbook-comprehensive-algorithms/dp/1838986197) - Nonfree book

#### Meta-links
- [Awesome Vulkan](https://github.com/vinjn/awesome-vulkan)
- [Great Resources - Vulkan Guide](https://vkguide.dev/docs/great_resources)

#### Sychronization
- [Understanding Vulkan Synchronization](https://www.khronos.org/blog/understanding-vulkan-synchronization)
- [Vulkan Timeline Semaphores](https://www.khronos.org/blog/vulkan-timeline-semaphores)

#### Vulkan Compute
- [A simple Vulkan Compute example](https://www.duskborn.com/posts/a-simple-vulkan-compute-example/)
- [Vulkan Subgroup tutorial. AKA wavefronts](https://www.khronos.org/blog/vulkan-subgroup-tutorial)

#### Libraries
- [vk-bootstrap](https://github.com/charles-lunarg/vk-bootstrap) Library that simplify the Vulkan initialization boilerplate.
- [VulkanMemoryAllocator](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator) Memory allocation library that simplifies Vulkan memory allocation and provides decent performance.
- [volk](https://github.com/zeux/volk) Meta-loader for Vulkan that allows you to dynamically load entrypoints required to use Vulkan. It also simplify the use of Vulkan extensions.
- [SPIRV-Reflect](https://github.com/KhronosGroup/SPIRV-Reflect) - Can be used to extract descriptor and push constant information from SPIRV

#### Performance Best Practice
- [Writing an efficient Vulkan renderer](https://zeux.io/2020/02/27/writing-an-efficient-vulkan-renderer/)

#### Others
- [Vulkan Diagram](https://github.com/David-DiGioia/vulkan-diagrams)

### WebGL
- [Awesome WebGL](https://project-awesome.org/sjfricke/awesome-webgl)

### WebGPU
- [Spec](https://gpuweb.github.io/gpuweb/)
#### Tutorials
- [Learn wgpu](https://sotrh.github.io/learn-wgpu/)

## Programming
### Meta-links
- [Awesome C](https://project-awesome.org/inputsh/awesome-c#game-programming)
- [Awesome C++](https://project-awesome.org/fffaraz/awesome-cpp)
- [Awesome Rust](https://github.com/rust-unofficial/awesome-rust)
### Engine Development
- [The Shader Permutation Problem - Part 1: How Did We Get Here?](https://therealmjp.github.io/posts/shader-permutations-part1/)
- [The Shader Permutation Problem - Part 2: How Do We Fix It?](https://therealmjp.github.io/posts/shader-permutations-part2/)
### High-level Programming
- [Game Programming Patterns](http://gameprogrammingpatterns.com/)
### Game loop
- [Game Loop - Game Programming Patterns](http://gameprogrammingpatterns.com/game-loop.html)
- [Fix Your Timestep!](https://gafferongames.com/post/fix_your_timestep/)

## Tools
### Debuggers
- [RenderDoc](https://renderdoc.org/)
- [Nvidia Nsight Graphics](https://developer.nvidia.com/nsight-graphics)
- [Radeon™ GPU Profiler (AMD)](https://github.com/GPUOpen-Tools/radeon_gpu_profiler)
- [Intel® GPA](https://www.intel.com/content/www/us/en/developer/tools/graphics-performance-analyzers/overview.html)
- [SpectorJS (WebGL)](https://github.com/BabylonJS/Spector.js)

## Assets
- [McGuire Computer Graphics Archive](http://casual-effects.com/data/index.html) - OBJ format scenes
- [ORCA: Open Research Content Archive](https://developer.nvidia.com/orca) - Free large graphics scene samples
- [ambientCG](https://ambientcg.com/) - Public Domain materials for Physically Based Rendering
- [Rendering Resources - Benedikt Bitterli](https://benedikt-bitterli.me/resources/) - Scenes in Tungsten, Mitsuba and pbrt-v3 formats
