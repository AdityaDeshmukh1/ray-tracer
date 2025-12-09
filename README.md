# Ray Tracer in One Weekend

A raw C++ implementation of a path tracer, built from scratch following Peter Shirley's [*Ray Tracing in One Weekend*](https://raytracing.github.io/books/RayTracingInOneWeekend.html).

This project implements the physics of light transport—including reflection, refraction, and defocus blur—without using any external graphics APIs. Just pure vector math and CPU cycles.

## Features
- **Primitives**: Spheres with adjustable radii and centers.
- **Materials**:
  - **Lambertian (Matte)**: Diffuse reflection.
  - **Metal**: Specular reflection with adjustable fuzziness.
  - **Dielectric (Glass)**: Refraction using Snell’s Law and Schlick approximation for reflectance.
- **Camera**: Positionable camera with depth-of-field (defocus blur) support.
- **Antialiasing**: Multi-sampling per pixel.

## Build & Run

No external dependencies required. You just need a C++ compiler.

![final-render](final.jpeg)
