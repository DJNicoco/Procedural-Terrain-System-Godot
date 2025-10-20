# 🎮 Procedural-Terrain-System-Godot

###  COMP 360 – Game Graphics (Fall 2025)
**Type:** Independent Implementation (Group Assignment)  
**Language:** GDScript  
**Engine:** Godot 4  

---

## 📖 Overview
This project showcases my individual implementation from a group assignment in COMP 360 – Game Graphics.  
I built a Procedural Terrain System in Godot 4 that uses FastNoiseLite to generate 2D heightmaps and 3D terrain meshes procedurally.  
This deepened my understanding of noise functions, mesh construction, and 3D rendering pipelines in real-time environments.

---

## ⚙️ Tech Used
- Godot 4  
- GDScript  
- FastNoiseLite  

---

## 🖼️ Visual Results

<div align="center" style="display: flex; gap: 20px; justify-content: center; flex-wrap: wrap;">

  <figure>
    <img src="images/2d_fastnoiseheightmap.png" width="420" alt="2D Cellular-Noise Heightmap (FastNoiseLite)">
    <figcaption>2D Cellular-Noise Heightmap (FastNoiseLite, Grayscale)</figcaption>
  </figure>

  <figure>
    <img src="images/3d_fastnoiseheightmap.png" width="420" alt="3D Terrain Mesh from Heightmap">
    <figcaption>3D Terrain Mesh (Vertex Heights Sampled from Heightmap)</figcaption>
  </figure>

</div>

<p align="center"><em>Screenshots from my personal implementation (no source code shared per course policy).</em></p>


---

## 💡 Key Features
- Generated grayscale heightmaps using **FastNoiseLite** with multiple octaves of cellular noise.  
- Built 3D terrain mesh programmatically with vertex heights sampled from the heightmap.  