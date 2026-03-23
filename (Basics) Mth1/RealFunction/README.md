# Math 1 · Topic 1 — Real Functions

## Topics

### 1. Real Functions / Domain / Increasing & Decreasing / Composition / Range
- What a function is — input → output
- Domain — all valid inputs
- Range — all possible outputs
- Increasing & decreasing — where the function grows or shrinks
- Composition functions — f(g(x)) — **this is what neural networks are**

### 2. Sketching Functions
- Visualizing behavior of a function
- Not critical for ML — light touch

### 3. Even & Odd / One-to-One / Inverse Functions
- Even & odd — symmetry properties
- One-to-one — each input maps to a unique output
- Inverse functions — undoing a function — useful conceptually

### 4. Exponential & Logarithmic Functions
- Exponential — growth curves, softmax, sigmoid
- Logarithmic — **log is everywhere in ML**
  - Cross-entropy loss
  - Log-likelihood
  - Log probabilities

### 5. Absolute Value / Piecewise Defined Functions
- Absolute value — distance from zero
- Piecewise — **ReLU activation is a piecewise function**
  - ReLU(x) = x if x > 0, else 0

### 6. Trigonometric Functions
- Sin, Cos, Tan and their properties
- Used in **positional encoding** in Transformers — know the basics

### 7. Hyperbolic Functions
- Sinh, Cosh, Tanh
- **Tanh is an activation function in neural networks** — know this one
- Skip the rest for now

### 8. Inverse Trigo / Inverse Hyperbolic
- Not needed for ML — skip for now

---

## What Matters Most for AI/ML

| Topic | Importance | Why |
|-------|-----------|-----|
| Composition functions | ⭐⭐⭐ | Neural networks are compositions of functions |
| Exponential & Log | ⭐⭐⭐ | Loss functions, probabilities, activations |
| Piecewise / Absolute value | ⭐⭐⭐ | ReLU activation function |
| Tanh | ⭐⭐ | Activation function in neural networks |
| Trig functions | ⭐ | Positional encoding in Transformers |
| Sketching | — | Not needed |
| Inverse Trigo / Hyperbolic | — | Skip |

---

## Resources

- **3Blue1Brown** — Essence of Calculus (covers functions visually)
  - https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr
- **Khan Academy** — Functions
  - https://www.khanacademy.org/math/algebra/x2f8bb11595b61c86:functions

---

## Done When

- [ ] Can define domain and range of any function
- [ ] Can compose two functions f(g(x)) and explain what it means
- [ ] Can explain what log does and why it's useful in ML
- [ ] Can write ReLU as a piecewise function
- [ ] Can explain what tanh outputs and why it's used as an activation