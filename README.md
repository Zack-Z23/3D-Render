## Final Render
 
The culmination of the series: a scene with hundreds of randomly generated spheres across all three material types — Lambertian, metal, and glass — rendered with a narrow field of view, a distant camera position, and subtle depth of field.
 
![Final Scene](https://github.com/user-attachments/assets/53b7d4b4-3ff6-46c0-a9a9-a7c22b64243f)

 
---
 
## Concepts Covered
 
| Concept | Details |
|---|---|
| Ray-sphere intersection | Analytic solution via quadratic formula |
| Lambertian reflectance | True random unit vector scattering |
| Metal reflection | `v - 2(v·n)n` with optional fuzz |
| Dielectrics | Snell's Law, total internal reflection, Schlick approximation |
| Antialiasing | Multi-sample averaging per pixel |
| Gamma correction | √ transform for perceptually correct output |
| Camera model | Positionable with FOV, orientation, and depth of field |
| Defocus blur | Thin lens approximation with randomized ray origin disk |
 
---
 
## References
 
- [_Ray Tracing in One Weekend_](https://raytracing.github.io/books/RayTracingInOneWeekend.html) — Peter Shirley
