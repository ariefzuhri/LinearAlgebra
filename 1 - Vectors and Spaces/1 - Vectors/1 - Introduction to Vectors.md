# Introduction to Vectors

![Source: [Vector intro for linear algebra (video) | Khan Academy](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/vector-introduction-linear-algebra)](https://github.com/ariefzuhri/LinearAlgebra/blob/main/Resources/introduction_to_vectors_0.png)

Source: [Vector intro for linear algebra (video) | Khan Academy](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/vector-introduction-linear-algebra)

# 🧠 What Is a Vector?

A **vector** is a quantity that has:

- **Magnitude** (size or length) ✅
- **Direction** (where it's pointing) ✅

So, a vector = **magnitude + direction**.

---

# 🧮 Scalar vs Vector (Speed vs Velocity)

## 📏 Scalar (Speed)

- Example: "5 mph"
- Only has magnitude
- Does **not** include direction
- Called a **scalar quantity**

## 🧭 Vector (Velocity)

- Example: "5 mph east"
- Has both magnitude **and** direction
- Called a **vector quantity**

🔁 So:

- **Speed** = scalar
- **Velocity** = vector

---

# 🎯 Visualizing Vectors

## 🧾 Notation

- Vectors are often written in **bold** (in textbooks) or with an **arrow** overhead (in handwriting), like:
    
    → **v** or $\vec{v}$
    

## ✏️ Column Vector Form

A vector pointing 5 units right (east), with no vertical movement, is written as:

```
v = [5]
    [0]

```

This tells us:

- 5 units in the **x-direction** (horizontal)
- 0 units in the **y-direction** (vertical)

Or in row format:

```
v = (5, 0)

```

🧠 In 2D: the first number is horizontal (x), the second is vertical (y).

---

# 📐 Example: Vector "a" = [3, 4]

Shown as a diagonal arrow from origin, where:

- x (horizontal) movement = 3 units ➡️
- y (vertical) movement = 4 units ⬆️

This vector is written:

```
a = [3]
    [4]

```

## 📏 Magnitude of a Vector

Use the Pythagorean Theorem!

For `a = [3, 4]`:

$\text{Magnitude} = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5$

🧠 Aha! It’s a **3-4-5 triangle**.

---

# 🧭 Properties of Vectors

## ✅ Equivalent Vectors

Two vectors are **equivalent** if:

- They have the **same magnitude**
- They point in the **same direction**

**📍Doesn’t matter where the arrow starts!**

---

# 🧮 Vectors in Higher Dimensions

While we can draw vectors in 2D and 3D...

- 🧠 Our brains can’t visualize 4D, 5D, or 20D well.
- But ✨ linear algebra lets us **work with them algebraically**.

Hence, using vector notation like `[3, 4]`, `[5, 0]`, etc., is **powerful and scalable** to more dimensions.

---

# ✅ Key Takeaways

| Concept | Description |
| --- | --- |
| Vector | A quantity with both **magnitude** and **direction** |
| Scalar | A quantity with only **magnitude** (e.g. speed) |
| Velocity | A **vector** version of speed (includes direction) |
| Notation | Vectors as tuples `(x, y)` or columns `[[x], [y]]` |
| Vector Length | Calculated with Pythagoras: `√(x² + y²)` |
| Equivalent Vectors | Same magnitude + direction, position irrelevant |
| Higher Dimensions | Handled symbolically using notation—beyond visual intuition |
