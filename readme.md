# Hamiltonian Graphs: Theory, Theorems & Interactive Sandbox

An interactive web-based educational platform designed to visualize, trace, and analyze **Hamiltonian Graphs**, **Hamiltonian Paths**, and **Hamiltonian Cycles**. Featuring an interactive graph sandbox with dedicated buttons for node/edge addition and deletion, step-by-step traversal playback controls, backtracking cycle/path solvers, and rigorous mathematical theorems.

🚀 **Live Demo:** [https://surajit-sahoo-iitian.github.io/Hamiltonian-Graph-Interactive-Visualization/](https://surajit-sahoo-iitian.github.io/Hamiltonian-Graph-Interactive-Visualization/)

## ✨ Features

- 📖 **Rigorous Mathematical Framework**: Comprehensive coverage of Hamiltonian paths vs. cycles, mandatory connectedness, necessary degree conditions ($\delta(G) \geq 2$), cut-vertex restrictions, and the vertex subset connected components theorem ($c(G - S) \leq |S|$).
- 📐 **Sufficient Conditions (Dirac's & Ore's Theorems)**: Clear explanations of degree bounds ($\deg(v) \geq n/2$ and $\deg(u) + \deg(v) \geq n$ for every pair of distinct nonadjacent vertices $u, v$) that guarantee Hamiltonicity.
- 🕹️ **Interactive Traversal Engine**:
  - Select custom **Start Vertex**.
  - Controls: **Play**, **Pause**, **Stop**, **Next Step**, **Previous Step**.
  - Backtracking solver that detects Hamiltonian cycles or paths and provides real-time status updates (*"Hamiltonian Cycle Found!"*, *"Hamiltonian Path Found!"*, or *"No Hamiltonian Path or Cycle"*).
- 🛠️ **Custom Sandbox**:
  - Explicit mode toolbar: **Add Node**, **Add Edge**, and **Delete Mode** (click any node or edge to remove it instantly).
- 🎨 **Responsive UI**: Built with Tailwind CSS and HTML5 Canvas for ultra-smooth rendering.

---

## 📂 Repository Structure

```text
.
├── index.html                  # Main interactive Hamiltonian web application
└── README.md                   # Project documentation
```

---

## 🚀 Quick Setup & Deployment

### 1. Run Locally (VS Code)
1. Clone this repository or download the source code:
   ```bash
   git clone https://github.com/Surajit-Sahoo-IITIAN/Hamiltonian-Graph-Interactive-Visualization.git
   ```
2. Open the project folder in **VS Code**.
3. Launch `index.html` using the **Live Server** extension (or double-click `index.html` to open directly in any web browser).

### 2. Deploy to GitHub Pages (`github.io`)
1. Push your `index.html` and `README.md` files to your main GitHub repository branch.
2. Go to **Settings** > **Pages** in your repository.
3. Under **Branch**, select `main` (or `master`) and save.
4. Your site will be live at:
   `https://Surajit-Sahoo-IITIAN/<repository-name>/`

---

## 🧮 Mathematical Background

### Mandatory Connectedness & Necessary Conditions
- **Connectedness**: Connectedness is mandatory for any graph containing a Hamiltonian path or cycle.
- **Minimum Degree**: If a simple graph $G$ with $n \geq 3$ vertices is Hamiltonian, then every vertex has degree at least two:
  $$\delta(G) \geq 2$$
- **Connected Components Theorem**: If $G$ is Hamiltonian, then for every nonempty proper subset $S \subset V(G)$, the number of connected components of $G-S$ cannot exceed the size of $S$:
  $$c(G - S) \leq |S|$$

### Sufficient Conditions (Dirac's & Ore's Theorems)
- **Dirac's Theorem**: Let $G$ be a simple graph with $n \geq 3$ vertices. If $\deg(v) \geq n/2$ for every $v \in V(G)$, then $G$ is Hamiltonian.
- **Ore's Theorem**: Let $G$ be a simple graph with $n \geq 3$ vertices. If $\deg(u) + \deg(v) \geq n$ for every pair of distinct nonadjacent vertices $u, v$, then $G$ is Hamiltonian.

---

## 📜 Copyright & Attribution

Created and authorized by **Surajit Sahoo**.  
Distributed for open educational use under the MIT License.
