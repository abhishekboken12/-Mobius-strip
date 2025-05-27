# Möbius Strip: Parametric Modeling & Surface Area Approximation

> What is Mobius Strip ? <br/>
> A surface with one continuous side formed by joining the ends of a rectangle after twisting one end through 180°

## Deliverables

### 3D Visualization

---


**Code Structure:**  
The project is organized around a `MobiusStrip` class that encapsulates all core functionalities: generating 3D parametric coordinates, calculating analytical partial derivatives, numerically approximating surface area via vector calculus, computing the edge length, and plotting the strip. This modular design promotes clarity and easy maintenance.

**Surface Area Approximation:**  
Surface area is computed numerically by evaluating the integral of the magnitude of the cross product of the parametric surface’s partial derivatives \(\mathbf{r}_u\) and \(\mathbf{r}_v\) over the parameter domain.

**Challenges Faced:**  
- When UV mapping the grid, it went from (0, 0) in the bottom left corner to (1, 1) in the top right. Howver, the moebius strip loops, meaning that the first edge is connected to the last 
  edge. The problem with this is that the UV coordinates went from 0...1 in a tiny space.
- Deriving and correctly implementing analytical expressions for partial derivatives to ensure accurate surface element calculations.  
- Balancing mesh resolution for numerical precision without excessive computation time.  
- Achieving a smooth, clear 3D visualization of the twisted Möbius geometry using Matplotlib’s plotting tools.

---

### Assignment Focus Areas

- Parametric 3D modeling of complex surfaces  
- Numerical integration and geometric computation  
- Visualization of non-orientable surfaces  
- Writing clear, maintainable, and modular code

---

Feel free to explore, modify, and extend this foundation to push your geometric modeling skills further!

