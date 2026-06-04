Readme · MD
# Ray Tracing in One Weekend
> *(It takes me longer than one weekend)*
 
A deep dive into 3D rendering and ray tracing, following the [Ray Tracing in One Weekend](https://raytracing.github.io/) series. Each step builds on the last — from a basic renderer all the way to realistic lighting and materials.
 
---
 
## Progress
 
### Basic Renderer
 
The starting point: a simple ray tracer rendering spheres with basic shading.
 
![Current Progress](https://github.com/user-attachments/assets/209bcff8-fbbb-4831-86c4-0de8915e8f6f)
 
---
 
### Antialiasing
 
Added multisampling antialiasing to smooth out jagged edges along object boundaries.
 
![Antialiasing](https://github.com/user-attachments/assets/20537bc1-5e57-44b7-ad0b-7f0d4a049d39)
 
---
 
### Diffuse Materials & Reflectance
 
First realistic render using **True Lambertian Reflectance**. Shadow acne is eliminated using an intersection offset, allowing the diffuse reflectance of the surface to come through clearly.

 
**30% Reflectance**
 
![30% Reflectance](https://github.com/user-attachments/assets/698c635c-d6f9-4e47-a3b2-09f1e09b02f0)

**50% Reflectance**
 
![50% Reflectance](https://github.com/user-attachments/assets/042d7e07-1158-42be-9ee6-77e9381ac0a9)

**70% Reflectance**

![70% Reflectance](https://github.com/user-attachments/assets/583b5199-a283-457d-9658-e698f8ee6a6c)


