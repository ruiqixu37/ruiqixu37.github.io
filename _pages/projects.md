---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

# Visual Computing Projects
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <style>
    .project {
      display: flex;
      flex-direction: row;
      align-items: center;
      margin-bottom: 10px;
    }
    .project img {
      width: 400px;
	  height: 400px;
      margin-left: 20px;
	  object-fit: contain;
    }
    .description a {
      text-decoration: none;
    }
  </style>
</head>
<body>
	<div class="project">
    <div class="description">
      <h2>Reconstructing 3D language field with in-the-wild images</h2>
      <p> Construct a 3D language field with Gaussian Splatting to handle images containing transient objects. The model leverages semantic segmentation and CLIP embeddings to model transient objects in the scene.
      <a href="https://github.com/ruiqixu37/2952X-Final-Project">[Github]</a> <a href="https://drive.google.com/file/d/1plYeHFmX0MkWaqokV5WWmvFjgXElzR9h/view?usp=drive_link">[Report]</a>  
	  <br><br>
	  <strong> Keywords: </strong> Gaussian Splatting, 3D reconstruction, Segment-Anything, CLIP
	  </p>
    </div>
    <img src="../images/noisylangsplat.png" alt="Screenshot of Generalized Category Discovery Project"/>
  </div>

  <!-- First Project -->
  <div class="project">
    <div class="description">
      <h2>Procedural landscape generator</h2>
      <p> A dynamic scene generator consisting of sky, water, mountains, and terrains with seasonal changes
      <a href="https://github.com/szhan227/CSCI2230FinalProject">[Github]</a>
	  <br><br>
	  <strong> Keywords: </strong> Procedural Modeling, GLSL
	  </p>
    </div>
    <img src="../images/scene.png" alt="Screenshot of Generalized Category Discovery Project"/>
  </div>

  <!-- Second Project -->
  <div class="project">
    <div class="description">
      <h2>Ray Tracer</h2>
      <p> Ray tracer based on Phong shading model. The ray tracer supports reflection, refraction, and shadows, and models various light sources, including point lights, directional lights, and spotlights.
      <a href="https://github.com/BrownCSCI1230/projects-ray-ruiqixu37">[Github]</a>
	  <br><br>
	  <strong> Keywords: </strong> Ray tracing, Phong shading
	  </p>
    </div>
    <img src="../images/reflections_complex.png" alt="Screenshot of Kriging Convolutional Networks Project"/>
  </div>

  <!-- Third Project -->
  <div class="project">
    <div class="description">
      <h2>Path tracing</h2>
      <p> Physically-based path tracer that simulates global illumination, caustics, and soft shadows. The path tracer supports various materials, including Lambertian, specular, and refractive materials.
      <a href="https://github.com/brown-cs-224/path-ruiqixu37">[Github]</a>
	  <br><br>
	  <strong> Keywords: </strong> Path tracing, physically-based rendering
	  </p>
    </div>
    <img src="../images/path_tracing.png" alt="Screenshot of Kriging Convolutional Networks Project"/>
  </div>

  <div class="project">
    <div class="description">
      <h2>As-Rigid-As-Possible Surface Modeling</h2>
      <p> A system for user-interactive deformation of 3D meshes. In the system, mesh vertices can be re-positioned by clicking and dragging. The system will update the rest of the mesh in response to these user interactions such that it moves as-rigidly-as-possible.
      <a href="https://github.com/brown-cs-224/arap-ruiqixu37">[Github]</a>
	  <br><br>
	  <strong> Keywords: </strong> Optimization, mesh deformation
	  </p>
    </div>
    <img src="../images/arap.png" alt="Screenshot of Kriging Convolutional Networks Project"/>
  </div>

  <div class="project">
    <div class="description">
      <h2>Geometry Processing (Mesh) </h2>
      <p> Implementations of various geometry processing algorithms on triangular meshes, including Loop subdivision, quadric error simplification, and isotropic remeshing.
      <a href="https://github.com/brown-cs-224/mesh-ruiqixu37">[Github]</a>
	  <br><br>
	  <strong> Keywords: </strong> Geometry processing, mesh simplification, mesh remeshing
	  </p>
    </div>
    <img src="../images/cow_simplify.png" alt="Screenshot of Kriging Convolutional Networks Project"/>
  </div>

  <div class="project">
    <div class="description">
      <h2>Interactive brush painting interface</h2>
      <p> A 2D drawing board that allows users to paint with different brush styles and colors. The brush effects are implemented through multiple filters (e.g., constant, linear, quadratic, cubic, and sinusoidal) and color blending modes.
      <a href="https://github.com/BrownCSCI1230/projects-1-and-2-brush-and-filter-ruiqixu37">[Github]</a>
	  <br><br>
	  <strong> Keywords: </strong> OpenGL, filters, color blending, GUI
	  </p>
    </div>
    <img src="../images/brush.png" alt="Screenshot of Generalized Category Discovery Project"/>
  </div>

  <div class="project">
    <div class="description">
      <h2>Finite Element Simulation </h2>
      <p> Animate deformable solid objects using the finite element method. The project supports essential features such as force computation, time integration, and collision response.
      <a href="https://github.com/brown-cs-224/fem-ruiqixu37">[Github]</a>
	  <br><br>
	  <strong> Keywords: </strong> Finite element method, animation
	  </p>
    </div>
    <img src="../images/fem.png" alt="Screenshot of Kriging Convolutional Networks Project"/>
  </div>
</body>
</html>

# Other Experiences

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <style>
    .project {
      display: flex;
      flex-direction: row;
      align-items: center;
      margin-bottom: 10px;
    }
    .project img {
      width: 250;
	  height: 250;
      margin-left: 20px;
	  object-fit: contain;
    }
    .description a {
      text-decoration: none;
    }
  </style>
</head>
<body>
  <!-- First Project -->
  <div class="project">
    <div class="description">
      <h2>Generalized Category Discovery</h2>
      <p>Semi-Supervised Deep Clustering for Generalized Category Discovery. I worked with Patrick Feeney and Prof. Michael Hughes on this project in Spring 2023.
      <a href="https://github.com/tufts-ai-robotics-group/ImbalancedGCD">[Github]</a></p>
    </div>
    <img src="../images/GCD.png" alt="Screenshot of Generalized Category Discovery Project"/>
  </div>

  <!-- Second Project -->
  <div class="project">
    <div class="description">
      <h2>Kriging Convolutional Networks</h2>
      <p>Optimized PyTorch implementation of Kriging Convolutional Networks. I finished this project under the supervision of Prof. Liping Liu in Fall 2022.
      <a href="https://github.com/tufts-ml/kcn-torch">[Github]</a></p>
    </div>
    <img src="../images/KCN.png" alt="Screenshot of Kriging Convolutional Networks Project"/>
  </div>

  <!-- Third Project -->
  <div class="project">
    <div class="description">
      <h2>Citadel DataOpen Summer Invitational</h2>
      <p>Second place winner of virtual, one-week datathon hosted by Citadel in Summer 2021.
      <a href="https://github.com/ruiqixu37/2021-Citadel-Datathon">[Github]</a></p>
    </div>
    <img src="../images/Citadel.png" alt="Screenshot of Citadel DataOpen Summer Invitational Project"/>
  </div>
</body>
</html>

