# Vulkan Sponza Renderer

## 📌 Overview
This project implements a real-time rendering pipeline using Vulkan, featuring the Sponza scene as a benchmark environment.

## 🚀 Features
- Vulkan-based real-time renderer
- Sponza scene rendering (complex geometry & lighting)
- GPU memory management using Vulkan buffers and images

## 🧠 Motivation
The goal of this project is to build a rendering pipeline and understand the mechanisms behind Vulkan graphics rendering

## 🏗️ Tech Stack
- **Graphics API:** Vulkan
- **Language:** C++
- **Windowing:** GLFW
- **Build System:** CMake / Visual Studio

## 🖼️ Demo
![Sponza Screenshot](assets/sponza_complete.png)
![Sponza Screenshot](assets/sponza_diffuse.png)
![Sponza Screenshot](assets/sponza_normal.png)

## ⚙️ Setup & Installation

### Prerequisites
- Vulkan SDK installed
- C++ compiler (MSVC recommended)
- GLFW

### Build Instructions

#### Using Visual Studio
1. Open `.sln` file
2. Build solution
3. Run project

#### Using CMake
```bash
mkdir build
cd build
cmake ..
cmake --build .
