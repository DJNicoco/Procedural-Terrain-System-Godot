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

| 2D Cellular-Noise Heightmap | 3D Terrain Mesh |
| --- | --- |
| <img src="images/2d_fastnoiseheightmap.png" width="420" alt="2D cellular-noise heightmap"> | <img src="images/3d_fastnoiseheightmap.png" width="420" alt="3D terrain mesh from heightmap"> |
| <sub>FastNoiseLite, grayscale</sub> | <sub>Vertex heights sampled from heightmap</sub> |

<p align="center"><em>Screenshots from my personal implementation (no source code shared per course policy).</em></p>

---

## 💡 Key Features
- Generated grayscale heightmaps using **FastNoiseLite** with multiple octaves of cellular noise.  
- Built 3D terrain mesh programmatically with vertex heights sampled from the heightmap.  