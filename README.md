# Vector Equilibrium Solver (C++)

## 📝 Problem Description
This program determines whether a system of forces acting on a body in a 3D space is in equilibrium. It calculates the sum of all components ($x, y, z$) of the given vectors and checks if the resultant force equals zero.

## 🚀 Optimization Features
* **Fast I/O Operations:** Uses `ios_base::sync_with_stdio(false);` and `cin.tie(nullptr);` to decouple standard C and C++ streams. This significantly speeds up execution time when handling large input datasets.
* **Space Complexity:** $O(1)$ auxiliary space, as it processes inputs dynamically on the fly without storing them in arrays or vectors.
* **Time Complexity:** $O(n)$ where $n$ is the number of coordinate triplets.

## 🛠️ How to Compile & Run
Ensure you have a GCC compiler installed. Run the following commands in your terminal:
```bash
g++ -O3 main.cpp -o solver
./solver
