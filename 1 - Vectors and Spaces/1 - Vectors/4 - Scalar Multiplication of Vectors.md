# 📘 Scalar Multiplication of Vectors

![Source: [Multiplying a vector by a scalar (video) | Khan Academy](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/multiplying-vector-by-scalar)](https://github.com/ariefzuhri/LinearAlgebra/blob/main/Resources/scalar_multiplication_of_vectors_0.jpeg)

Source: [Multiplying a vector by a scalar (video) | Khan Academy](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/multiplying-vector-by-scalar)

# 🟦 Multiplying a Vector by a Scalar

When we multiply a vector by a scalar (a regular number), we **scale** its magnitude while preserving or flipping its direction.

---

# 🟣 Examples

Given a 2D vector:

$$
\vec{a} = \begin{bmatrix} 2 \\ 1 \end{bmatrix}
$$

This means:

- Move **2 units right** (horizontal)
- Move **1 unit up** (vertical)

It's like giving directions: "Go 2 steps East, then 1 step North."

## 🟢 Example 1: Multiply by a Positive Scalar

### Multiply by 3

$$
\vec{a} = 3 \cdot \begin{bmatrix} 2 \\ 1 \end{bmatrix} = \begin{bmatrix} 6 \\ 3 \end{bmatrix}
$$

✅ **Effect**:

- Same direction as $\vec{a}$
- Magnitude is **3× longer**

🧠 Think of this like zooming in on the original vector. You’re stretching it by a factor of 3.

## 🔵 Example 2: Multiply by a Negative Scalar

### Multiply by -1

$$
\vec{a} = -1 \cdot \begin{bmatrix} 2 \\ 1 \end{bmatrix} = \begin{bmatrix} -2 \\ -1 \end{bmatrix}
$$

✅ **Effect**:

- **Flips direction**
- **Same magnitude**

🧠 This is like walking backwards the same distance you were walking forward.

## 🟠 Example 3: Multiply by -2

$$
-2\vec{a} = -2 \cdot \begin{bmatrix} 2 \\ 1 \end{bmatrix} = \begin{bmatrix} -4 \\ -2 \end{bmatrix}
$$

✅ **Effect**:

- **Flips direction**
- **Magnitude is 2× longer**

🧠 This is like doubling your backward stride.

---

# ✅ Key Takeaways

Original vector =
$$
\begin{bmatrix} 2 \\ 1 \end{bmatrix}
$$

| Scalar | Resulting Vector | Direction | Magnitude Effect |
| --- | --- | --- | --- |
| 3 | $[6, 3]$ | Same | 3× longer |
| -1 | $[-2, -1]$ | Opposite | Same |
| -2 | $[-4, -2]$ | Opposite | 2× longer |

💡 **Rule**:

$$
c\vec{a} = \begin{bmatrix} c \cdot a_1 \\ c \cdot a_2 \end{bmatrix}
$$

Where $c$ is a **scalar**, and
$$
\vec{a} = \begin{bmatrix} a_1 \\ a_2 \end{bmatrix}
$$