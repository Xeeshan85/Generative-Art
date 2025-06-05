# 🌀 Interactive Fractal Generator

Explore a visual journey through the mathematical beauty of **fractals**. This project features interactive fractal renderers with both **simple** and **complex** fractals implemented using HTML and JavaScript.

---

## 🔗 Live Demo

- 🔹 [Simple Fractals](https://xeeshan85.github.io/Generative-Art/fractal-renderer-simple.html)
- 🔸 [Complex Fractals](https://xeeshan85.github.io/Generative-Art/fractal-renderer-complex.html)

---

## 📚 What Are Fractals?

Fractals are infinitely complex, self-similar patterns generated using recursive or iterative mathematical equations. Found in nature and mathematics, fractals demonstrate how simple rules can lead to intricate, beautiful structures.

---

## 🔹 Simple Fractals

### 1. **Von Koch Snowflake**
- **Equation**: Recursive division of each line into 4 segments, adding a triangle in the center.
- **Description**: Infinite perimeter, finite area.

### 2. **Fractal Tree**
- **Equation**: Recursively split line segments at a fixed angle and ratio.
- **Description**: Mimics natural tree branching.

### 3. **Barnsley's Fern**
- **Equation**: A set of affine transformations:
- `f1: x' = 0, y' = 0.16y`
- `f2: x' = 0.85x + 0.04y, y' = -0.04x + 0.85y + 1.6`
- `f3: x' = 0.20x - 0.26y, y' = 0.23x + 0.22y + 1.6`
- `f4: x' = -0.15x + 0.28y, y' = 0.26x + 0.24y + 0.44`
- **Description**: Creates a lifelike fern shape.

### 4. **Dragon Curve**
- **Equation**: Recursive folding with right angles.
- **Description**: A self-similar, space-filling curve.

### 5. **Sierpinski Triangle**
- **Equation**: Remove the central triangle recursively.
- **Description**: Classic triangle-based recursive pattern.

### 6. **Sierpinski Carpet**
- **Equation**: Divide a square into 9 parts, remove the center, and repeat.
- **Description**: A 2D generalization of the Sierpinski triangle.

---

## 🔸 Complex Fractals

### 1. **Mandelbrot Set**
- **Equation**: `zₙ₊₁ = zₙ² + c`
- **Description**: The most famous fractal; plots complex numbers that remain bounded.

### 2. **Mandelbrot Variants**
- **Equations**:
- z¹: Linear (rarely used)
- z²: Classical Mandelbrot
- z³: `zₙ₊₁ = zₙ³ + c`
- z⁴: `zₙ₊₁ = zₙ⁴ + c`
- **Description**: Different powers yield intricate boundary patterns.

### 3. **Burning Ship**
- **Equation**: `zₙ₊₁ = (|Re(zₙ)| + i|Im(zₙ)|)² + c`
- **Description**: Produces flame-like jagged edges.

### 4. **Julia Set**
- **Equation**: `zₙ₊₁ = zₙ² + c` (with fixed `c`)
- **Description**: Related to the Mandelbrot set; each `c` gives a unique pattern.

### 5. **Phoenix**
- **Equation**: `zₙ₊₁ = zₙ² + c + p·zₙ₋₁`
- **Description**: Introduces dependence on the previous iteration.

### 6. **Tricorn**
- **Equation**: `zₙ₊₁ = conjugate(zₙ)² + c`
- **Description**: Generates a 3-lobed mirrored structure.

### 7. **Multibrot**
- **Equation**: `zₙ₊₁ = zₙ^d + c` (where `d` is an integer > 2)
- **Description**: Extends Mandelbrot with different powers.

### 8. **Newton Fractal**
- **Equation**: `zₙ₊₁ = zₙ - f(zₙ)/f′(zₙ)`
- **Example**: `f(z) = z³ - 1`
- **Description**: Shows convergence of Newton’s method in the complex plane.

### 9. **Rose Curve**
- **Equation**: `r(θ) = a·cos(kθ)` or `r(θ) = a·sin(kθ)`
- **Description**: Creates flower-like polar patterns.

### 10. **Hypocycloid**
- **Equation**: `x = (R - r)·cos(θ) + r·cos((R - r)/r · θ)`
- **Description**: Curve traced by a point inside a rolling circle.

### 11. **Fermat Spiral**
- **Equation**: `r = √θ`
- **Description**: Found in nature (e.g., sunflower seed patterns).


---

## 🧪 How to Use

Just click the links above to run the fractal generator in your browser. You can explore various fractals with different parameters.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Credits

Developed by [M Zeeshan](https://github.com/xeeshan85)

