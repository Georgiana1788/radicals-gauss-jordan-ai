# Educational Notes – Radicals and the Gauss-Jordan Method

---

## What are radicals?

A **radical** is a mathematical operation that asks: “what number, when raised to a certain power, gives a specific result?”  
The most common radical is the **square root**: √x, which means “what number squared equals x?”

### Historical background:
- The radical symbol (√) was first used in 1525 by German mathematician **Christoff Rudolff**.
- The term “radical” comes from the Latin word *radix*, meaning “root”.

### Where are radicals used?
- In physics (speed, energy, wave functions)
- In economics (variance and standard deviation)
- In geometry (Pythagorean theorem)
- In computer science and engineering calculations

### How are radicals calculated?
- √9 = 3 because 3² = 9
- ∛27 = 3 because 3³ = 27
- √(x² + 2x + 1) = x + 1 (if x > 0)

---

## The Gauss-Jordan Method

### Short history:
- Named after **Carl Friedrich Gauss** and **Wilhelm Jordan** in the 19th century
- It extends Gaussian elimination to reduce a matrix to **row-reduced echelon form** (identity matrix)
- Used for solving systems of linear equations

### Where is it used?
- In algebra, engineering, network analysis, statistics
- In solving systems with 2, 3 or more variables

### How it works:
1. Write the system as an augmented matrix
2. Use row operations to transform it into this form:
   ```
   [1 0 0 | x]
   [0 1 0 | y]
   [0 0 1 | z]
   ```
3. Steps involve:
   - Creating pivot elements (=1)
   - Eliminating other entries in the column using row operations

It’s a logical, step-by-step method that guarantees an exact solution if the system is consistent.

---