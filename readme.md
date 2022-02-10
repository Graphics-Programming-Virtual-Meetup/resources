# Graphics Programming Resources

A hand-picked list of graphics programming resources maintained by graphics programming virtual meetup attendees.

- Meetup page: https://www.meetup.com/Graphics-Programming-Virtual-Meetup
- Join our Discord: https://discord.gg/TsTDb4uYfR
- Follow us on Twitter: https://twitter.com/GraphicsMeetup
- YouTube channel: https://www.youtube.com/channel/UCbX05PBAE-582PYaRXdjRnw

## Contents
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<details>
<summary>Table of Contents</summary>

- [Beginner friendly](#beginner-friendly)
- [Meta-links](#meta-links)
- [Overview](#overview)
  - [Books](#books)
  - [Courses](#courses)
- [Career Advice](#career-advice)
- [Math](#math)
  - [Tutorials](#tutorials)
  - [Books](#books-1)
  - [Homogeneous Coordinate](#homogeneous-coordinate)
  - [Rotation](#rotation)
  - [Geometric Algebra](#geometric-algebra)
  - [Curves and Surfaces](#curves-and-surfaces)
  - [Implementing Math Library](#implementing-math-library)
  - [Circular/Spherical harmonics](#circularspherical-harmonics)
- [Ray Tracing](#ray-tracing)
  - [Intro to Ray Tracing](#intro-to-ray-tracing)
  - [Ray Tracing Books](#ray-tracing-books)
  - [Algortihms](#algortihms)
  - [BVH](#bvh)
  - [Sampling & Variance Reduction](#sampling--variance-reduction)
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
  - [Line, Edge, and Outline Drawing](#line-edge-and-outline-drawing)
  - [Text Rendering](#text-rendering)
  - [Tessellation](#tessellation)
  - [Voxel Rendering](#voxel-rendering)
  - [Volume Rendering](#volume-rendering)
  - [Dithering](#dithering)
  - [Sprite Rendering](#sprite-rendering)
- [PBR](#pbr)
- [Textures](#textures)
  - [Mipmapping](#mipmapping)
  - [Texture Compression](#texture-compression)
  - [Texture Bombing](#texture-bombing)
- [Shader Programming](#shader-programming)
- [Compute](#compute)
  - [Introduction to compute shader](#introduction-to-compute-shader)
  - [GPU Architecture](#gpu-architecture)
  - [Parallel Algorithms](#parallel-algorithms)
- [Color, HDR, and Tone Mapping](#color-hdr-and-tone-mapping)
- [Sampling](#sampling)
- [Animation](#animation)
- [Geometry](#geometry)
  - [Geometry representations](#geometry-representations)
  - [Iso-surface methods](#iso-surface-methods)
  - [Libraries](#libraries)
- [Physics and Simulation](#physics-and-simulation)
  - [Physics-Based Animation](#physics-based-animation)
  - [Attractors](#attractors)
- [APIs](#apis)
  - [OpenGL](#opengl)
  - [Vulkan](#vulkan)
  - [DirectX 12](#directx-12)
  - [WebGL](#webgl)
  - [WebGPU](#webgpu)
- [System Design](#system-design)
  - [Renderer Architecture](#renderer-architecture)
  - [GPU-driven rendering](#gpu-driven-rendering)
- [Assets Format](#assets-format)
- [Scene Description](#scene-description)
- [General Programming](#general-programming)
  - [Meta-links](#meta-links-1)
  - [Engine Development](#engine-development)
  - [High-level Programming](#high-level-programming)
  - [Game loop](#game-loop)
  - [Floating-point numbers](#floating-point-numbers)
  - [Memory Allocation & Management](#memory-allocation--management)
- [Tools/libraries](#toolslibraries)
  - [Debuggers](#debuggers)
  - [Profilers](#profilers)
  - [Denoiser](#denoiser)
- [Assets](#assets)

</details>
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Beginner friendly

Here is a list of resources suitable for beginners,
though intermediate or advanced folks can also benefit from them.

- [Learn OpenGL](https://learnopengl.com/) - Learn OpenGL is the definitive resource for learning real-time renderer techniques as beginners. Even though it is an OpenGL tutorial, it also teaches rendering techniques at the same time.
- [Ray Tracing in One Weekend series](https://raytracing.github.io/) - Those three short books explain basic concepts of path tracing and implement a software renderer from scratch.
- 🎥 [CMU's introductory to Computer Graphics course](https://www.youtube.com/playlist?list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E) -
A comprehensive introduction to various topics in computer graphics.
- [Catlike Coding](https://catlikecoding.com/) - Focuses on C# and shaders in Unity.
- [Book Of Shaders](https://thebookofshaders.com/) - The author introduces shaders from an artistic perspective, and the book covers many topics that more engineering-focused resources such as "Learn OpenGL" won't cover.

## Meta-links
Resources that curate other resources. Some of meta links are omitted here if they are mentioned in other categories.

- [GPU Optimization for GameDev](https://gist.github.com/silvesthu/505cf0cbf284bb4b971f6834b8fec93d)
- [Volumetric Clouds Resources List](https://gist.github.com/pixelsnafu/e3904c49cbd8ff52cb53d95ceda3980e)
- [graphics resources](https://github.com/mattdesl/graphics-resources)
- [Awesome Computer Graphics](https://github.com/luisnts/awesome-computer-graphics)
- [Awesome Graphics Libraries - engines & frameworks](https://github.com/jslee02/awesome-graphics-libraries)
- [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision)
- [Awesome Gamedev](https://github.com/ellisonleao/magictools) - Lots of graphics related stuff.
- [Physics-Based Animation](http://www.physicsbasedanimation.com/) - Contains learning resources and papers.
- [Digital Morphogenesis Resources - Info About Some Different Simulation Techniques](https://github.com/jasonwebb/morphogenesis-resources)
- [Graphics Programming Weekly - Article Database](https://www.jendrikillner.com/article_database/)

## Overview
### Books
- [Graphics Codex](https://graphicscodex.courses.nvidia.com/app.html) - Free book that contains chapters on physically-based shading and rendering, coding projects, and reference pages.
- [Real-Time Rendering, Fourth Edition](https://www.amazon.com/Real-Time-Rendering-Fourth-Tomas-Akenine-M%C3%B6ller/dp/1138627003)
- [Fundamentals of Computer Graphics 5th Edition](https://www.amazon.com/Fundamentals-Computer-Graphics-Steve-Marschner/dp/0367505037)

### Courses
- [CMU's introductory to Computer Graphics course](https://www.youtube.com/playlist?list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E)
- [6.837: Introduction to Computer Graphics (fall 2020)](https://youtube.com/playlist?list=PLQ3UicqQtfNuBjzJ-KEWmG1yjiRMXYKhh)
- [Introduction to Computer Graphics - Cem Yuksel](https://youtube.com/playlist?list=PLplnkTzzqsZTfYh4UbhLGpI5kGd5oW_Hh)

## Career Advice
- [Finding Your Home in Game Graphics Programming](http://alextardif.com/LearningGraphics.html) - Presents a high level overview of the rendering world and resources for getting started in the different specializations
- [Insider guide to tech interviews](https://bartwronski.com/2022/01/04/insider-guide-to-tech-interviews/) - An in-depth analysis of the interview process for experienced developers

## Math

### Tutorials
- 🎥 [Math For Game Devs](https://www.youtube.com/playlist?list=PLImQaTpSAdsD88wprTConznD1OY1EfK_V) - Video Series from Freya Holmér

### Books
- [immersive linear algebra](http://immersivemath.com/ila/index.html) - Free online book with interactive figures.
- [Mathematics for Computer Graphics](https://www.amazon.com/Mathematics-Computer-Graphics-Undergraduate-Science/dp/1447173341)
- [Mathematics for 3D Game Programming and Computer Graphics, 3rd Edition](https://www.amazon.com/Mathematics-Programming-Computer-Graphics-Third/dp/1435458869)
- [Foundations of Game Engine Development, Volume 1: Mathematics](https://www.amazon.com/Foundations-Game-Engine-Development-Mathematics/dp/0985811749) - Introduces math routines with implementations. It also touchs Grassman algebra.

### Homogeneous Coordinate
- [A trip down the graphics pipeline: the homogeneous perspective transform](https://www.ece.uvic.ca/~bctill/20004/additional/homcoord/00210494.pdf)

### Rotation
- [Gimbal lock confusion - Computer Graphics Stack Exchange](https://computergraphics.stackexchange.com/questions/12273/gimbal-lock-confusion)

### Geometric Algebra
- [Let's remove Quaternions from every 3D Engine](https://marctenbosch.com/quaternions/) - Introduces *Rotors* in Geometric Algebra.

### Curves and Surfaces
- 🎥 [The Beauty of Bézier Curves](https://www.youtube.com/watch?v=aVwxzDHniEw)

### Implementing Math Library
- [On Vector Math Libraries](https://www.reedbeta.com/blog/on-vector-math-libraries/)
- [GDC18 - Linear Algebra Upgraded](http://www.terathon.com/gdc18_lengyel.pdf) - Designs an affine space type library with distinct vector and point types, and also uses template and union hacks to implement vector swizzling in C++.
- 🎥 [CppCon 2018: Valentin Galea “Rapid Prototyping of Graphics Shaders in Modern C++”](https://www.youtube.com/watch?v=8FoAxasNssA) - Also implemented swizzling with similar techniques.

### Circular/Spherical harmonics
- [Circular Harmonics: Digging in circles](https://valdes.cc/articles/ch.html)
- [Spherical Harmonics for Beginners](https://dickyjim.wordpress.com/2013/09/04/spherical-harmonics-for-beginners/) - Cover the fundamentals of using Spherical Harmonics without delving into the math deeply
- [Spherical Harmonics in Graphics: A Brief Overview](https://gen-graphics.blogspot.com/2017/11/spherical-harmonics-in-graphics-brief.html)
- [Spherical Harmonic Lighting](https://simonstechblog.blogspot.com/2011/12/spherical-harmonic-lighting.html)
- [Stupid Spherical Harmonics (SH) Tricks](https://www.ppsloan.org/publications/StupidSH36.pdf)
- [Spherical Harmonic Lighting: The Gritty Details](http://www.cse.chalmers.se/~uffe/xjobb/Readings/GlobalIllumination/Spherical%20Harmonic%20Lighting%20-%20the%20gritty%20details.pdf)

## Ray Tracing
### Intro to Ray Tracing
- [Ray Tracing in One Weekend series](https://raytracing.github.io/)
- [An Improved Illumination Model for Shaded Display](https://www.cs.drexel.edu/~david/Classes/Papers/p343-whitted.pdf) - Turner Whitted's original Ray Tracing paper.
- 🎥 [Lecture 18: Monte Carlo Rendering (CMU 15-462/662)](https://youtu.be/FUZJNlRqrAc) - Including a very good introduction of importance sampling.

### Ray Tracing Books
- [Physically Based Rendering: From Theory To Implementation Third Edition](https://www.pbr-book.org/) - The definitive book for offline rendering.
- [Ray Tracing Gems](https://www.realtimerendering.com/raytracinggems/rtg/index.html) - Like other "gems" book, it contains standalone chapters on various ray tracing topics.
- [Ray Tracing Gems II](https://www.realtimerendering.com/raytracinggems/rtg2/index.html)
- [Advanced Global Illumination](https://www.amazon.com/Advanced-Global-Illumination-Philip-Dutre/dp/1568813074) - An advanced book that focuses on light transport theory.

### Algortihms
- [Bidirectional Estimators for Light Transport](https://www.cs.jhu.edu/~misha/ReadingSeminar/Papers/Veach94.pdf) - Introduces *bidirectional path tracing*.
- [Monte Carlo Methods for Light Transport Simulation](https://graphics.stanford.edu/papers/veach_thesis/) - the Academy Award-winning PhD thesis by Eric Veach. It starts from *bidirectional light transport algorithms* and introduces *multiple importance sampling* and *Metropolis light transport*

### BVH
- [A Survey on Bounding Volume Hierarchies for Ray Tracing](https://meistdan.github.io/publications/bvh_star/paper.pdf) - Excellent overview paper on BVH.
- [bvh - A modern C++ BVH construction and traversal library](https://github.com/madmann91/bvh) - Implements various algorithms for BVH traversal and construction.

### Sampling & Variance Reduction
- 🎥 [Lecture 19: Variance Reduction (CMU 15-462/662)](https://youtu.be/IQhLk_XaFc8)
- [Stratified Sampling of Spherical Triangles](http://www.graphics.cornell.edu/pubs/1995/Arv95c.pdf)
- [Distributing Monte Carlo Errors as a Blue Noise in Screen Space by Permuting Pixel Seeds Between Frames](https://hal.archives-ouvertes.fr/hal-02158423/file/blueNoiseTemporal2019_slides.pdf)
- [A Low-Discrepancy Sampler that Distributes Monte Carlo Errors as a Blue Noise in Screen Space](https://belcour.github.io/blog/slides/2019-sampling-bluenoise/index.html)
- [Rendering in Real Time with Spatiotemporal Blue Noise Textures](https://developer.nvidia.com/blog/rendering-in-real-time-with-spatiotemporal-blue-noise-textures-part-1/) series

### Intersection
- [Static Object Intersections - Real Time Rendering Resource Page](https://www.realtimerendering.com/intersections.html) - A collection of intersection algorithms.

### Denoising
- [Ray Tracing Denoising - Alain.xyz](https://alain.xyz/blog/ray-tracing-denoising)
- [Ray Tracing Filtering - Alain.xyz](https://alain.xyz/blog/ray-tracing-filtering)
- [Edge-Avoiding À-Trous Wavelet Transform for fast Global Illumination Filtering](https://jo.dreggn.org/home/2010_atrous.pdf) - Classic paper that introduces a fast and simple filtering for real-time ray tracing denoising

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
- [Percentage-Closer Soft Shadows](https://developer.download.nvidia.com/shaderlibrary/docs/shadow_PCSS.pdf)
- [Efficient Shadows from Many Lights](https://efficientshading.com/wp-content/uploads/s2015_shadows.pdf)
- [Experiments in Hybrid Raytraced Shadows](https://interplayoflight.wordpress.com/2021/05/15/experiments-in-hybrid-raytraced-shadows/)
- 🎥 [Michał Olejnik - Raytraced Shadows in Call of Duty: Modern Warfare video presentation](https://www.youtube.com/watch?v=VXp-HEAw-l4)
- [Using Blue Noise For Raytraced Soft Shadows](https://blog.demofox.org/2020/05/16/using-blue-noise-for-raytraced-soft-shadows/)

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
- [Compositing digital images](https://graphics.pixar.com/library/Compositing/paper.pdf)
- [Visual glBlendFunc + glBlendEquation Tool](https://www.andersriggelsen.dk/glblendfunc.php)

### Ray Marching and SDF
- [Graphics Codex: Ray Marching](https://graphicscodex.courses.nvidia.com/app.html?page=_rn_rayMrch)
- [Distant functions for primitives - Inigo Quilez](https://www.iquilezles.org/www/articles/distfunctions/distfunctions.htm)
- [soft shadows in raymarched SDFs - 2010](https://www.iquilezles.org/www/articles/rmshadows/rmshadows.htm)

### Line, Edge, and Outline Drawing
#### Triangulated line
- [Drawing Lines is Hard](https://mattdesl.svbtle.com/drawing-lines-is-hard) - Summarizes the problem of GPU line primitives and introduces techniques for drawing triangulated lines.
- [Instanced Line Rendering Part I](https://wwwtyro.net/2019/11/18/instanced-lines.html) - Builds on the foundation from "Drawing Lines is Hard" and uses instance rendering to draw lines.
- [Instanced Line Rendering Part II: Alpha blending](https://wwwtyro.net/2021/10/01/instanced-lines-part-2.html) - Continue of the above article, and introduces a way to do alpha-blending with triangulated lines.

#### Outline
- [5 ways to draw an outline](https://alexanderameye.github.io/notes/rendering-outlines/)
- [The Quest for Very Wide Outlines](https://bgolus.medium.com/the-quest-for-very-wide-outlines-ba82ed442cd9)

### Text Rendering
- [Learn OpenGL: Text Rendering](https://learnopengl.com/In-Practice/Text-Rendering)
- [bitmap font renderer](https://jmickle66666666.github.io/blog/techart/2019/12/18/bitmap-font-renderer.html)

### Tessellation
- [Tutorial 30: Basic Tessellation](https://ogldev.org/www/tutorial30/tutorial30.html)

### Voxel Rendering
- [VoxelSpace](https://github.com/s-macke/VoxelSpace)

### Volume Rendering
- [Structured Volume Sampling](https://github.com/huwb/volsample) - MIT-licensed implementation of Structured Volume Sampling technique, along with simple framework for comparing other techniques.

### Dithering
- [Dithering on the GPU](http://alex-charlton.com/posts/Dithering_on_the_GPU/) - describe a novel algorithm for ordered dithering based on an arbitrary palette

### Sprite Rendering
- [Modern (Bindless) Sprite Batch for Vulkan (and more!)](https://jorenjoestar.github.io/post/modern_sprite_batch/)

### Atmosphere Scattering
- [Precomputed Atmospheric Scattering](https://hal.inria.fr/inria-00288758/document)
- [Precomputed Atmospheric Scattering: a New Implementation](https://ebruneton.github.io/precomputed_atmospheric_scattering/)

## PBR
- [Physically Based Rendering in Filament](https://google.github.io/filament/Filament.html)
- [PBR - Learn OpenGL](https://learnopengl.com/PBR/Theory)
- [Everything (or most things) wrong with learnopengl.com/PBR/Theory](https://docs.google.com/document/d/1ZLT1-fIek2JkErN9ZPByeac02nWipMbO89oCW2jxzXo/edit)
- [Crash Course in BRDF Implementation](https://boksajak.github.io/files/CrashCourseBRDF.pdf)
- [Physically Based Shading at Disney](https://blog.selfshadow.com/publications/s2012-shading-course/burley/s2012_pbs_disney_brdf_notes_v3.pdf)
- [Deriving Lambertian BRDF from first principles](https://sakibsaikia.github.io/graphics/2019/09/10/Deriving-Lambertian-BRDF-From-First-Principles.html)
- [Basics of physically-based rendering](https://www.researchgate.net/publication/262326548_Basics_of_physically-based_rendering)

## Textures
### Mipmapping
- [Pyramidal Parametrics](http://www.cs.cmu.edu/afs/cs.cmu.edu/academic/class/15869-f11/www/readings/williams83_mipmap.pdf) - The original Mipmap paper.

### Texture Compression
- [Understanding BCn Texture Compression Formats](https://www.reedbeta.com/blog/understanding-bcn-texture-compression-formats/) - describes a family of lossy hardware-based texture compression formats called BCn

### Texture Bombing
- [GPU Gems Chapter 20. Texture Bombing](https://developer.download.nvidia.com/books/HTML/gpugems/gpugems_ch20.html)
- [Texture bombing 3 samples](https://www.shadertoy.com/view/4tyGWK) - a shader from Inigo Quilez (modified by huwb) that shows how to perform the GPU Gems technique using 3 texture samples instead of 4! 
- [On Histogram-Preserving Blending for Randomized Texture Tiling](https://jcgt.org/published/0008/04/02/) - attempts to resolve artifacts you get when blending two textures together (also only using 3 texture samples, plus a lookup table per texture

## Shader Programming
- [The Book of Shaders](https://thebookofshaders.com/)
- [shadertoy smoothstep demo](https://www.shadertoy.com/view/sdyGRW)
- [Shader Derivative Functions](http://www.aclockworkberry.com/shader-derivative-functions/) - Useful for normals.
- [How to read shader assembly](https://interplayoflight.wordpress.com/2021/04/18/how-to-read-shader-assembly/)
- [ShaderToy Advanced Tricks](https://shadertoyunofficial.wordpress.com/2021/03/09/advanced-tricks/) 

## Compute
### Introduction to compute shader
- [Introduction to Compute Shaders](https://anteru.net/blog/2018/intro-to-compute-shaders/)
- [More Compute Shaders](https://anteru.net/blog/2018/more-compute-shaders/)
- [Even more Compute Shaders](https://anteru.net/blog/2018/even-more-compute-shaders/)
- [Compute Shader Glossary](https://github.com/googlefonts/compute-shader-101/blob/main/docs/glossary.md)

### GPU Architecture
- 🎥 [CIS 565 GPU Programming and Architecture](http://cis565-fall-2021.github.io/) - A course that introduce parallel programming with a Computer Graphics flavor.
- [Gentle introduction to GPUs inner workings](https://vksegfault.github.io/posts/gentle-intro-gpu-inner-workings/) - This article summarizes some lower level aspect of how GPU executes. It uses the Vulkan API terminology, but the concept is largely platform independent.
- [GCN – two ways of latency hiding and wave occupancy](https://bartwronski.com/2014/03/27/gcn-two-ways-of-latency-hiding-and-wave-occupancy/)
- [Breaking Down Barriers](https://therealmjp.github.io/posts/breaking-down-barriers-part-1-whats-a-barrier/)
- [How does a GPU Shader work?](https://aras-p.info/texts/files/2018Academy%20-%20GPU.pdf)
- [Compute Shaders: Optimize your engine using compute / Lou Kramer, AMD](https://www.youtube.com/watch?v=0DLOJPSxJEg) 

### Parallel Algorithms
- [Parallel Prefix Sum (Scan) with CUDA](http://www.eecs.umich.edu/courses/eecs570/hw/parprefix.pdf)
- [Thinking Parallel, Part I: Collision Detection on the GPU](https://developer.nvidia.com/blog/thinking-parallel-part-i-collision-detection-gpu/)
- [Thinking Parallel, Part II: Tree Traversal on the GPU](https://developer.nvidia.com/blog/thinking-parallel-part-ii-tree-traversal-gpu/)
- [Thinking Parallel, Part III: Tree Construction on the GPU](https://developer.nvidia.com/blog/thinking-parallel-part-iii-tree-construction-gpu/)

## Color, HDR, and Tone Mapping
- [Supporting Native HDR Monitors - OurMachinery](https://ourmachinery.com/post/supporting-native-hdr-monitors/)
- [Introduction to Color Theory for Games, Art and Tech - Shahriar Shahrabi](https://shahriyarshahrabi.medium.com/introduction-to-color-theory-for-games-art-and-tech-67bd4c8607d7)
- [Tone Mapping](https://64.github.io/tonemapping/) - Introduces the theory of Tone Mapping and talks about some commonly used Tone Mapping Operators


## Sampling
See also [Ray Tracing/Sampling & Variance Reduction](#sampling--variance-reduction)
- [A Pixel is not a Little Square!](http://alvyray.com/Memos/CG/Microsoft/6_pixel.pdf) - Classic paper on misconception of "a pixel is a little square." It also serves as an introduction to sampling.
- [Basics of Image Resampling](https://entropymine.com/imageworsener/resample/)
- [Computing the Discrepancy with Applications to Supersampling Patterns](http://mentallandscape.com/Papers_tog96.pdf)
- [Generating Antialiased Images at Low Sampling Densities](http://mentallandscape.com/Papers_siggraph87.pdf)

## Animation
- [Learn OpenGL: Skeletal Animation](https://learnopengl.com/Guest-Articles/2020/Skeletal-Animation)
- 🎥 [Animation Programming Basics](https://youtu.be/Jkv0pbp0ckQ)
- 🎥 [Animation Graphs](https://youtu.be/R-T3Mk5oDHI)

## Geometry
### Geometry representations
- 🎥 [Lecture 10: Meshes and Manifolds (CMU 15-462/662)](https://youtu.be/HePDHsp8spU) - Great overview, and also spend significant time on the half-edge data structure

### Iso-surface methods
- [Interactive explanation of marching cubes and dual contouring](https://wordsandbuttons.online/interactive_explanation_of_marching_cubes_and_dual_contouring.html)
- [Polygonising a scalar field (Marching Cubes)](http://paulbourke.net/geometry/polygonise/)
- [Dual Contouring Tutorial](https://www.boristhebrave.com/2018/04/15/dual-contouring-tutorial/)
- [The Transvoxel Algorithm](https://transvoxel.org/)

### Libraries
- [Geometry Central](https://geometry-central.net/) - A modern C++ library of data structures and algorithms for geometry processing, with a particular focus on surface meshes.

## Physics and Simulation
### Physics-Based Animation
- 🎥 [SIGGRAPH University 2019 Course - An Introduction to Physics-Based Animation](https://youtu.be/b_WJ-HwalwU) - A three-hour fast-pace introduction to Physics-Based Animation
- 🎥 [CSC417/CSC2549-Physics-based Animation Fall 2021](https://youtube.com/playlist?list=PLTkE7n2CwG_PH09_q0Q7ttjqE2F9yGeM3) - Introductory lecture for a course in physics-based animation.

### Attractors
- [Strange Attractors on the GPU series](https://observablehq.com/@rreusser/strange-attractors-on-the-gpu-part-1?collection=@rreusser/writeups)

## APIs
### OpenGL
- [docs.gl](http://docs.gl/) - OpenGL API Documentation.
- [GLConstantsTranslator](https://javagl.github.io/GLConstantsTranslator/GLConstantsTranslator.html) - This page has the names of most OpenGL constants with their respective decimal and hex values. It is useful for when certain functions return GL constants.

#### Tutorials
- [Learn OpenGL](https://learnopengl.com/) - The highly recommended tutorial.

#### Meta-links
- [Awesome OpenGL](https://project-awesome.org/eug/awesome-opengl) - Curated List for OpenGL.

#### Best Practices
- [Using Modern OpenGL to Avoid Common Errors](https://juandiegomontoya.github.io/modern_opengl.html) - Talks about using features of post-4.2 OpenGL

### Vulkan
- [Spec](https://www.khronos.org/registry/vulkan/specs/1.2-extensions/html/index.html) - It is a good idea to keep it open while doing Vulkan Programming.
#### Tutorials
- [Vulkan Guide](https://vkguide.dev/) - The best "Vulkan Tutorial" available.
- 🎥 [TU Wien: Vulkan Lecture Series](https://www.youtube.com/playlist?list=PLmIqTlJ6KsE1Jx5HV4sd2jOe3V1KMHHgn)
- [vk_mini_path_tracer tutorial](https://github.com/nvpro-samples/vk_mini_path_tracer) - A relative small tutorial that focus on path tracing using Vulkan's ray tracing API.
- [3D Graphics Rendering Cookbook](https://www.amazon.com/Graphics-Rendering-Cookbook-comprehensive-algorithms/dp/1838986197)

#### Meta-links
- [Awesome Vulkan](https://github.com/vinjn/awesome-vulkan)
- [Great Resources - Vulkan Guide](https://vkguide.dev/docs/great_resources)

#### Swapchain & frame resources
- [API without Secrets: The Practical Approach to Vulkan* - Part 1](https://www.intel.com/content/www/us/en/developer/articles/training/practical-approach-to-vulkan-part-1.html) (there is no part 2)

#### Renderpass & Dynamic Rendering
- [VK_KHR_dynamic_rendering tutorial](https://lesleylai.info/en/vk-khr-dynamic-rendering/) - A tutorial to Vulkan's dynamic rendering extension
- [Khrnos: Streamlining Render Passes](https://www.khronos.org/blog/streamlining-render-passes) - Introduces the [VK_KHR_dynamic_rendering](https://www.khronos.org/registry/vulkan/specs/1.2-extensions/man/html/VK_KHR_dynamic_rendering.html) extension.

#### Bindless/Descriptor indexing
- 🎥 [Khronos Talk on Descriptor Indexing](https://www.youtube.com/watch?v=tXipcoeuNh4)
- [Vulkan Descriptor Indexing for Mobile](https://community.arm.com/developer/tools-software/graphics/b/blog/posts/vulkan-descriptor-indexing)
- [OurMachinery's Moving The Machinery to Bindless](https://ourmachinery.com/post/moving-the-machinery-to-bindless)
- [Wicked Engine: Bindless Descriptors](https://wickedengine.net/2021/04/06/bindless-descriptors/)
- [DethRaid's Vulkan Descriptor Indexing](https://gist.github.com/DethRaid/0171f3cfcce51950ee4ef96c64f59617)
- [A note on Descriptor Indexing](https://chunkstories.xyz/blog/a-note-on-descriptor-indexing/)
- [Vulkan Pills 1: Bindless Textures](https://jorenjoestar.github.io/post/vulkan_bindless_texture/)

#### Sychronization
- [TheMaister's Yet another blog explaining Vulkan synchronization](https://themaister.net/blog/2019/08/14/yet-another-blog-explaining-vulkan-synchronization/)
- [Understanding Vulkan Synchronization](https://www.khronos.org/blog/understanding-vulkan-synchronization)
- [Vulkan Timeline Semaphores](https://www.khronos.org/blog/vulkan-timeline-semaphores)

#### Vulkan Compute
- [A simple Vulkan Compute example](https://www.duskborn.com/posts/a-simple-vulkan-compute-example/)
- [Vulkan Subgroup tutorial. AKA wavefronts](https://www.khronos.org/blog/vulkan-subgroup-tutorial)

#### Libraries
- [vk-bootstrap](https://github.com/charles-lunarg/vk-bootstrap) - Library that simplifies the Vulkan initialization boilerplate.
- [VulkanMemoryAllocator](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator) - Memory allocation library that simplifies Vulkan memory allocation and provides decent performance.
- [volk](https://github.com/zeux/volk) - Meta-loader for Vulkan that allows you to dynamically load entrypoints required to use Vulkan. It also simplify the use of Vulkan extensions.
- [SPIRV-Reflect](https://github.com/KhronosGroup/SPIRV-Reflect) - Can be used to extract descriptor and push constant information from SPIRV.

#### Performance Best Practice
- [Writing an efficient Vulkan renderer](https://zeux.io/2020/02/27/writing-an-efficient-vulkan-renderer/)

#### Others
- [Vulkan Diagram](https://github.com/David-DiGioia/vulkan-diagrams)

### DirectX 12
- [Reader Question Answered 1 - Learning D3D12](https://www.jendrikillner.com/post/d3d12-learning-plan/) - A roadmap for learning DirectX 12
- [Raw DirectX 12](https://alain.xyz/blog/raw-directx12) - An introduction to writing a simple Hello Triangle DirectX 12 application.
- [Learning DirectX 12](https://www.3dgep.com/learning-directx-12-1/)
- [Direct3D 12 programming guide](https://docs.microsoft.com/en-us/windows/win32/direct3d12/directx-12-programming-guide)

#### Resource Binding & Bindless
- [Resource Binding - Direct3D 12 Programming Guide](https://docs.microsoft.com/en-us/windows/win32/direct3d12/resource-binding)
- [Bindless Texturing for Deferred Rendering and Decals](https://mynameismjp.wordpress.com/2016/03/25/bindless-texturing-for-deferred-rendering-and-decals/)
- [Binding Bindlessly](https://alextardif.com/Bindless.html)
- [Wicked Engine: Bindless Descriptors](https://wickedengine.net/2021/04/06/bindless-descriptors/)

### WebGL
- [Awesome WebGL](https://project-awesome.org/sjfricke/awesome-webgl)

### WebGPU
- [Spec](https://gpuweb.github.io/gpuweb/)
#### Tutorials
- [Learn wgpu](https://sotrh.github.io/learn-wgpu/) - Tutorial of WebGPU api using Rust and the wgpu library.

## System Design
### Renderer Architecture
- 🎥 [SIGGRAPH 2021 REAC: Unity Rendering Architecture](https://www.youtube.com/watch?v=6LzcXPIWUbc)

### GPU-driven rendering
- [GPU Driven Rendering - Siggraph 2015](http://advances.realtimerendering.com/s2015/aaltonenhaar_siggraph2015_combined_final_footer_220dpi.pdf)

## Assets Format
## Scene Description
- [Siggraph 2019 Hydra](https://graphics.pixar.com/usd/files/Siggraph2019_Hydra.pdf) - Presentation slides for Hydra, which is an open source framework to transport live scene graph data to renderers.

## General Programming
### Meta-links
- [Awesome C](https://project-awesome.org/inputsh/awesome-c#game-programming)
- [Awesome C++](https://project-awesome.org/fffaraz/awesome-cpp)
- [Awesome Rust](https://github.com/rust-unofficial/awesome-rust)
### Engine Development
- [Game Engine Archirecture](https://www.gameenginebook.com/) (paid book)
- [The Shader Permutation Problem - Part 1: How Did We Get Here?](https://therealmjp.github.io/posts/shader-permutations-part1/)
- [The Shader Permutation Problem - Part 2: How Do We Fix It?](https://therealmjp.github.io/posts/shader-permutations-part2/)
### High-level Programming
- [Game Programming Patterns](http://gameprogrammingpatterns.com/)
### Game loop
- [Game Loop - Game Programming Patterns](http://gameprogrammingpatterns.com/game-loop.html)
- [Fix Your Timestep!](https://gafferongames.com/post/fix_your_timestep/)
- Chapter 8 "The Game Loop and Real-Time Simulation" of Game Engine Archirecture

### Floating-point numbers
- [Floating-point in mobile shaders](https://solidpixel.github.io/2021/11/23/floats_in_shaders.html)

### Memory Allocation & Management
- [Memory Allocation Strategies series](https://www.gingerbill.org/series/memory-allocation-strategies/)
- [Memory Management section on Pbrt](https://www.pbr-book.org/3ed-2018/Utilities/Memory_Management)
- The Memory chapter of Game Engine Archirecture
- [Object Pool](http://gameprogrammingpatterns.com/object-pool.html) chapter of Game Programming Pattern.
- 🎥 CppCon 2017: John Lakos “Local ('Arena') Memory Allocators” [[Part1]](https://youtu.be/nZNd5FjSquk) [[Part2]](https://youtu.be/CFzuFNSpycI)
- 🎥 [CppCon 2017: Bob Steagall “How to Write a Custom Allocator”](https://youtu.be/kSWfushlvB8)

## Tools/libraries

### Debuggers
- [RenderDoc](https://renderdoc.org/)
- [Nvidia Nsight Graphics](https://developer.nvidia.com/nsight-graphics)
- [Radeon™ GPU Profiler (AMD)](https://github.com/GPUOpen-Tools/radeon_gpu_profiler)
- [Intel® GPA](https://www.intel.com/content/www/us/en/developer/tools/graphics-performance-analyzers/overview.html)
- [SpectorJS (WebGL)](https://github.com/BabylonJS/Spector.js)

### Profilers
A bunch of graphics debuggers above also have profiling capability.
- [Optick: C++ Profiler For Games](https://github.com/bombomby/optick)
- [Tracy Profiler](https://github.com/wolfpld/tracy)
- [Dear Imgui profiler widget](https://github.com/Raikiri/LegitProfiler)

### Denoiser
- [Optix Denoiser](https://developer.nvidia.com/optix-denoiser)
- [FidelityFX-Denoiser](https://github.com/GPUOpen-Effects/FidelityFX-Denoiser)
- [Open Image AI Denoiser](https://github.com/OpenImageDenoise/oidn)

## Assets
- [McGuire Computer Graphics Archive](http://casual-effects.com/data/index.html) - OBJ format scenes.
- [ORCA: Open Research Content Archive](https://developer.nvidia.com/orca) - Free large graphics scene samples.
- [ambientCG](https://ambientcg.com/) - Public Domain materials for Physically Based Rendering.
- [Rendering Resources - Benedikt Bitterli](https://benedikt-bitterli.me/resources/) - Scenes in Tungsten, Mitsuba, and pbrt-v3 formats.
