# Möbius Strip: Parametric Modeling & Surface Area Approximation

> What is Mobius Strip ? <br/>
> A surface with one continuous side formed by joining the ends of a rectangle after twisting one end through 180°

## Deliverables

### 3D Visualization
![image alt](https://github.com/abhishekboken12/-Mobius-strip/blob/f6a0344031b5de0362692b6556793dcbbad5298c/Mo%CC%88bius_Strip.jpg)

## 🧠 Features

- Parametric generation of a Möbius Strip
- 3D visualization using `matplotlib`
- Numerical estimation of:
  - Surface Area
  - Edge Length

---

**Code Structure:** 
- `class MobiusStrip:`  
  - `__init__`: Initializes radius, width, and mesh resolution  
  - `generate_3Delemnts`: Computes 3D coordinates for the strip surface  
  - `surface_area`: Numerically estimates the surface area  
  - `edge_length`: Calculates the length of the Möbius edge  
  - `plot`: 3D visualization using matplotlib  

- `User Input`: Prompts for `radius` and `width`  
- `Execution`: Instantiates `MobiusStrip`, prints area and edge length, and shows 3D plot 


**Challenges Faced:**  
- When UV mapping the grid, it went from (0, 0) in the bottom left corner to (1, 1) in the top right. Howver, the moebius strip loops, meaning that the first edge is connected to the last 
  edge. The problem with this is that the UV coordinates went from 0...1 in a tiny space.
- Deriving and correctly implementing analytical expressions for partial derivatives to ensure accurate surface element calculations.  
- Balancing mesh resolution for numerical precision without excessive computation time.  
- Achieving a smooth, clear 3D visualization of the twisted Möbius geometry using Matplotlib’s plotting tools.
---



