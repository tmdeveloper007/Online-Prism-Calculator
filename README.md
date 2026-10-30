# Online Prism Calculator

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Website](https://img.shields.io/badge/Website-onlineprismcalculator.com-0070f3.svg?style=flat-square)](https://onlineprismcalculator.com)

**Online Prism Calculator** is an interactive geometric calculation and real-time 3D visualization suite for prisms and spatial polyhedra. Built for students, educators, architects, and engineers, it pairs analytical precision with interactive spatial models, dynamic 2D unfolded nets, and step-by-step mathematical derivations.

**Live Application:** [onlineprismcalculator.com](https://onlineprismcalculator.com)

---

## Features

- **Interactive 3D Visualization**: Orbit, pan, and inspect polyhedra in real time with solid, translucent glass, and wireframe skeleton viewing modes.
- **Space Diagonal & Liquid Fill Simulation**: Visualize internal 3D diagonal vectors with their base projections, and simulate volumetric liquid capacity levels.
- **Step-by-Step Derivations**: View complete Euclidean proofs and algebraic substitutions with intermediate working and configurable precision.
- **Bidirectional Solvers**: Calculate forward properties (volume, total surface area, lateral area, base perimeter, space diagonals) or solve inverse dimensions (e.g., finding height from volume or surface area).
- **Dynamic 2D Unfolded Nets**: Inspect real-time planar nets illustrating how 3D polyhedra unfold into 2D patterns.
- **Multi-Unit Support**: Seamlessly convert between metric and imperial units for length, surface area, volume, and fluid capacity ($mm$, $cm$, $m$, $in$, $ft$, $yd$, $L$, $mL$).

---

## Supported Geometries

| Prism Type | Base Shape | Supported Calculations |
| :--- | :--- | :--- |
| **Rectangular Prism** | Rectangle ($l \times w$) | Volume, Surface Area, Space Diagonal, Height, Base Area |
| **Cube** | Square ($a \times a$) | Volume, Total Surface Area, Face/Space Diagonals |
| **Triangular Prism** | Base & Height / Equilateral / Scalene (Heron) | Cross-Section Area, Volume, Lateral & Total Surface Area |
| **Trapezoidal Prism** | Trapezoid ($a, b, h_t$) | Trough Volume, Slanted Edges, Capacity in Liters |
| **Hexagonal Prism** | Regular Hexagon | Base Area, Volume, Long & Short Space Diagonals |
| **Pentagonal Prism** | Regular Pentagon | Base Area, Volume, Total Surface Area |

---

## Key Formulas

For any right prism with base area $B$, base perimeter $P$, and height $h$:

- **Volume:**  
  $$V = B \cdot h$$
- **Lateral Surface Area:**  
  $$L = P \cdot h$$
- **Total Surface Area:**  
  $$S = 2B + L = 2B + P \cdot h$$
- **Space Diagonal (Cuboid):**  
  $$d = \sqrt{l^2 + w^2 + h^2}$$
- **Inverse Height:**  
  $$h = \frac{V}{B} = \frac{S - 2B}{P}$$

---

## Getting Started

### Prerequisites

- Node.js (v20+ or v22+ recommended)
- npm, pnpm, or yarn

### Quick Start

```bash
# Clone the repository
git clone https://github.com/tmdeveloper007/onlineprismcalculator.com.git
cd onlineprismcalculator.com

# Install dependencies
npm install

# Start local development server
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

### Production Build

```bash
# Build static production bundle
npm run build

# Preview build locally
npm run preview
```

---

## License

This project is licensed under the [MIT License](LICENSE).
