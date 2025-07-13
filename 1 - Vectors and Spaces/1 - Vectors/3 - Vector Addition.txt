![Source: [Adding vectors algebraically & graphically (video) | Khan Academy](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/adding-vectors)](https://github.com/ariefzuhri/LinearAlgebra/blob/main/Resources/vector_addition_0.jpeg)

Source: [Adding vectors algebraically & graphically (video) | Khan Academy](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/vectors/v/adding-vectors)

# 🧮 Vector Addition in $\mathbb{R}^2$

## 📦 Given Vectors

We’re working with two 2D vectors:

- **Vector a**:
    
    $\vec{a} = \begin{bmatrix} 6 \\ -2 \end{bmatrix}$
    
    👉 Right 6 units, Down 2 units.
    
- **Vector b**:
    
    $\vec{b} = \begin{bmatrix} -4 \\ 4 \end{bmatrix}$
    
    👉 Left 4 units, Up 4 units.
    

Both vectors are elements of $\mathbb{R}^2$, meaning they live in 2D space.

---

# ➕ How Do We Add Vectors?

## 🧠 The Rule

Add **corresponding components**:

$\vec{a} + \vec{b} = \begin{bmatrix} 6 \\ -2 \end{bmatrix} + \begin{bmatrix} -4 \\ 4 \end{bmatrix} = \begin{bmatrix} 2 \\ 2 \end{bmatrix}$

So the result is another 2D vector:

**"Right 2 units, Up 2 units."**

This also works in reverse:

$\vec{b} + \vec{a} = \vec{a} + \vec{b} = \begin{bmatrix} 2 \\ 2 \end{bmatrix}$

### 🔁 Commutativity

Vector addition is **commutative**, just like adding numbers:

$\vec{a} + \vec{b} = \vec{b} + \vec{a}$

---

# 🧭 Visualizing Vector Addition

## 🖼️ Diagram Breakdown

In the image:

- **Magenta vectors** = copies of $\vec{a}$
- **Teal/green vectors** = copies of $\vec{b}$
- **Blue vector** = the resulting sum $\vec{a} + \vec{b}$

## ✍️ Interpretation

### 🧷 Method 1: Tip-to-Tail

To add two vectors:

1. Start with the tail of $\vec{a}$ at the origin.
2. Place the **tail of $\vec{b}$** at the **tip of $\vec{a}$**.
3. Draw a vector from the origin to the new tip → this is $\vec{a} + \vec{b}$.

💡 It’s like:

> Walking 6 steps east and 2 steps south, then 4 steps west and 4 steps north. Your final position is just 2 steps east and 2 steps north of where you started.
> 

### 🔁 Method 2: $\vec{b} + \vec{a}$

Flip the order:

1. Start with vector $\vec{b}$ (tail at origin).
2. Put $\vec{a}$ at the tip of $\vec{b}$.
3. Again, draw the vector from origin to the new tip → it’s still $\begin{bmatrix}2 \\ 2\end{bmatrix}$.

No matter the order, **the result is the same**. That’s the magic of vector addition in Euclidean space 🎇.

---

# 🧠 Conceptual Sense

- Vectors are **not fixed in space**: Only magnitude + direction matter.
- You can **slide** them around the graph — just don’t rotate or stretch them.
- The **sum vector** represents the **total displacement** after two moves.

👟 It’s like walking from home to the café (vector a), then from the café to the bookstore (vector b). The sum vector is your direct path from home to the bookstore.

---

# 🧪 Vector Addition Applies To...

- Displacement
- Velocity
- Acceleration
- Forces
- Anything where **direction + magnitude** matter.

---

# ✅ Key Takeaways

| Concept | Description |
| --- | --- |
| Vector notation | $\vec{v} = \begin{bmatrix} x \\ y \end{bmatrix}$ |
| Vector addition | Add components: $\vec{a} + \vec{b} = \begin{bmatrix} a_x + b_x \\ a_y + b_y \end{bmatrix}$ |
| Commutative property | $\vec{a} + \vec{b} = \vec{b} + \vec{a}$ |
| Visual interpretation | Tip-to-tail method → sum is vector from start to final tip |
| Vectors are movable | Direction + magnitude matter, position does not |
| Result in $\mathbb{R}^2$ | Sum of two 2D vectors is still a 2D vector |