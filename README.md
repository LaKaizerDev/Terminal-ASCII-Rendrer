# ASCII 3D Renderer

A small 3D software renderer written in C++ that displays shaded, rotating 3D objects using ASCII characters in the terminal.

The goal of this project is to explore the fundamentals of computer graphics and lower-level C++ programming by building a renderer from scratch, without relying on graphics libraries or game engines.

## Goals

- Build a character-based framebuffer.
- Represent and manipulate 3D vectors and vertices.
- Rotate 3D objects using basic linear algebra and trigonometry.
- Project 3D coordinates onto a 2D terminal grid.
- Rasterize and fill triangles.
- Implement a depth buffer for hidden-surface removal.
- Add simple directional lighting and ASCII shading.
- Animate a rotating 3D cube in the terminal.

## Planned Tech Stack

- **Language:** C++
- **Standard:** C++17
- **Display:** Terminal using ASCII characters
- **Graphics libraries:** None for the initial version
- **Build tools:** GCC and the command line

## Roadmap

### Milestone 1 — Framebuffer
- Create a character grid.
- Clear the grid and modify individual cells.
- Print the grid to the terminal.
- Draw basic 2D shapes.

### Milestone 2 — 3D Mathematics
- Implement a 3D vector representation.
- Define the cube's vertices and faces.
- Rotate vertices around the coordinate axes.
- Project 3D points onto the 2D grid.

### Milestone 3 — Filled Surfaces
- Rasterize triangles.
- Fill visible faces.
- Implement a depth buffer to hide surfaces behind closer geometry.

### Milestone 4 — Animation and Lighting
- Animate the rotating cube.
- Calculate basic surface lighting.
- Map brightness levels to ASCII characters.
- Polish the output and document the build process.

## Building and Running

Build instructions will be added once the initial source code and project structure are in place.

The initial implementation is intended to compile with GCC using the C++17 standard.

## Scope

The first version focuses on rendering a single rotating, shaded cube. Model loading, textures, advanced lighting, camera controls, GPU rendering, and engine features are intentionally out of scope.

## Learning Objectives

This project is a hands-on exploration of C++, data structures, coordinate transformations, rasterization, depth testing, and the mathematics behind 3D graphics.

The priority is to understand the implementation, complete a manageable project, and build a foundation for future graphics and systems programming projects.

## Status

**In development — Milestone 1: Framebuffer.**